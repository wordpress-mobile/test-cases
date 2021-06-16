# Unsupported Block Editing - Test Cases

--------------------------------------------------------------------------------
## Test Checklist
```
### Unsupported Block Tests
- [ ] TC001 User can edit unsupported blocks on Simple WP.com sites
- [ ] TC002 User can discard edits to an unsupported block on Simple WP.com sites
- [ ] TC003 Editing unsupported blocks is allowed on Gutenberg-enabled Atomic sites
- [ ] TC004 Editing unsupported blocks is disallowed on Classic-enabled Atomic sites
- [ ] TC005 Editing unsupported blocks is enabled on self-hosted sites accessed via Jetpack
- [ ] TC006 Editing unsupported blocks is disallowed on self-hosted sites access via their own username and password
```
--------------------------------------------------------------------------------

##### TC001

#### Precondition

A WP.com Simple site (i.e. not an Atomic site). Any free WP.com site should suffice.

### User can edit unsupported blocks on Simple WP.com sites

1. On the site described above, add a post, then add a block that's not yet supported on mobile
2. Log into the WordPress mobile app using the site's WP.com account
3. Open the post and expect to see the block rendered as a placeholder with the text "Unsupported"
4. Tap the `(?)` icon and expect the option to edit the block in a web browser to be shown
5. Tap the edit in a web browser button and expect the block to be shown, ready to edit, on a new screen
6. Edit the block content
7. Tap the Continue button and expect to be taken back to the block editor
8. Publish the post and verify it contains the edits


##### TC002

**Known Issues**
-  **[Android-only]** The update button is not greyed-out when changes are discarded

### User can discard edits to an unsupported blocks on Simple WP.com sites

1. Repeat steps 1 to 6 from TC001 above
2. Tap the Cancel button to discard changes and expect to be taken back to the block editor
3. Expect the Update button to be greyed-out
4. Using HTML mode in the editor, view the HTML content of the post and expect it to **not** contain any of the edits


##### TC003

**Known Issues**
- [Editing unsupported blocks is not enabled on sites accessed via older WP.com accounts](https://github.com/wordpress-mobile/gutenberg-mobile/issues/3425)

#### Precondition

A WP.com Atomic site (i.e. a WP.com site with a Business plan) with the **Gutenberg Editor** set as the default. Here are the steps for creating this if necessary:

1. Find a site with a Business plan or higher
2. Find an account created in 2019 or later (account age is found under https://wordpress.com/me/account), otherwise the known issue listed above will break the Unsupported Block Editor
3. In Calypso choose your site and go to Tools | Plugins | Installed Plugins — ensure the Classic Editor plugin is **not** installed (or if it is installed, make sure it is not the default editor in the plugin settings)

### Editing unsupported blocks is allowed on Gutenberg-enabled Atomic sites

1. On the site described above, add a post, then add a block that's not yet supported on mobile
2. Log into the WordPress mobile app using the site's WP.com account
3. Open the post and expect to see the block rendered as a placeholder with the text "Unsupported"
4. Tap the `(?)` icon and expect the option to edit the block in a web browser to be shown
5. Tap the edit in a web browser button and expect the block to be shown, ready to edit, on a new screen
6. Edit the block content
7. Tap the Continue button and expect to be taken back to the block editor
8. Publish the post and verify it contains the edits


##### TC004

**Known Issues**
- [Editing unsupported blocks is not enabled on sites accessed via older WP.com accounts](https://github.com/wordpress-mobile/gutenberg-mobile/issues/3425)
- [Editing unsupported blocks is not disallowed on Classic-enabled Atomic sites](https://github.com/wordpress-mobile/gutenberg-mobile/issues/3544)

#### Precondition

A WP.com Atomic site (i.e. a WP.com site with a Business plan) with the **Classic editor** set as the default. Here are the steps for creating this if necessary:

1. Find a site with a Business plan or higher
2. Find an account created in 2019 or later (account age is found under https://wordpress.com/me/account), otherwise the known issue listed above will break the Unsupported Block Editor
3. Install and activate the Classic Editor plugin
4. In Calypso choose your site and go to Tools | Plugins | Installed Plugins, then tap Settings under the Classic Editor plugin and set **Default editor for all users** to **Classic Editor**

### Editing unsupported blocks is disallowed on Classic-enabled Atomic sites

**Please note that this must be skipped until the above known issue, [Editing unsupported blocks is not disallowed on Classic-enabled Atomic sites](https://github.com/wordpress-mobile/gutenberg-mobile/issues/3544), is fixed.**

1. On the site described above, add a post, then add a block that's not yet supported on mobile
2. Log into the WordPress mobile app using the site's WP.com account
3. Open the post and expect to see the block rendered as a placeholder with the text "Unsupported"
4. Tap the `(?)` icon and expect to **not** see an option to edit the block in a web browser


##### TC005

**Known Issues**
- [Editing unsupported blocks is not enabled on sites accessed via older WP.com accounts](https://github.com/wordpress-mobile/gutenberg-mobile/issues/3425)

#### Precondition

For this test, you need a self-hosted site with the Jetpack plugin installed, activated and connected to a WP.com account. Here are the steps for creating this if needed:

1. Log into a WP.com account
1. Create a site on https://jurassic.ninja/
2. Connect Jetpack to the signed in WP.com account 
3. Visit https://wordpress.com/settings/security, choose newly created site and enable "WordPress.com log in"
4. By default, Gutenberg is the default editor so no action required there

### Editing unsupported blocks is enabled on self-hosted sites accessed via Jetpack

1. On the site described above, add a post, then add a block that's not yet supported on mobile via the site's WP Admin web interface
2. Log into the WordPress mobile app using the WP.com account that was used to connect Jetpack to the self-hosted site
3. Open the post and expect to see the unsupported block rendered as a placeholder with the text "Unsupported"
4. Tap the `(?)` icon and expect the option to edit the block in a web browser to be shown 
5. Tap the edit in a web browser button and expect a web view requesting to `Login with WordPress.com`
6. Tap on said option and expect the block to be shown, ready to edit, on a new screen
7. Edit the block content
8. Tap the Continue button and expect to be taken back to the block editor
9. Publish the post and verify it contains the edits


##### TC006

#### Precondition

For this test, you need a self-hosted site with its own login credentials (we're not going to access the app using WP.com credentials). Here are the steps for creating this if needed:

1. Create a site on https://jurassic.ninja/
2. It doesn't matter if the Jetpack plugin (which comes pre-installed) is connected or not to a WP.com account, we're going to access the site by its own credentials
3. By default, Gutenberg is the default editor so no action required there
4. In the Dashboard, make note of the site username and password

### Editing unsupported blocks is disallowed on self-hosted sites accessed via their own username and password

1. On the site described above, add a post, then add a block that's not yet supported on mobile via the site's WP Admin web interface
2. Log into the WordPress mobile app by adding the site address and subsequently authenticating with the site username and password
3. Open the post and expect to see the unsupported block rendered as a placeholder with the text "Unsupported"
4. Tap the `(?)` icon and expect to **not** see an option to edit the block in a web browser

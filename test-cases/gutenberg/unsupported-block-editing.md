# Unsupported Block Editing - Test Cases

--------------------------------------------------------------------------------

##### TC001

### User can edit unsupported blocks on regular WP.com sites

1. On a regular WP.com site (i.e. not Atomic), add a block that's not yet supported on mobile (e.g. the Jetpack Markdown `jetpack/markdown` block) — this can be done by switching to HTML mode and pasting in the raw content (or by adding it via WordPress.com, where it is supported)

    Example HTML:
```
<!-- wp:jetpack/markdown {"source":"This is a \nnew line"} -->
<div class="wp-block-jetpack-markdown"><p>This is a
new line</p>
</div>
<!-- /wp:jetpack/markdown -->
```
2. Switch back to Visual mode if needed
3. Expect to see the block rendered as a placeholder with the text "Unsupported"
4. Tap the `(?)` icon and expect the option to edit the block in a web browser to be shown
5. Tap the edit in a web browser and expect the block to be shown, ready to edit, in a new screen
6. Edit the block content (e.g. update its text)
7. Tap the Continue button and expect to be taken back to the block editor
8. Publish the post and verify it contains the edited block content


##### TC002

**Known Issues**
-  **[Android-only]** The update button is not greyed-out when changes are discarded

### Ensure discarded edits are not persisted

1. Repeat steps 1 to 5 above
2. Edit the block content (e.g. update its text)
3. Tap the Cancel button to discard changes and expect to be taken back to the block editor
4. Expect the Update button to be greyed-out
5. Using HTML mode in the editor, view the HTML content of the post and expect it to **not** contain any of the changes

##### TC003

### User can edit unsupported blocks on regular WP.com Business (Atomic) sites

Repeat steps from TC001 using a post on a WP.com site with a Business Plan (i.e. Atomic site)

##### TC004

**Known Issues**
- This feature [not available on Jetpack connected self-hosted sites](https://github.com/wordpress-mobile/gutenberg-mobile/issues/2471)

### Self-hosted sites are supported (if they are not connected to WordPress via Jetpack)

Repeat steps from TC001 using a post on a .org site (self-hosted) that does not have Jetpack connected

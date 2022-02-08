# Editor Theme - Test Cases

--------------------------------------------------------------------------------

##### TC001

### Default Colors - Check that default colors still load

When a theme doesn't have any custom colors defined the editor should allow selection from the default color palette and display them.

***Note:*** the following can be tested with the theme [Blask v1.1.2](https://wordpress.com/theme/blask) - [Download](https://public-api.wordpress.com/rest/v1/themes/download/blask.zip)

**Steps:**
- Select and activate a theme without any custom colors
- Create a new post or page or open one with one of the supported blocks
- Edit the color on a block that supports theme colors such as Buttons or Cover

**Expected behavior:**

- Expect to see the [default colors](https://github.com/WordPress/gutenberg/blob/2822c999921afb8f4cbdbb94a48ec4a92aec6a9b/packages/block-editor/src/store/defaults.js#L40-L97) in the color picker
- Expect to see the block to display the selected color

--------------------------------------------------------------------------------

##### TC002

### Default Gradients - Check that default gradients still load

When a theme doesn't have any custom gradients defined the editor should allow selection from the default gradient list and display them.

***Note:*** the following can be tested with the theme [Blask v1.1.2](https://wordpress.com/theme/blask) - [Download](https://public-api.wordpress.com/rest/v1/themes/download/blask.zip)

**Steps:**
- Select and activate a theme without any custom gradients
- Create a new post or page or open one with one of the supported blocks
- Edit the gradient on a block that supports theme gradients such as Buttons or Cover

**Expected behavior:**

- Expect to see the [default gradients](https://github.com/WordPress/gutenberg/blob/2822c999921afb8f4cbdbb94a48ec4a92aec6a9b/packages/block-editor/src/store/defaults.js#L156-L229) in the color/gradient picker
- Expect to see the block to display the selected gradient

--------------------------------------------------------------------------------

##### TC003

### Custom Colors - Check that custom colors load in the editor

When a theme has a custom color palette defined the editor should allow selection from the custom colors and display them.

***Note:*** The following can be tested with the theme [Seedlet](https://wordpress.com/theme/seedlet) - [Download](https://public-api.wordpress.com/rest/v1/themes/download/seedlet.zip)

**Steps:**
- Select and activate a theme with custom colors
- Create a new post or page or open one with one of the supported blocks
- Edit the color on a block that supports theme colors such as Buttons or Cover

**Expected behavior:**

- Expect to see the colors provided by the theme
- Expect to see the block to display the selected color

--------------------------------------------------------------------------------

##### TC004

### Custom Gradients - Check that custom gradients load in the editor

When a theme has a custom gradients defined the editor should allow selection from the custom gradients and display them.

***Note:*** the following can be tested with the theme [Seedlet](https://wordpress.com/theme/seedlet) - [Download](https://public-api.wordpress.com/rest/v1/themes/download/seedlet.zip)

**Steps:**
- Select and activate a theme with custom gradients
- Create a new post or page or open one with one of the supported blocks
- Edit the gradient on a block that supports theme gradients such as Buttons or Cover

**Expected behavior:**

- Expect to see the gradients provided by the theme
- Expect to see the block to display the selected gradient

--------------------------------------------------------------------------------

##### TC005

### Offline Support

When a theme has a custom colors and/or gradients defined the editor should display the theme when offline.

***Note:*** the following can be tested with the theme [Seedlet](https://wordpress.com/theme/seedlet) - [Download](https://public-api.wordpress.com/rest/v1/themes/download/seedlet.zip)

**Steps:**
- Select and activate a theme with custom colors and/or gradients.
- Open the editor for the site in app. This will make the initial cache.
- Leave the editor and take your device offline by enabling airplane mode and/or disabling WiFi.
- Open the editor again (feel free to experiment by closing the editor)

**Expected behavior:**

- Expect to see the custom colors and/or gradients provided by the theme in the color picker
- Expect to see any previously configured blocks to display the selected colors/gradients.

--------------------------------------------------------------------------------

##### TC006

### FSE Colors and Gradients

When a theme supports FSE validate that theme colors and gradients still load.

***Note:*** The following can be tested with the theme [TT1 Blocks](https://wordpress.org/themes/tt1-blocks/) - [Download](https://downloads.wordpress.org/theme/tt1-blocks.0.4.5.zip)

**Steps:**
- Select and activate a theme that supports FSE and Global Styles.
- On the Web add a custom color or gradient then go back to the app.
- Create a new post or page or open one with one of the supported blocks
- Edit the color options on a block that supports color settings such as Buttons or Cover

**Expected behavior:**

- Expect to see the the same color options available on web including your custom selection.
- Expect to see the block to display the selected option.

--------------------------------------------------------------------------------

##### TC007

### FSE Offline Support

Perform the same setup as [TC006](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/editor-theme.md#tc006)

**Steps:**
- After doing [TC006](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/editor-theme.md#tc006) take your device offline.
- Create a new post or page
- Edit the color options on a block that supports color settings such as Buttons or Cover =
    - Verify the expected behavior
- Reopen your artifact from [TC006](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/editor-theme.md#tc006)
    - Verify the expected behavior
	
**Expected behavior:**

- Expect to see the the same color options available on web including your custom selection.
- Expect to see the block to display the selected option.

--------------------------------------------------------------------------------

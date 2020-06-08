# Editor Theme - Test Cases

--------------------------------------------------------------------------------

##### TC001

### Default Colors - Check that default colors still load

When a theme doesn't have any custom colors defined the editor should allow selection from the default color palette and display them.

***Note:*** the following can be tested with the theme [Blask v1.1.2](https://wordpress.com/theme/blask) - [Download](https://public-api.wordpress.com/rest/v1/themes/download/blask.zip)

**Steps:**
- Select and activate a theme without any custom colors
- Create a new post or page or open one with on of the supported blocks
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
- Create a new post or page or open one with on of the supported blocks
- Edit the gradient on a block that supports theme gradients such as Buttons or Cover

**Expected behavior:**

- Expect to see the [default gradients](https://github.com/WordPress/gutenberg/blob/2822c999921afb8f4cbdbb94a48ec4a92aec6a9b/packages/block-editor/src/store/defaults.js#L156-L229) in the color/gradient picker
- Expect to see the block to display the selected gradient

--------------------------------------------------------------------------------

##### TC003

### Custom Colors - Check that custom colors load in the editor

When a theme has a custom color palette defined the editor should allow selection from the custom colors and display them.

***Note:*** the following can be tested with the theme [Twenty Twenty](https://wordpress.com/theme/twentytwenty) - [Download](https://public-api.wordpress.com/rest/v1/themes/download/twentytwenty.zip)

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

***Note:*** the following can be tested with the theme [Twenty Twenty - Copy](../resources/twentytwenty-copy.zip) - [Download](../resources/twentytwenty-copy.zip)

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

***Note:*** the following can be tested with the theme [Twenty Twenty - Copy](../resources/twentytwenty-copy.zip) - [Download](../resources/twentytwenty-copy.zip)

**Steps:**
- Select and activate a theme with custom colors and/or gradients.
- Open the editor for the site in app. This will make the initial cache.
- Leave the editor and take your device offline by enabling airplane mode and/or disabling WiFi.
- Open the editor again (feel free to experiment by closing the editor)

**Expected behavior:**

- Expect to see the custom colors and/or gradients provided by the theme in the color picker
- Expect to see any previously configured blocks to display the selected colors/gradients.

--------------------------------------------------------------------------------


# Buttons Block - Test Cases

--------------------------------------------------------------------------------

##### TC001

### Buttons block is added with focused Button with gray background color and white text color

-   Add `Buttons` block
-   Expect to see focused `Button` inside `Buttons` block
-   Expect gray background color and white text

--------------------------------------------------------------------------------

##### TC002

### Removing exactly one Button (when Buttons contain more of them)

-   Add `Buttons` block
-   Press an inline appender
-   Expect a new `Button` is added and focused
-   Press trash button
-   Expect current `Button` is removed and the previous `Button` is focused
-   Press an inline appender
-   Expect a new `Button` is added and focused
-   Type something
-   Delete all of the text from Button
-   Expect current `Button` is removed and the previous `Button` is focused

--------------------------------------------------------------------------------

##### TC003

### Wrapping Buttons

-   Add `Buttons` block
-   Press an inline appender
-   Expect a new `Button` is added and focused
-   Select the first `Button`
-   Type some characters to fill `Button` width
-   Expect the second `Button` to fall into the second row

--------------------------------------------------------------------------------

##### TC004

### Buttons alignment options

-   Add `Buttons` block
-   Press inline appender
-   Expect a new `Button` is added and focused
-   Navigate up to select `Buttons`
-   Use alignment options
-   Expect:
      - Buttons adhere to the left edge when the first option is selected
      - Buttons are centred when the second option is selected
      - Buttons adhere to the right edge when the third option is selected

--------------------------------------------------------------------------------

##### TC005

### Edit text styles

-   Add `Buttons` block
-   Type some characters
-   Select your text
-   Press icons responsible for changing text styles: `Bold`, `Italic`, `Strikethrough`
-   Save the post
-   Open a post e.g in preview mode
-   Expect text style changes accordingly to selected options

--------------------------------------------------------------------------------

##### TC006

### Settings: Link URL

-   Add `Buttons` block
-   Open link [settings](../resources/button-link-settings.png)
-   Edit `Button URL` field and add link
-   Save the post
-   Open a post e.g. in preview mode
-   Expect Button is redirecting to the added link

--------------------------------------------------------------------------------

##### TC007

### Settings: Open in new tab

-   Add `Buttons` block
-   Open link [settings](../resources/button-link-settings.png)
-   Switch on `Open in new tab`
-   Expect `noreferrer noopener` is added automatically in `Link Rel` field
-   Save the post
-   Open a post e.g. in preview mode
-   Expect Button is opening a link in new tab

--------------------------------------------------------------------------------

##### TC008

### Settings: Link rel

-   Add `Buttons` block
-   Open link [settings](../resources/button-link-settings.png)
-   Edit `Link Rel` field and add link rel e.g `noreferrer`
-   Open link [settings](../resources/button-link-settings.png) again
-   Expect link rel is saved

--------------------------------------------------------------------------------

##### TC009

### Settings: Synchronize with button options

-   Add `Buttons` block
-   Open link [settings](../resources/button-link-settings.png)
-   Edit `Button URL` field and add link
-   Switch on `Open in new tab`
-   Edit `Link Rel` field and add rel
-   Open button [options](../resources/button-options.png)
-   Expect fields `Button URL`, `Open in new tab`, `Link Rel` to have the same content as in link settings

--------------------------------------------------------------------------------

##### TC010

### Settings: Remove link

-   Add `Buttons` block
-   Open link [settings](../resources/button-link-settings.png)
-   Edit `Button URL` field and add link
-   Switch on `Open in new tab`
-   Edit `Link Rel` field and add rel
-   Press `Remove link` button
-   Open link settings again
-   Expect default settings

--------------------------------------------------------------------------------

##### TC011

### Settings: Change Button border radius

-   Add `Buttons` block
-   Open button [options](../resources/button-options.png)
-   Edit `Border Radius` moving slider
-   Expect Button border radius changed accordingly to the value
-   Edit `Border Radius` typing border radius value in input
-   Expect Button border radius changed accordingly to the value

--------------------------------------------------------------------------------

##### TC012

### Render custom background color

-   Open gutenberg web, add `Buttons` block
-   Choose the **custom** background color from **picker**
-   Save the post
-   Open the same post on mobile app
-   Expect `Button` background color is the same as on web

--------------------------------------------------------------------------------

##### TC013

### Render custom text color

-   Open gutenberg web, add `Buttons` block
-   Choose the **custom** text color from **picker**
-   Save the post
-   Open the same post on mobile app
-   Expect `Button` text color is the same as on web

--------------------------------------------------------------------------------

##### TC014

### Render gradient background color

-   Open gutenberg web, add `Buttons` block
-   Choose the **gradient** background color from the palette
-   Save the post
-   Open the same post on mobile app
-   Expect `Button` gradient background color is the same as on web

--------------------------------------------------------------------------------

##### TC015

### Render theme colors

-   Open gutenberg web, add `Buttons` block
-   Choose a theme color from the **palette* (among the predefined ones)
-   Save the post
-   Open the same post on mobile app
-   Expect `Button` with selected background color and selected text color

--------------------------------------------------------------------------------

##### TC016

### Check if selection / caret color matches font color

-   Open gutenberg web, add `Buttons` block
-   Choose the **custom** text color from **picker**
-   Save the post
-   Open the same post on mobile app
-   Observe caret / select text
-   Expect `Button` caret / selection color to match the custom text color

**_Note:_** This may work if running on Android API 28+ do to restrctions that will be handled as part of [Issue #1787](https://github.com/wordpress-mobile/gutenberg-mobile/issues/1787)

--------------------------------------------------------------------------------

##### TC017

### The newly created button has set background color to the theme-default color in preview

-   Add `Buttons` block
-   Save the post
-   Open a post e.g in preview mode
-   Expect `Button` with background color consistent with theme-default color

--------------------------------------------------------------------------------

##### TC018

### Toolbar link button is active when Button has link

-   Add `Buttons` block
-   Open link [settings](../resources/button-link-settings.png)
-   Edit `Button URL` field and add link
-   Close bottom-sheet
-   Expect toolbar link button is active

--------------------------------------------------------------------------------

##### TC019

### Button's wrapper grows properly

-   Add `Buttons` block
-   Add next button using inline appender or inserter
-   Select the first one and type some characters
-   Expect button's width grows properly (_horizontally_)

--------------------------------------------------------------------------------

##### TC020

### Link from the clipboard is presented as an option in the link picker

-   Copy link into clipboard, e.g. `http://wordpress.com`
-   Add `Buttons` block
-   Open link [settings](../resources/button-link-settings.png)
-   Edit the `Link to` field.
-   Tap the `From clipboard` option.
-   Expect link from the clipboard to be automatically added into the empty URL field

--------------------------------------------------------------------------------
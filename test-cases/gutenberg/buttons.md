
# Buttons Block - Test Cases

--------------------------------------------------------------------------------

##### TC001

### Buttons block is added with focused Button with gray background color and white text color

-   Add `Buttons` block
-   Expect to see focused `Button` inside `Buttons` block
-   Expect gray background color and white text

--------------------------------------------------------------------------------

##### TC002

### Buttons inline appender

-   Add `Buttons` block
-   Expect an inline appender is located next to the last `Button` block
-   Add another `Button` within `Buttons`
-   Expect an inline appender is located next to the last `Button` block
-   Navigate up to select `Buttons`
-   Expect an inline appender is in the same place (next to the last `Button` block)
-   Select different block than `Buttons` or `Button`
-   Expect to not see an inline appender in `Buttons` block

--------------------------------------------------------------------------------

##### TC003

### Add another Button inside Buttons using inserter

-   Add `Buttons` block
-   Press inserter
-   Choose `Button` from the opened bottom sheet
-   Expect `ADD BLOCK HERE` line isn't displayed
-   Expect a new `Button` is added and focused
-   Expect Buttons are displayed side-by-side

--------------------------------------------------------------------------------

##### TC004

### Removing Button along with Buttons block

-   Add `Buttons` block
-   Expect focused `Button` inside `Buttons`
-   Press trash button
-   Expect `Button` is removed along with whole `Buttons` container
-   Add new `Buttons` block
-   Expect focused `Button` inside `Buttons`
-   Type something
-   Delete all of the text from `Button`
-   Expect `Button` is removed along with whole `Buttons` container

--------------------------------------------------------------------------------

##### TC005

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

##### TC006

### Wrapping Buttons

-   Add `Buttons` block
-   Press an inline appender
-   Expect a new `Button` is added and focused
-   Select the first `Button`
-   Type some characters to fill `Button` width
-   Expect the second `Button` to fall into the second row

--------------------------------------------------------------------------------

##### TC007

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

##### TC008

### Link from the clipboard is automatically added into the empty URL field in link settings and button options

-   Copy link into clipboard, e.g. `http://wordpress.com`
-   Add `Buttons` block
-   Open link [settings](../resources/button-link-settings.png)
-   Expect link from the clipboard to be automatically added into the empty URL field

--------------------------------------------------------------------------------

##### TC009

### Edit text styles

-   Add `Buttons` block
-   Type some characters
-   Select your text
-   Press icons responsible for changing text styles: `Bold`, `Italic`, `Strikethrough`
-   Save the post
-   Open a post e.g in preview mode
-   Expect text style changes accordingly to selected options

--------------------------------------------------------------------------------

##### TC010

### Settings: Link URL

-   Add `Buttons` block
-   Open link [settings](../resources/button-link-settings.png)
-   Edit `Button URL` field and add link
-   Save the post
-   Open a post e.g. in preview mode
-   Expect Button is redirecting to the added link

--------------------------------------------------------------------------------

##### TC011

### Settings: Open in new tab

-   Add `Buttons` block
-   Open link [settings](../resources/button-link-settings.png)
-   Switch on `Open in new tab`
-   Expect `noreferrer noopener` is added automatically in `Link Rel` field
-   Save the post
-   Open a post e.g. in preview mode
-   Expect Button is opening a link in new tab

--------------------------------------------------------------------------------

##### TC012

### Settings: Link rel

-   Add `Buttons` block
-   Open link [settings](../resources/button-link-settings.png)
-   Edit `Link Rel` field and add link rel e.g `noreferrer`
-   Open link [settings](../resources/button-link-settings.png) again
-   Expect link rel is saved

--------------------------------------------------------------------------------

##### TC013

### Settings: Synchronize with button options

-   Add `Buttons` block
-   Open link [settings](../resources/button-link-settings.png)
-   Edit `Button URL` field and add link
-   Switch on `Open in new tab`
-   Edit `Link Rel` field and add rel
-   Open button [options](../resources/button-options.png)
-   Expect fields `Button URL`, `Open in new tab`, `Link Rel` to have the same content as in link settings

--------------------------------------------------------------------------------

##### TC014

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

##### TC015

### Settings: Change Button border radius

-   Add `Buttons` block
-   Open button [options](../resources/button-options.png)
-   Edit `Border Radius` moving slider
-   Expect Button border radius changed accordingly to the value
-   Edit `Border Radius` typing border radius value in input
-   Expect Button border radius changed accordingly to the value

--------------------------------------------------------------------------------

##### TC016

### Render custom background color

-   Open gutenberg web, add `Buttons` block
-   Choose the **custom** background color from **picker**
-   Save the post
-   Open the same post on mobile app
-   Expect `Button` background color is the same as on web

--------------------------------------------------------------------------------

##### TC017

### Render custom text color

-   Open gutenberg web, add `Buttons` block
-   Choose the **custom** text color from **picker**
-   Save the post
-   Open the same post on mobile app
-   Expect `Button` text color is the same as on web

--------------------------------------------------------------------------------

##### TC018

### Render gradient background color

-   Open gutenberg web, add `Buttons` block
-   Choose the **gradient** background color from the palette
-   Save the post
-   Open the same post on mobile app
-   Expect `Button` gradient background color is the same as on web

--------------------------------------------------------------------------------

##### TC019

### Render theme colors

-   Open gutenberg web, add `Buttons` block
-   Choose a theme color from the **palette* (among the predefined ones)
-   Save the post
-   Open the same post on mobile app
-   Expect `Button` with gray background color and white text color

--------------------------------------------------------------------------------

##### TC020

### Check if selection / caret color matches font color

-   Open gutenberg web, add `Buttons` block
-   Choose the **custom** text color from **picker**
-   Save the post
-   Open the same post on mobile app
-   Observe caret / select text
-   Expect `Button` caret / selection color to match the custom text color

**_Note:_** This may work if running on Android API 28+ do to restrctions that will be handled as part of [Issue #1787](https://github.com/wordpress-mobile/gutenberg-mobile/issues/1787)

--------------------------------------------------------------------------------

##### TC021

### The newly created button has set background color to the theme-default color in preview

-   Add `Buttons` block
-   Save the post
-   Open a post e.g in preview mode
-   Expect `Button` with background color consistent with theme-default color

--------------------------------------------------------------------------------

##### TC022

### Toolbar link button is active when Button has link

-   Add `Buttons` block
-   Open link [settings](../resources/button-link-settings.png)
-   Edit `Button URL` field and add link
-   Close bottom-sheet
-   Expect toolbar link button is active

--------------------------------------------------------------------------------

##### TC023

### Button's wrapper grows properly

-   Add `Buttons` block
-   Add next button using inline appender or inserter
-   Select the first one and type some characters
-   Expect button's width grows properly (_horizontally_)

--------------------------------------------------------------------------------
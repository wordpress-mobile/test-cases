
# Buttons Block - Test Cases

--------------------------------------------------------------------------------

##### TC001

### Buttons is added with focused Button with gray background color and white text color

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

### Add another Button inside Buttons using an inline appender

-   Add `Buttons` block
-   Press an inline appender
-   Expect a new `Button` is automatically added and focused
-   Expect Buttons are displayed side-by-side

--------------------------------------------------------------------------------

##### TC004

### Add another Button inside Buttons using inserter

-   Add `Buttons` block
-   Press inserter
-   Choose `Button` from the opened bottom sheet
-   Expect `ADD BLOCK HERE` line isn't displayed
-   Expect a new `Button` is added and focused
-   Expect Buttons are displayed side-by-side

--------------------------------------------------------------------------------

##### TC005

### Removing Button along with Buttons using the trash button

-   Add `Buttons` block
-   Expect focused `Button` inside `Buttons`
-   Press trash button
-   Expect `ADD BLOCK HERE` line isn't displayed
-   Expect `Button` is removed along with whole `Buttons` container

--------------------------------------------------------------------------------

##### TC006

### Removing Button along with Buttons deleting all characters

-   Add `Buttons` block
-   Expect focused `Button` inside `Buttons`
-   Type something
-   Press trash button
-   Delete all of the text from `Button`
-   Expect `Button` is removed along with whole `Buttons` container

--------------------------------------------------------------------------------

##### TC007

### Removing exactly one Button (when Buttons contain more of them) using the trash button

-   Add `Buttons` block
-   Press an inline appender
-   Expect a new `Button` is added and focused
-   Press trash button
-   Expect current `Button` is removed and the previous `Button` is focused

--------------------------------------------------------------------------------

##### TC008

### Removing exactly one Button (when Buttons contain more of them) deleting all characters

-   Add `Buttons` block
-   Press an inline appender
-   Expect a new `Button` is added and focused
-   Type something
-   Delete all of the text from Button
-   Expect current `Button` is removed and the previous `Button` is focused

--------------------------------------------------------------------------------

##### TC009

### Wrapping Buttons

-   Add `Buttons` block
-   Press an inline appender
-   Expect a new `Button` is added and focused
-   Select the first `Button`
-   Type some characters to fill `Button` width
-   Expect the second `Button` to fall into the second row

--------------------------------------------------------------------------------

##### TC010

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

##### TC011

### Button max width is calculated OK inside inner blocks(iOS only)

-   Add `Buttons` block
-   Expect to see focused `Button` inside `Buttons` block
-   Start typing and removing characters
-   Expect `Button` is expanding / shrinking accordingly to the editing process
-   Type more character to fill all the space
-   Expect `Button` text is not exceeding the container

--------------------------------------------------------------------------------

##### TC012

### Link from the clipboard is automatically added into the empty URL field in link settings and button options

-   Copy link into clipboard, e.g. `http://wordpress.com`
-   Add `Buttons` block
-   Open link [settings](../resources/button-link-settings.png)
-   Expect link from the clipboard to be automatically added into the empty URL field

--------------------------------------------------------------------------------

##### TC013

### Edit text styles

-   Add `Buttons` block
-   Type some characters
-   Select your text
-   Press icons responsible for changing text styles: `Bold`, `Italic`, `Strikethrough`
-   Save the post
-   Open a post e.g in preview mode
-   Expect text style changes accordingly to selected options

--------------------------------------------------------------------------------

##### TC014

### Settings: Link URL

-   Add `Buttons` block
-   Open link [settings](../resources/button-link-settings.png)
-   Edit `Button URL` field and add link
-   Save the post
-   Open a post e.g. in preview mode
-   Expect Button is redirecting to the added link

--------------------------------------------------------------------------------

##### TC015

### Settings: Open in new tab

-   Add `Buttons` block
-   Open link [settings](../resources/button-link-settings.png)
-   Switch on `Open in new tab`
-   Expect `noreferrer noopener` is added automatically in `Link Rel` field
-   Save the post
-   Open a post e.g. in preview mode
-   Expect Button is opening a link in new tab

--------------------------------------------------------------------------------

##### TC016

### Settings: Link rel

-   Add `Buttons` block
-   Open link [settings](../resources/button-link-settings.png)
-   Edit `Link Rel` field and add link rel e.g `noreferrer`
-   Open link [settings](../resources/button-link-settings.png) again
-   Expect link rel is saved

--------------------------------------------------------------------------------

##### TC017

### Settings: Synchronize with button options

-   Add `Buttons` block
-   Open link [settings](../resources/button-link-settings.png)
-   Edit `Button URL` field and add link
-   Switch on `Open in new tab`
-   Edit `Link Rel` field and add rel
-   Open button [options](../resources/button-options.png)
-   Expect fields `Button URL`, `Open in new tab`, `Link Rel` to have the same content as in link settings

--------------------------------------------------------------------------------

##### TC018

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

##### TC019

### Settings: Change Button border radius

-   Add `Buttons` block
-   Open button [options](../resources/button-options.png)
-   Edit `Border Radius` moving slider
-   Expect Button border radius changed accordingly to the value
-   Edit `Border Radius` typing border radius value in input
-   Expect Button border radius changed accordingly to the value

--------------------------------------------------------------------------------

##### TC020

### Render custom background color

-   Add `Buttons` block
-   Save the post
-   Open the same post on web
-   Choose the **custom** background color from **picker**
-   Save the post
-   Open the same post on mobile app
-   Expect `Button` background color is the same as on web

_Known issue_: There is a conversion error for `Button` block. It's related to case where older version of gutenberg editor is trying to edit the block generated by a newer version. Choose an option e.g. `Attempt Block Recovery` to continue.

--------------------------------------------------------------------------------

##### TC021

### Render custom text color

-   Add `Buttons` block
-   Save the post
-   Open the same post on web
-   Choose the **custom** text color from **picker**
-   Save the post
-   Open the same post on mobile app
-   Expect `Button` text color is the same as on web

_Known issue_: There is a conversion error for `Button` block. It's related to case where older version of gutenberg editor is trying to edit the block generated by a newer version. Choose an option e.g. `Attempt Block Recovery` to continue.

--------------------------------------------------------------------------------

##### TC022

### Render gradient background color

-   Add `Buttons` block
-   Save the post
-   Open the same post on web
-   Choose the **gradient** background color from the palette
-   Save the post
-   Open the same post on mobile app
-   Expect `Button` gradient background color is the same as on web

_Known issue_: There is a conversion error for `Button` block. It's related to case where older version of gutenberg editor is trying to edit the block generated by a newer version. Choose an option e.g. `Attempt Block Recovery` to continue.

--------------------------------------------------------------------------------

##### TC023

### Fallback to default colors in case theme colors are used

-   Add `Buttons` block
-   Save the post
-   Open the same post on web
-   Choose a background color from the **palette**
-   Choose a text color from the **palette**
-   Save the post
-   Open the same post on mobile app
-   Expect `Button` with gray background color and white text color

_Known issue_: There is a conversion error for `Button` block. It's related to case where older version of gutenberg editor is trying to edit the block generated by a newer version. Choose an option e.g. `Attempt Block Recovery` to continue.

--------------------------------------------------------------------------------

##### TC024

### Check if selection / caret color matches font color

-   Add `Buttons` block
-   Save the post
-   Open the same post on web
-   Choose the **custom** text color from **picker**
-   Save the post
-   Open the same post on mobile app
-   Observe caret / select text
-   Expect `Button` caret / selection color to match the custom text color

**_Note:_** This may work if running on Android API 28+ do to restrctions that will be handled as part of [Issue #1787](https://github.com/wordpress-mobile/gutenberg-mobile/issues/1787)

_Known issue_: There is a conversion error for `Button` block. It's related to case where older version of gutenberg editor is trying to edit the block generated by a newer version. Choose an option e.g. `Attempt Block Recovery` to continue.

--------------------------------------------------------------------------------

##### TC025

### The newly created button has set background color to the theme-default color in preview

-   Add `Buttons` block
-   Save the post
-   Open a post e.g in preview mode
-   Expect `Button` with background color consistent with theme-default color

--------------------------------------------------------------------------------

##### TC026

### Toolbar link button is active when Button has link

-   Add `Buttons` block
-   Open link [settings](../resources/button-link-settings.png)
-   Edit `Button URL` field and add link
-   Close bottom-sheet
-   Expect toolbar link button is active

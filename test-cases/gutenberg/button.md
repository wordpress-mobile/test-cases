
# Button Block - Test Cases

--------------------------------------------------------------------------------

##### TC001

### Button max width is calculated OK inside inner blocks(iOS only)

-   Add a Button block
-   Start typing and removing characters
-   Expect Button is expanding / shrinking accordingly to the editing process
-   Type more character to fill all the space
-   Expect Button text is not exceeding the container

--------------------------------------------------------------------------------

##### TC002

### Link from the clipboard is automatically added into the empty URL field in link settings and button options

-   Copy link into clipboard, e.g. `http://wordpress.com`
-   Add a Button block
-   Open link [settings](../resources/button-link-settings.png)
-   Expect link from the clipboard to be automatically added into the empty URL field
-   Add second Button block
-   Open button [options](../resources/button-options.png)
-   Expect link from the clipboard to be automatically added into the empty URL field 

--------------------------------------------------------------------------------

##### TC003

### Edit text styles

-   Add a Button block
-   Type some characters
-   Select your text
-   Press icons responsible for changing text styles: `Bold`, `Italic`, `Strikethrough`
-   Save the post
-   Open a post e.g in preview mode
-   Expect text style changes accordingly to selected options

--------------------------------------------------------------------------------

##### TC004

### Settings: Link URL

-   Add a Button block
-   Open link [settings](../resources/button-link-settings.png)
-   Edit `Button URL` field and add link
-   Save the post
-   Open a post e.g. in preview mode
-   Expect Button is redirecting to the added link

--------------------------------------------------------------------------------

##### TC005

### Settings: Open in new tab

-   Add a Button block
-   Open link [settings](../resources/button-link-settings.png)
-   Switch on `Open in new tab`
-   Expect `noreferrer noopener` is added automatically in `Link Rel` field
-   Save the post
-   Open a post e.g. in preview mode
-   Expect Button is opening a link in new tab

--------------------------------------------------------------------------------

##### TC006

### Settings: Link rel

-   Add a Button block
-   Open link [settings](../resources/button-link-settings.png)
-   Edit `Link Rel` field and add link rel e.g `noreferrer`
-   Open link [settings](../resources/button-link-settings.png) again
-   Expect link rel is saved

--------------------------------------------------------------------------------

##### TC007

### Settings: Synchronize with button options

-   Add a Button block
-   Open link [settings](../resources/button-link-settings.png)
-   Edit `Button URL` field and add link
-   Switch on `Open in new tab`
-   Edit `Link Rel` field and add rel
-   Open button [options](../resources/button-options.png)
-   Expect fields `Button URL`, `Open in new tab`, `Link Rel` to have the same content as in link settings

--------------------------------------------------------------------------------

##### TC008

### Settings: Remove link

-   Add a Button block
-   Open link [settings](../resources/button-link-settings.png)
-   Edit `Button URL` field and add link
-   Switch on `Open in new tab`
-   Edit `Link Rel` field and add rel
-   Press `Remove link` button
-   Open link settings again
-   Expect default settings

--------------------------------------------------------------------------------

##### TC009

### Settings: Change Button border radius

-   Add a Button block
-   Open button [options](../resources/button-options.png)
-   Edit `Border Radius` moving slider
-   Expect Button border radius changed accordingly to the value
-   Edit `Border Radius` typing border radius value in input
-   Expect Button border radius changed accordingly to the value

--------------------------------------------------------------------------------

##### TC010

### Render custom background color

-   Add a Button block
-   Save the post
-   Open the same post on web
-   Choose the **custom** background color from **picker**
-   Save the post
-   Open the same post on mobile app
-   Expect Button background color is the same as on web

--------------------------------------------------------------------------------

##### TC011

### Render custom text color

-   Add a Button block
-   Save the post
-   Open the same post on web
-   Choose the **custom** text color from **picker**
-   Save the post
-   Open the same post on mobile app
-   Expect Button text color is the same as on web

--------------------------------------------------------------------------------

##### TC012

### Render gradient background color

-   Add a Button block
-   Save the post
-   Open the same post on web
-   Choose the **gradient** background color from the palette
-   Save the post
-   Open the same post on mobile app
-   Expect Button gradient background color is the same as on web

--------------------------------------------------------------------------------

##### TC013

### Fallback to default colors in case theme colors are used

-   Add a Button block
-   Save the post
-   Open the same post on web
-   Choose a background color from the **palette**
-   Choose a text color from the **palette**
-   Save the post
-   Open the same post on mobile app
-   Expect Button with gray background color and white text color

--------------------------------------------------------------------------------

##### TC014

### New Button is created with the gray color

-   Add a Button block
-   Expect gray background color and white text

--------------------------------------------------------------------------------

##### TC015

### Check if selection / caret color matches font color

-   Add a Button block
-   Save the post
-   Open the same post on web
-   Choose the **custom** text color from **picker**
-   Save the post
-   Open the same post on mobile app
-   Observe caret / select text
-   Expect Button caret / selection color to match the custom text color

**_Note:_** This may work if running on Android API 28+ do to restrctions that will be handled as part of [Issue #1787](https://github.com/wordpress-mobile/gutenberg-mobile/issues/1787)

--------------------------------------------------------------------------------

##### TC016

### The newly created button has set background color to the theme-default color in preview

-   Add a Button block
-   Save the post
-   Open a post e.g in preview mode
-   Expect Button with background color consistent with theme-default color

--------------------------------------------------------------------------------

##### TC017

### Tapping `delete` key removes block when Button is empty

-   Add a Button block
-   Type some characters
-   Remove all characters
-   Press `delete` key when Button is empty
-   Expect Button is deleted

--------------------------------------------------------------------------------

##### TC018

### Toolbar link button is active when Button has link

-   Add a Button block
-   Open link [settings](../resources/button-link-settings.png)
-   Edit `Button URL` field and add link
-   Close bottom-sheet
-   Expect toolbar link button is active

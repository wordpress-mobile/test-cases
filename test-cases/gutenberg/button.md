
# Button Block - Test Cases

--------------------------------------------------------------------------------

##### TC001

### Expand / shrink RichText inside Button

-   Add a Button block
-   Start typing and removing characters
-   Expect Button is expanding / shrinking accordingly to the editing process
-   Type more character to fill all the space
-   Expect Button text is not exceeding the container

--------------------------------------------------------------------------------

##### TC002

### Copy link from a clipboard 

-   Add a Button block
-   Copy link into clipboard
-   Open link [settings](../resources/button-link-settings.png)
-   Expect link from the clipboard to be automaticially added into the empty URL field

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

### Edit Button link settings - _add link_

-   Add a Button block
-   Open link [settings](../resources/button-link-settings.png)
-   Edit `Button URL` field and add link
-   Save the post
-   Open a post e.g. in preview mode
-   Expect Button is redirecting to the added link

--------------------------------------------------------------------------------

##### TC005

### Edit Button link settings - _open in new tab_

-   Add a Button block
-   Open link [settings](../resources/button-link-settings.png)
-   Switch on `Open in new tab`
-   Expect `noreferrer noopener` is added automatically in `Link Rel` field
-   Save the post
-   Open a post e.g. in preview mode
-   Expect Button is opening a link in new tab

--------------------------------------------------------------------------------

##### TC006

### Edit Button link settings - _link rel_

-   Add a Button block
-   Open link [settings](../resources/button-link-settings.png)
-   Edit `Link Rel` field and add link rel e.g `noreferrer`
-   Open link [settings](../resources/button-link-settings.png) again
-   Expect link rel is saved

--------------------------------------------------------------------------------

##### TC007

### Synchronize link settings with button options

-   Add a Button block
-   Open link [settings](../resources/button-link-settings.png)
-   Edit `Button URL` field and add link
-   Switch on `Open in new tab`
-   Edit `Link Rel` field and add rel
-   Open button [options](../resources/button-options.png)
-   Expect fields `Button URL`, `Open in new tab`, `Link Rel` to have the same content as in link settings

--------------------------------------------------------------------------------

##### TC008

### Clear link settings

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

### Change Button border radius

-   Add a Button block
-   Open button [options](../resources/button-options.png)
-   Edit `Border Radius` moving slider
-   Expect Button border radius changed accrodingly to the value
-   Edit `Border Radius` typing border radius value in input
-   Expect Button border radius changed accordingly to the value

--------------------------------------------------------------------------------

##### TC010

### Render custom background color

-   Open post on web
-   Add a Button block
-   Choose the **custom** background color from **picker**
-   Save the post
-   Open the same post on mobile app
-   Expect Button background color is the same as on web

--------------------------------------------------------------------------------

##### TC011

### Render custom text color

-   Open post on web
-   Add a Button block
-   Choose the **custom** text color from **picker**
-   Save the post
-   Open the same post on mobile app
-   Expect Button text color is the same as on web

--------------------------------------------------------------------------------

##### TC012

### Render gradient background color

-   Open post on web
-   Add a Button block
-   Choose the **gradient** background color from the palette
-   Save the post
-   Open the same post on mobile app
-   Expect Button gradient background color is the same as on web

--------------------------------------------------------------------------------

##### TC013

### Render fallback background and text colors

-   Open post on web
-   Add a Button block
-   Choose the **regular** background color from the palette
-   Choose the **regular** text color from the palette
-   Save the post
-   Open the same post on mobile app
-   Expect Button with gray background color and white text color

--------------------------------------------------------------------------------

##### TC014

### Render blue background color for new Button

-   Add a Button block
-   Expect blue background color and white text

--------------------------------------------------------------------------------

##### TC015

### Render selection / caret color only for custom colors

-   Open post on web
-   Add a Button block
-   Choose the **custom** text color from **picker**
-   Save the post
-   Open the same post on mobile app
-   Observe caret / select text
-   Expect Button caret / selection color to match the custom text color

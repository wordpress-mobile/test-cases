
# Cover Block - Test Cases

##### TC001

### Add image background from WordPress Media library

-   Add a cover block 
-   Tap on Placeholder
-   The picker should show up with the `WordPress Media library` option

![Cover media picker](../resources/cover-7.png)
-   Select and image
-   Expect to see the selected image in the Cover Block

--------------------------------------------------------------------------------

##### TC002

### Change Minimum height in pixels

-   Add a cover block and select an image from the `WordPress Media library`
-   Tap on the settings icon of the block
-   Verify that the bottom sheet opens with the Minimum height in pixels setting

![Minimum height in pixels](../resources/cover-1.png)
-   Update the value using the slider
-   Close the bottom sheet
-   Expect to see the cover with the new height value

--------------------------------------------------------------------------------

##### TC003

### Image focal point is rendered properly

-   Add a Cover block from the Web editor
-   Select an image
-   Decrease the height of the block and use the Focal point picker in the right sidebar, select any point

![Web focal point picker](../resources/cover-2.png)
-   Save the post
-   Open the post from the app
-   Expect to see the the Cover block with the image and the right focal point

![Cover with focal point](../resources/cover-3.png)

--------------------------------------------------------------------------------

##### TC004

### Custom color is rendered properly

-   Add a Cover block from the Web editor
-   Select an image
-   Type in any text
-   Select the block
-   Add a **custom** solid overlay color

![Web overlay color setting](../resources/cover-4.png)
-   Select the text
-   Add a **custom** text color

![Web text color setting](../resources/cover-5.png)
-   Save the post
-   Open the post from the app
-   Expect to see the the Cover block with the image and color styles

![Cover with color styles](../resources/cover-6.png)


--------------------------------------------------------------------------------

##### TC005

### Add Video Background from WordPress Media library

#### **Precondition**

A site with premium or business plan

-   Add a Cover block
-   Tap on Placeholder
-   Select a video
-   Expect to see the video added and playing without sound

--------------------------------------------------------------------------------

##### TC006

### Replace media

-   Add a Cover block
-   Tap on Placeholder
-   Select an image
-   Expect to see the image added
-   Tap on the replace media option

![Replace media](../resources/cover-8.png)
-   Select another image
-   Expect to see the new image

--------------------------------------------------------------------------------

##### TC007

### Gradient background is rendered properly

-   Add a Cover block from the Web editor
-   Select a gradient background

![Gradient setting](../resources/cover-9.png)
-   Open the post from the app
-   Expect to see the Cover block with the gradient as background

![Cover with gradient](../resources/cover-10.png)

--------------------------------------------------------------------------------

##### TC008

### Gradient overlay is rendered properly

-   Add a Cover block from the Web editor
-   Select an image as a background
-   Select a gradient overlay

![Gradient setting](../resources/cover-9.png)
-   Open the post from the app
-   Expect to see the Cover block with the image and the gradient on top as an overlay

![Cover with gradient](../resources/cover-12.png)

--------------------------------------------------------------------------------

##### TC009

### Change Background Opacity

-   Add a cover block and select an image from the `WordPress Media library`
-   Tap on the settings icon of the block
-   Verify that the bottom sheet opens with the Background Opacity setting

![Background Opacity](../resources/cover-11.png)
-   Update the value using the slider
-   Close the bottom sheet
-   Expect to see the cover with the new overlay opacity value

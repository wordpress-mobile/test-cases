
# Cover Block - Test Cases

##### TC001

### Add image

-   Add a cover block 
-   Tap on Add Image or Video
-   The picker should show up with the `WordPress Media library` option
![Cover media picker](../resources/cover-7.png)
-   Select and image
-   Expect to see the selected image in the Cover Block

--------------------------------------------------------------------------------

##### TC002

### Change settings

-   Add a cover block and select an image from the `WordPress Media library`
-   Tap on the settings icon of the block
-   Verify that the bottom sheet opens with the following settings
![Cover settings](../resources/cover-1.png)
-   Update the values using the sliders
-   Verify that the Cover block changes accordingly

--------------------------------------------------------------------------------

##### TC003

### Focal point of an image

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

### Color styles

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

### Video background

#### **Precondition**

A site with premium or business plan

-   Add a Cover block
-   Tap on Add Image or Video
-   Select a video
-   Expect to see the video added and playing without sound

--------------------------------------------------------------------------------

##### TC006

### Replace media

-   Add a Cover block
-   Tap on Add Image or Video
-   Select an image
-   Expect to see the image added
-   Tap on the replace media option
![Replace media](../resources/cover-8.png)
-   Select another image
-   Expect to see the new image

--------------------------------------------------------------------------------

##### TC007

### Gradient overlay

-   Add a Cover block from the Web editor
-   Select a gradient background
![Gradient setting](../resources/cover-9.png)
-   Open the post from the app
-   Expect to see the Cover block with the gradient as background
![Cover with gradient](../resources/cover-10.png)



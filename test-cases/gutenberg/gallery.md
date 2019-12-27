
# Gallery Block - Test Cases

#### **Precondition**

A site with premium or business plan

##### TC001

**Close/Re-open post with an ongoing image upload**

-   Add a gallery block and insert images from device
-   While there’s an ongoing upload, close the post with publishing changes
-   Verify that you see the upload progress in post summary
![Progress](../resources/upload-progress-posts-list.png)
-   Reopen the post while upload is ongoing
-   Verify you still see the upload progress in the gallery block

##### TC002

**Close post with an ongoing image upload**

-   Add a gallery block and insert images from device
-   While there’s an ongoing upload, close the post with publishing changes
-   Verify that you see the upload progress in post summary
![Progress](../resources/upload-progress-posts-list.png)
-   Wait until upload finishes
-   Re-open the post
-   Verify that Gallery block shows the uploaded images

##### TC003

**Add caption to gallery**

-   Add a Gallery block
-   Set a caption to your gallery

![Gallery Caption](../resources/gallery-caption-3.png)
-   Add some styles to your caption:
    - Bold
    - Italic
    - Underline
    - Expect all to work correctly

![Gallery Caption Styles](../resources/gallery-caption-4.png)

-   Save the post
-   Open it and expect to see the captions with their styles

##### TC004

**Add caption to gallery images**

-   Add a Gallery block
-   Add some images to your gallery
-   Set some captions to your images by tapping on each image

![Gallery Image Caption](../resources/gallery-caption-1.png)
-   Add some styles to your captions:
    - Bold
    - Italic
    - Break line
    - Expect all to work correctly

![Gallery Image Caption Styles](../resources/gallery-caption-2.png)

-   Save the post
-   Open it and expect to see the captions with their styles

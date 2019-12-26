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

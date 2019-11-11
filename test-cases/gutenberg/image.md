
# Image Block - Test Cases

#### **Precondition**

A site with premium or business plan

##### TC001

**Insert image from device (failing)**

-   Tap on the Image block placeholder or edit button in the toolbar
-   Tap option ‘Choose from device’ and choose an image
-   Turn off internet connection and wait
-   You should see the retry message on the image thumbnail
![Upload failed](resources/image-upload-failed.png)
-   Turn your internet connection back on
-   Tap on the image
-   You should be asked to retry
![Upload failed](resources/retry-upload.png)
-   Tap retry
-   The upload should continue

##### TC002

**Insert image from device (cancel)**

-   Tap on the Image block placeholder or edit button in the toolbar
-   Tap option ‘Choose from device’ and choose an image
-   While the upload is in progress tap on the image thumbnail
-   You should see the below message:
![Cancel upload](resources/cancel-upload.png)
-   Tap cancel
-   You should see the image block is cleared and placeholder is again visible

##### TC003

**Add Caption**

-   Add a caption to the image block and save the post
-   Reopen the post
-   Verify caption text is there


##### TC004

**Close/Re-open post with an ongoing image upload**

-   Add an image block and insert image from device
-   While there’s an ongoing upload, close the post with publishing changes
-   Verify that you see the upload progress in post summary
![Progress](resources/upload-progress-posts-list.png)
-   Reopen the post while upload is ongoing
-   Verify you see the upload progress in the image block
![Progress](resources/upload-progress-image.png)

##### TC005

**Close post with an ongoing image upload**

-   Add an image block and insert image from device
-   While there’s an ongoing upload, close the post with publishing changes
-   Verify that you see the upload progress in post summary
![Progress](resources/upload-progress-posts-list.png)
-   Wait until upload finishes
-   Re-open the post
-   Verify that Image block shows the uploaded image

##### TC006

**Switch to classic editor with an image block in page**

-   Add an image block and insert image
-   Switch to classic editor
-   Verify that you see the image there too




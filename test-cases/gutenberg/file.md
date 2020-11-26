
# File Block - Test Cases

#### **Precondition**

A site with premium or business plan

##### TC001

**Upload completes successfully from the device library**

**Steps**
- Tap on Choose a file on the Media Placeholder. 
- Tap option "Choose from device" and choose a file. 

**Expected Behavior**
- Expect to see the upload indicator and the Download button should be dimmed.
- Expect to not see a link or replace buttons in the toolbar

![Upload pending](../resources/local-file-upload-pending.png)
- Expect to see file's name and an active Download button once the upload is complete.  
- Expect the link and replace buttons to appear in the toolbar

![Upload successful](../resources/local-file-upload-successful.png)

##### TC002

**Upload completes successfully from the WordPress Media library**

**Steps**
- Tap on Choose a file on the Media Placeholder. 
- Tap option "WordPress Media Library" and choose a file. 

**Expected Behavior**
- Expect to see file's name  (without link)  and an active Download button once the upload is complete.  

![Upload successful](../resources/local-file-upload-successful.png)

##### TC003

**Upload fails from the device library**

**Steps**
-   Tap on Choose a file on the Media Placeholder or the edit button in the toolbar.
-   Tap option ‘Choose from device’ and choose a file.
-   Turn off internet connection and wait.

**Expected Behavior**
-   You should see an error message and a dimmed Download button.

![Upload failed](../resources/local-file-upload-failed.png)

**Steps**

-   Turn your internet connection back on.
-   Tap on the File block itself.
-   You should be asked to retry.

**Expected Behavior**

![Upload retry](../resources/local-file-upload-retry.png)

**Steps**
-   Tap retry

**Expected Behavior**
-   The upload should continue.

##### TC004

**Stop the file upload before it completes**

**Steps**

-   Tap on Choose a file on the Media Placeholder or edit button in the toolbar.
-   Tap option ‘Choose from device’ and choose an file.
-   While the upload is in progress tap on the File Block.

**Expected Behavior**

-   You should see the below message:
![Upload stopped](../resources/local-file-upload-stop.png)

**Steps**

-   Tap Stop

**Expected Behavior**

-   You should see the File block is cleared and the placeholder component should be visible.
![Upload placeholder](../resources/local-file-upload-placeholder.png)

##### TC005

**Close the post with an ongoing file upload**

**Steps**

-   Add a File block and insert a file from your device.
-   While there’s an ongoing upload, save the post as a draft.

**Expected Behavior**

-   Verify that you see the upload progress in post summary.
![File upload in post list](../resources/local-file-upload-post-list.png)

**Steps**

-   Wait until upload finishes
-   Re-open the post

**Expected Behavior**

-   Verify that File block shows the file name.
-   You can also switch to HTML mode to verify that the upload was complete by checking to see that the hyperlink points to a remote media. 

##### TC006

**Replace the selected files**

**Steps**

-   Tap on an existing File Block that has a file.
-   From the toolbar, click on the replace button. 
-   The Choose file bottom sheet will now be visible. 
- 


**Expected Behavior**

-   Verify that you see the upload progress in post summary.
![File upload in post list](../resources/local-file-upload-post-list.png)

**Steps**

-   Wait until upload finishes
-   Re-open the post

**Expected Behavior**

-   Verify that File block shows the file name.
-   You can also switch to HTML mode to verify that the upload was complete by checking to see that the hyperlink points to a remote media. 



# Media-Text Block - Test Cases

#### **Precondition**

A site with premium or business plan

##### TC001-i

**Insert image from device (failing)**

Use same same steps on Media-Text block: [image block TC001](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/image.md#tc001).

##### TC001-v

**Insert video from device (failing)**

Use same same steps on Media-Text block: [video block TC001](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/video.md#tc001).

##### TC002-i

**Insert image from device (cancel)**

Use same same steps on Media-Text block: [image block TC002](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/image.md#tc002) 

##### TC002-v

**Insert video from device (cancel)**

Use same same steps on Media-Text block: [video block TC002](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/video.md#tc002) 

##### TC003-i

**Close/Re-open post with an ongoing image upload**

Use same same steps on Media-Text block: [image block TC004](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/image.md#tc004)

##### TC003-v

**Close/Re-open post with an ongoing video upload**

Use same same steps on Media-Text block: [video block TC004](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/video.md#tc004)

##### TC004-i

**Close post with an ongoing image upload**

Use same same steps on Media-Text block: [image block TC005](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/image.md#tc005) 

##### TC004-v

**Close post with an ongoing video upload**

Use same same steps on Media-Text block: [video block TC005](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/video.md#tc005)

##### TC005-i

**Change media text order during upload and close the post**

- Add media-text
- Start an image upload
- Change media-text order using the toolbar button.
- Leave the post before upload finishes
- Wait until upload is finished
- Reopen the post
- Result: mediaId is wrong and it is still showing the upload id, this is also cauising a red screen on iOS since mediaId is making the block invalid.


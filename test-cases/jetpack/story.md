# Story Block - Test Cases

--------------------------------------------------------------------------------

##### TC001

#### Precondition

A wordpress.com site or a jetpack site with jetpack version 9.1 or newer

### Block picker shows the Story block

1. On the site described above, add a post, then tap on + to open the Block Picker
2. Verify the Story block appears among the blocks that can be added to the Post, and add it
3. An empty Story block should have been added to the Post (with the Add Media placeholder)

--------------------------------------------------------------------------------

##### TC002

#### Precondition

A. A jetpack site with jetpack version previous to 9.1
  * The following steps can be used to test an older Jetpack version via Jurassic Ninja:
    * Create a new site via Jurassic Ninja
    * Go to installed plugins
    * De-activate the Jetpack plugin
    * Delete the Jetpack plugin
    * Download an older version of Jetpack (e.g. [9.0.2](https://downloads.wordpress.org/plugin/jetpack.9.0.2.zip))
    * Add a new plugin
    * Upload the zip file downloaded earlier
    * Activate the older Jetpack plugin version

B. A self-hosted site without jetpack

### Block picker does not show the Story block

1. On the site described above, add a post, then tap on + to open the Block Picker
2. Verify the Story block does NOT appear among the blocks that can be added to the Post.
3. Perform steps 1 and 2 on a self-hosted site (option B above)


--------------------------------------------------------------------------------

#### Precondition for the following test cases

A wordpress.com site or a jetpack site with jetpack version 9.1 or newer

##### TC003

### Add Media to empty Story block

1. On the site described above, add a post, then tap on + to open the Block Picker
2. Add a Story block
3. Select the Story block, then tap on Add Media
4. The Story Composer capture mode appears, take a picture and create a Story
5. Save your edits by tapping on the check button on the top-right corner of the screen
6. Observe the picture you created appears as the cover of the Story block (*) and gets saved and uploaded to the site
7. Also while save and upload happen, verify the progress overlay is shown on the Story block.

(*) known issue: the image will flash as it shows the local file first, and then changes to point to the remote url after upload finishes, showing a blank cover for a few moments while the remote URL is loaded

For reference, see https://github.com/wordpress-mobile/WordPress-Android/pull/13174

--------------------------------------------------------------------------------

##### TC004

### Add Media to non-empty Story block

1. Open a Post containing an existing non-empty Story block
2. Select the Story block, then tap on the edit tools icon on the top right corner of the Story block cover
3. The Story Composer appears and shows the slides, selected on the first slide
4. Add a new slide and reorder it so it's the first slide (hold and press, then drag to the leftmost position) 
5. Save your edits by tapping on the check button on the top-right corner of the screen
6. Observe the new slide added appears as the cover of the Story block (*) and gets saved and uploaded to the site
7. Also while save and upload happen, verify the progress overlay is shown on the Story block.

(*) known issue: the image will flash as it shows the local file first, and then changes to point to the remote url after upload finishes, showing a blank cover for a few moments while the remote URL is loaded

--------------------------------------------------------------------------------

##### TC005

**Close/Re-open post with an ongoing Story upload**

Steps are similar with [image block TC004](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/image.md#tc004), proceed as follows:


1. On the site described above, add a post, then tap on + to open the Block Picker
2. Add a Story block
3. Select the Story block, then tap on Add Media
4. The Story Composer capture mode appears, take a picture and create a Story
5. Save your edits by tapping on the check button on the top-right corner of the screen
6. Observe the picture you created appears as the cover of the Story block and gets saved and uploaded to the site
7. Also while save and upload happen, verify the progress overlay is shown on the Story block.
8. At this point, close the post with publishing changes
9. Verify that you see the upload progress in post summary
10. Reopen the post while upload is ongoing
11. Verify you see the upload progress in the Story block

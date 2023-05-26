# Functionality Test Suites
This holds a grouping of certain test suites to run in order to share the work while doing periodic functionality tests. The code sections provide a helpful format, if you wish to use it, that you can use in a PR to track the progress on going through the test cases.

## Test Suite 1

- Gallery 1-3
- Columns 1-3
- MediaText 1-2
- Multiple Upload 1
- Cover 1
- Editor Theme 1
- Social Icons 1

```
### Gallery - 1

- [ ] Gallery block - Close/Re-open post with an ongoing image upload - [TC001](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/gallery.md#tc001)
- [ ] Gallery block - Close post with an ongoing image upload - [TC002](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/gallery.md#tc002)

### Gallery - 2

- [ ] Gallery block - Insert image from device (failing) - [TC006](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/gallery.md#tc006)
- [ ] Gallery block - Insert image from device (cancel) - [TC009](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/gallery.md#tc009)

### Gallery - 3

- [ ] Gallery block - Add Gallery Caption - [TC003](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/gallery.md#tc003)
- [ ] Gallery block - Add Gallery Image Caption - [TC04](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/gallery.md#tc004)
- [ ] Gallery block - Try adding same images from WP Media library and moving the images around - [TC010](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/gallery.md#tc010)

### Columns - 1

- [ ] Columns - Multiple slider in columns parent - [TC011](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/columns.md#tc011)
- [ ] Columns - Check if Column placeholders is visible for the unselected state - [TC001](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/columns.md#tc001)
- [ ] Columns - Appearance in vertical device position (vertical layout) - [TC004](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/columns.md#tc004)

### Columns - 2

- [ ] Columns - Max limit of Column number - [TC002](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/columns.md#tc002)
- [ ] Columns - Deep nesting is possible (iOS only)- [TC003](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/columns.md#tc003)
- [ ] Columns - Appearance in horizontal device position (horizontal layout) - [TC005](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/columns.md#tc005)

### Columns - 3

- [ ] Columns - Mover direction - [TC006](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/columns.md#tc006)
- [ ] Columns - Check if Column placeholder is render in nested structure - [TC007](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/columns.md#tc007)
- [ ] Columns - Unselected Column placeholder is stretched to content in nested structure- [TC008](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/columns.md#tc008)

### MediaText - 1

- [ ] Media Text block - Insert image from device (failing) - [TC001](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/media-text.md#tc001-i)
- [ ] Media Text block - Close/Re-open post with an ongoing image upload - [TC003](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/media-text.md#tc003-i)

### MediaText - 2

- [ ] Media Text block - Insert video from device - [TC002-v](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/media-text.md#tc002-v)
- [ ] Media Text block - Insert image from device - [TC002-i](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/media-text.md#tc002-i)

### MultipleUpload - 1

- [ ] Simultaneous uploads - [TC001](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/media-interaction.md#tc001)


### Cover - 1

- [ ] Cover - Add image background from WordPress Media library - [TC001](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/cover.md#tc001)
- [ ] Cover - Image focal point is rendered properly - [TC002](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/cover.md#tc002)
- [ ] Cover - Custom color is rendered properly - [TC002](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/cover.md#tc003)

### Editor Theme - 1

- [ ] Default Colors - Check that default colors still load - [TC001](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/editor-theme.md#tc001)
- [ ] Default Gradients - Check that default gradients still load - [TC002](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/editor-theme.md#tc002)
- [ ] Custom Colors - Check that custom colors load in the editor - [TC003](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/editor-theme.md#tc003)

### Social Icons - 1
- [ ] Active icon gets product color - [TC001](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/social-icons.md#tc001)
- [ ] Social icon forwarding to the link - [TC002](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/social-icons.md#tc002)
```


## Test Suite 2

- DarkMode 1
- Group 1
- Spacer 1
- Buttons 1-2-3
- Color Settings 1
- Image 1
- Drag and Drop Blocks - 1
- VideoPress 2

```
### DarkMode - 1

- [ ] Gallery block - Dark mode - [TC001](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/darkmode.md#tc001)
- [ ] Shortcode block - Dark mode - [TC002](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/darkmode.md#tc002)
- [ ] Media Text block - Dark mode - [TC003](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/darkmode.md#tc003)

### Group - 1

- [ ] Group - Deep nesting is possible (verify iOS does not crash) - [TC001](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/group.md#tc001)
- [ ] Group - Check if Group placeholder is visible for the unselected state - [TC002](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/group.md#tc002)
- [ ] Group - Check if Group placeholder is render in nested structure - [TC003](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/group.md#tc003)
- [ ] Group - Nested block have proper border styling - [TC004](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/group.md#tc004)
- [ ] Group - Breadcrumbs on FloatingToolbar is properly displayed - [TC005](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/group.md#tc005)

### Buttons-1

- [ ] Buttons block - Button's wrapper grows properly - [TC019](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/buttons.md#tc019)
- [ ] Buttons block - Removing exactly one Button (when Buttons contain more of them) - [TC002](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/buttons.md#tc002)
- [ ] Buttons block - Wrapping Buttons - [TC003](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/buttons.md#tc003)

### Button-2

- [ ] Buttons block - Buttons alignment options - [TC004](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/buttons.md#tc004)
- [ ] Buttons block - Settings: Open in new tab - [TC007](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/buttons.md#tc007)
- [ ] Buttons block - Settings: Link rel - [TC008](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/buttons.md#tc008)

### Button-3

- [ ] Buttons block - Settings: Link URL - [TC006](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/buttons.md#tc006)
- [ ] Buttons block - Settings: Remove link - [TC010](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/buttons.md#tc010)
- [ ] Buttons block - Settings: Synchronize with button options - [TC009](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/buttons.md#tc009)

### Color Settings - 1
- [ ] Colors Segmented Controls - [TC001](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/color-settings.md#tc001)
- [ ] Scroll color palette to start - [TC002](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/color-settings.md#tc002)
- [ ] Scroll color palette to the end - [TC003](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/color-settings.md#tc003)

### Image - 1
- [ ] Image block - Insert image from device (failing) - [TC001](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/image.md#tc001)
- [ ] Image block - Insert image from device (cancel) - [TC002](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/image.md#tc002)
- [ ] Image block - Add Caption - [TC003](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/image.md#tc003)
- [ ] Image block - Close/Re-open post with an ongoing image upload - [TC004](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/image.md#tc004)
- [ ] Image block - Close post with an ongoing image upload - [TC005](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/image.md#tc005)

### Drag and Drop Blocks - 1
- [ ] Drag and Drop Blocks - Drag block to the top of the content - [TC001](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/drag-and-drop-blocks.md#tc001)
- [ ] Drag and Drop Blocks - Drag block to the bottom of the content - [TC002](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/drag-and-drop-blocks.md#tc002)

### VideoPress - 2
- [ ] VideoPress block - Player - [TC003](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/jetpack/videopress.md#tc003)
- [ ] VideoPress block - Private video - [TC005](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/jetpack/videopress.md#tc005)
- [ ] VideoPress block - Upload limit for Free users - [TC006](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/jetpack/videopress.md#tc006)

```

## Test Suite 3

- Gallery 2-4
- Columns 2-4
- MediaText 3-4
- Shortcode 1
- Cover 2
- Image 2
- Story block 1

```
### Gallery - 2
- [ ] Gallery block - Insert image from device (failing) - [TC006](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/gallery.md#tc006)
- [ ] Gallery block - Insert image from device (cancel) - [TC009](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/gallery.md#tc009)

### Gallery - 3
- [ ] Gallery block - Add Gallery Caption - [TC003](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/gallery.md#tc003)
- [ ] Gallery block - Add Gallery Image Caption - [TC004](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/gallery.md#tc004)
- [ ] Gallery block - Try adding same images from WP Media library and moving the images around - [TC010](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/gallery.md#tc010)

### Gallery - 4
- [ ] Gallery block - Settings: Link to - [TC012](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/gallery.md#tc012)
- [ ] Gallery block - Settings: Column number - [TC013](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/gallery.md#tc013)
- [ ] Gallery block - Settings: Crop images - [TC014](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/gallery.md#tc014)

### Columns - 2
- [ ] Columns - Max limit of Column number - [TC002](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/columns.md#tc002)
- [ ] Columns - Deep nesting is possible (iOS only)- [TC003](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/columns.md#tc003)
- [ ] Columns - Check if Column placeholders is visible for the unselected state - [TC001](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/columns.md#tc001)
- [ ] Columns - Appearance in vertical device position (vertical layout) - [TC004](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/columns.md#tc004)

### Columns - 3
- [ ] Columns - Appearance in horizontal device position (horizontal layout) - [TC005](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/columns.md#tc005)
- [ ] Columns - Mover direction - [TC006](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/columns.md#tc006)
- [ ] Columns - Check if Column placeholder is render in nested structure - [TC007](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/columns.md#tc007)
- [ ] Columns - Unselected Column placeholder is stretched to content in nested structure- [TC008](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/columns.md#tc008)

### Columns - 4
- [ ] Columns - Check if in DarkMode all components gets proper colors - [TC018](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/columns.md#tc018)

### MediaText - 3
- [ ] Media Text block - Insert video from device (failing) - [TC001-v](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/media-text.md#tc001-v)
- [ ] Media Text block - Close/Re-open post with an ongoing video upload - [TC003-v](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/media-text.md#tc003-v)

### MediaText - 4
- [ ] Media Text block - Media & Text alignment - [TC006](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/media-text.md#tc006)
- [ ] Media Text block - Vertical alignment - [TC007](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/media-text.md#tc007)

### Shortcode-1
- [ ] Shortcode block - Add a youtube link - [TC001](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/shortcode.md#tc001)

### Cover - 2

- [ ] Cover - Add Video Background from WordPress Media library - [TC004](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/cover.md#tc004)
- [ ] Cover - Replace media - [TC005](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/cover.md#tc005)
- [ ] Cover - Gradient background is rendered properly - [TC006](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/cover.md#tc006)
- [ ] Cover - Gradient overlay is rendered properly - [TC007](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/cover.md#tc007)

### Image - 2
- [ ] Image block - Border style setting - [TC006](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/image.md#tc006)
- [ ] Image block - Image size setting - [TC007](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/image.md#tc007)
- [ ] Image block - Link to setting - [TC008](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/image.md#tc008)

### Story block - 1
- [ ] Story block - Verify is available in Block Picker - [TC001](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/jetpack/story.md#tc001)
- [ ] Story block - Verify is not available in Block Picker- [TC002](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/jetpack/story.md#tc002)
- [ ] Story block - Add media to empty Story block - [TC003](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/jetpack/story.md#tc003)
- [ ] Story block - Add media to non-empty Story block - [TC004](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/jetpack/story.md#tc004)
- [ ] Story block - Close/Re-open post with an ongoing Story upload - [TC005](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/jetpack/story.md#tc005)

```

## Test Suite 4

- DarkMode 2
- Group 2
- Spacer 1
- Buttons 4-5-7
- Editor Theme 2
- Color Settings 2
- VideoPress 1

```
### DarkMode - 2

- [ ] Spacer block - Dark mode - [TC004](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/darkmode.md#tc004)
- [ ] Buttons block - Dark mode - [TC005](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/darkmode.md#tc005)
- [ ] Group - Dark mode - [TC006](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/darkmode.md#tc006)
- [ ] Columns - Dark mode - [TC007](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/darkmode.md#tc007)

### Group - 2

- [ ] Group - Navigation up button works as expected - [TC006](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/group.md#tc006)
- [ ] Group - Navigation down works according to parent-first approach - [TC007](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/group.md#tc007)
- [ ] Group - Cross navigation between blocks works as expected - [TC008](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/group.md#tc008)
- [ ] Group - Check if in DarkMode all components gets proper colors - [TC009](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/group.md#tc009)
- [ ] Group - Check if nested Placeholder block can be replaced - [TC010](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/group.md#tc010)

### Spacer - 1

- [ ] Spacer block - Spacer in horizontal layout works as expected - [TC001](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/spacer.md#tc001)

### Buttons - 4

- [ ] Buttons block - Render custom text color - [TC013](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/buttons.md#tc013)
- [ ] Buttons block - Render custom background color - [TC012](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/buttons.md#tc012)
- [ ] Buttons block - Render gradient background color - [TC014](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/buttons.md#tc014)
- [ ] Buttons block - Check if selection / caret color matches font color - [TC016](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/buttons.md#tc016)
- [ ] Buttons block - The newly created Buttons has set background color to the theme-default color in preview - [TC017](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/buttons.md#tc017)

### Buttons - 5

- [ ] Buttons block - Edit text styles - [TC005](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/buttons.md#tc005)
- [ ] Buttons block - Render theme colors - [TC015](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/buttons.md#tc015)
- [ ] Buttons block - Settings: Change Button border radius - [TC011](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/buttons.md#tc011)

### Buttons - 7

- [ ] Buttons block - Toolbar link button is active when Button has link - [TC018](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/buttons.md#tc018)

### Editor Theme - 2
- [ ] Custom Gradients - Check that custom gradients load in the editor - [TC004](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/editor-theme.md#tc004)
- [ ] Offline Support - [TC005](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/editor-theme.md#tc005)

### Color Settings - 2
- [ ] Pressing color swatch - [TC004](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/color-settings.md#tc004)
- [ ] Customize gradient color - [TC005](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/color-settings.md#tc005)
- [ ] Custom color picker - [TC006](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/color-settings.md#tc006)

### VideoPress - 1
- [ ] VideoPress block - Upload a video - [TC001](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/jetpack/videopress.md#tc001)
- [ ] VideoPress block - Add Caption - [TC002](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/jetpack/videopress.md#tc002)
- [ ] VideoPress block - Close post with an ongoing video upload - [TC004](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/jetpack/videopress.md#tc004)

```

## Test Suite 5

- Video block 1-2
- File block 1-3
- Audio block 1-4
- Reusable block 1-2
- Embed block 1-2

```
Video block - 1
- [ ] Video block - Insert video from device (failing) - [TC001](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/video.md#tc001)
- [ ] Video block - Close/Re-open post with an ongoing video upload - [TC004](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/video.md#tc004)

Video block - 2
- [ ] Video block - Insert video from device (cancel) - [TC002](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/video.md#tc002)
- [ ] Video block - Close post with an ongoing video upload - [TC005](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/video.md#tc005)
- [ ] Video block - Add Caption - [TC003](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/video.md#tc003)

File block - 1
- [ ] File block - Upload completes successfully from the device library - [TC001](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/file.md#tc001)
- [ ] File block - Insert completes successfully from the WordPress Media library - [TC002](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/file.md#tc002)
- [ ] File block - Upload fails from the device library - [TC003](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/file.md#tc003)
- [ ] File block - Stop the file upload before it completes - [TC004](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/file.md#tc004)

File block - 2
- [ ] File block - Close the post with an ongoing file upload - [TC005](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/file.md#tc005)
- [ ] File block - Replace the selected files - [TC006](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/file.md#tc006)
- [ ] File block - Change the alignment in the File Block - [TC007](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/file.md#tc007)
- [ ] File block - The Link To Block Setting should open - [TC008](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/file.md#tc008)

File block - 3
- [ ] File block - Open link in new tab - [TC009](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/file.md#tc009)
- [ ] File block - Show/hide download button (Block Settings only) - [TC010](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/file.md#tc010)
- [ ] File block - Copy file URL - [TC011](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/file.md#tc011)
- [ ] File block - Close/Re-open post with an ongoing file upload - [TC012](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/file.md#tc012)

Audio block - 1
- [ ] Audio block - Upload completes successfully from the device library - [TC001](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/audio.md#tc001)
- [ ] Audio block - Insert completes successfully from the WordPress Media library - [TC002](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/audio.md#tc002)

Audio block - 2
- [ ] Audio block - Upload fails from the device library - [TC003](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/audio.md#tc003)
- [ ] Audio block - Stop the audio file upload before it completes - [TC004](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/audio.md#tc004)

Audio block - 3
- [ ] Audio block - Close the post with an ongoing audio file upload - [TC005](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/audio.md#tc005)
- [ ] Audio block - Replace the selected files - [TC006](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/audio.md#tc006)
- [ ] Audio block - Change the alignment in the Audio Block - [TC007](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/audio.md#tc007)

Audio block - 4
- [ ] Audio block - Autoplay setting - [TC008](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/audio.md#tc008)
- [ ] Audio block - Loop setting - [TC009](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/audio.md#tc009)
- [ ] Audio block - Close/Re-open post with an ongoing audio file upload - [TC010](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/audio.md#tc010)

Reusable block - 1
- [ ] Reusable block - Add block - [TC001](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/reusable.md#tc001)
- [ ] Reusable block - Convert to regular blocks - [TC002](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/reusable.md#tc002)

Reusable block - 2
- [ ] Reusable block - Deleted reusable block - [TC003](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/reusable.md#tc003)
- [ ] Reusable block - Recursive block rendering - [TC004](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/reusable.md#tc004)

Embed block - 1
- [ ] Embed block - Inline previews are rendered correctly for the top 5 most-used providers - [TC001](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/embed.md#tc001)

Embed block - 2
- [ ] Embed block - Inline previews are rendered accordingly for each alignment option - [TC002](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/embed.md#tc002)
```
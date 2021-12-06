# Sanity Test Suites
This holds a grouping of certain test suites to run in order to share the work while doing periodic sanity tests. The code sections provide a helpful format, if you wish to use it, that you can use in a PR to track the progress on going through the test cases.

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

- [ ] Gallery block - Close/Re-open post with an ongoing image upload - [TC001](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/gallery.md#tc001)
- [ ] Gallery block - Close post with an ongoing image upload - [TC002](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/gallery.md#tc002)

### Gallery - 2

- [ ] Gallery block - Insert image from device (failing) - [TC006](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/gallery.md#tc006)
- [ ] Gallery block - Insert image from device (cancel) - [TC009](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/gallery.md#tc009)

### Gallery - 3

- [ ] Gallery block - Add Gallery Caption - [TC003](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/gallery.md#tc003)
- [ ] Gallery block - Add Gallery Image Caption - [TC04](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/gallery.md#tc004)
- [ ] Gallery block - Try adding same images from WP Media library and moving the images around - [TC010](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/gallery.md#tc010)

### Columns - 1

- [ ] Columns - Columns percentage mechanism - column's preview - [TC019](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/columns.md#tc019)
- [ ] Columns - Columns percentage mechanism - column's slider input - [TC020](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/columns.md#tc020)
- [ ] Columns - Columns percentage mechanism - predefined percentage values are rendered correctly on frontend- [TC021](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/columns.md#tc021)
- [ ] Columns percentage mechanism - custom percentage values are rendered correctly on frontend- [TC022](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/columns.md#tc022)
- [ ] Columns - Multiple slider in columns parent - [TC023](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/columns.md#tc023)
- [ ] Columns - Adding Column with AppenderButton - [TC003](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/columns.md#tc003)
- [ ] Columns - Adding and removing Column with BottomSheet Stepper control - [TC004](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/columns.md#tc004)


### Columns - 2
- [ ] Columns - Max limit of Column number - [TC005](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/columns.md#tc005)
- [ ] Columns - Min limit of Column number - [TC006](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/columns.md#tc006)
- [ ] Columns - Removing Column with remove button - [TC007](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/columns.md#tc007)
- [ ] Columns - Removing the only one left Column with remove button - [TC008](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/columns.md#tc008)
- [ ] Columns - Changing alignment on Columns - [TC009](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/columns.md#tc009)
- [ ] Columns - Changing alignment on individual Column - [TC010](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/columns.md#tc010)
- [ ] Columns - Alignment attribute is properly passed when adding Column - [TC011](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/columns.md#tc011)
- [ ] Columns - Deep nesting is possible (iOS only)- [TC012](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/columns.md#tc012)

### Columns - 3
- [ ] Columns - Check if Column placeholders is visible for the unselected state - [TC002](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/columns.md#tc002)
- [ ] Columns - Appearance in vertical device position (vertical layout) - [TC013](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/columns.md#tc013)
- [ ] Columns - Appearance in horizontal device position (horizontal layout) - [TC014](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/columns.md#tc014)
- [ ] Columns - Mover direction - [TC015](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/columns.md#tc015)
- [ ] Columns - Check if Column placeholder is render in nested structure - [TC016](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/columns.md#tc016)
- [ ] Columns - Unselected Column placeholder is stretched to content in nested structure- [TC017](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/columns.md#tc017)

### MediaText - 1

- [ ] Media Text block - Insert image from device (failing) - [TC001](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/media-text.md#tc001-i)
- [ ] Media Text block - Close/Re-open post with an ongoing image upload - [TC003](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/media-text.md#tc003-i)

### MediaText - 2

- [ ] Media Text block - Insert video from device (TC002) - [steps](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/media-text.md#tc002-v)
- [ ] Media Text block - Insert image from device (TC002) - [steps](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/media-text.md#tc002-i)

### MultipleUpload - 1

- [ ] Simultaneous uploads - [TC001](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/media-interaction.md#tc001)


### Cover - 1

- [ ] Cover - Add image background from WordPress Media library - [TC001](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/cover.md#tc001)
- [ ] Cover - Change Minimum height in pixels - [TC002](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/cover.md#tc002)
- [ ] Cover - Change Background Opacity - [TC009](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/cover.md#tc009)
- [ ] Cover - Image focal point is rendered properly - [TC003](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/cover.md#tc003)
- [ ] Cover - Custom color is rendered properly - [TC004](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/cover.md#tc004)

### Editor Theme - 1

- [ ] Default Colors - Check that default colors still load - [TC001](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/editor-theme.md#tc001)
- [ ] Default Gradients - Check that default gradients still load - [TC002](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/editor-theme.md#tc002)
- [ ] Custom Colors - Check that custom colors load in the editor - [TC003](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/editor-theme.md#tc003)

### Social Icons - 1
- [ ] The newly created Social Icons block is added with 4 icons - [TC001](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/social-icons.md#tc001)
- [ ] Active icon gets product color - [TC002](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/social-icons.md#tc002)
- [ ] Only active icons are visible when not selected - [TC003](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/social-icons.md#tc003)

```


## Test Suite 2

- DarkMode 1
- Group 1
- Spacer 1
- Buttons 1-2-3-6
- Color Settings 1
- Image 1

```
### DarkMode - 1

- [ ] Gallery block - Dark mode - [TC001](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/darkmode.md#tc001)
- [ ] Shortcode block - Dark mode - [TC002](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/darkmode.md#tc002)
- [ ] Media Text block - Dark mode - [TC003](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/darkmode.md#tc003)

### Group - 1

- [ ] Group - AppenderButton is rendered - [TC001](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/group.md#tc001)
- [ ] Group - Deep nesting is possible (iOS only) - [TC002](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/group.md#tc002)
- [ ] Group - Check if Group placeholder is visible for the unselected state - [TC003](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/group.md#tc003)
- [ ] Group - Check if Group placeholder is render in nested structure - [TC004](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/group.md#tc004)
- [ ] Group - Nested block have proper border styling - [TC005](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/group.md#tc005)
- [ ] Group - Nested block have proper margins values - [TC006](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/group.md#tc006)
- [ ] Group - Breadcrumbs on FloatingToolbar is properly displayed - [TC008](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/group.md#tc008)

### Spacer - 1

- [ ] Spacer block - Spacer is rendered without crash - [TC001](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/spacer.md#tc001)
- [ ] Spacer block - Settings: Control spacer height using the slider - [TC002](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/spacer.md#tc002)
- [ ] Spacer block - Settings: Control spacer height using the text input - [TC003](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/spacer.md#tc003)

### Buttons-1

- [ ] Buttons block - Buttons block is added with focused Button with gray background color and white text color - [TC001](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/buttons.md#tc001)
- [ ] Buttons block - Buttons inline appender - [TC002](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/buttons.md#tc002)
- [ ] Buttons block - Add another Button inside Buttons using inserter - [TC003](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/buttons.md#tc003)
- [ ] Buttons block - Button's wrapper grows properly - [TC023](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/buttons.md#tc023)

### Buttons-2

- [ ] Buttons block - Removing Button along with Buttons block - [TC004](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/buttons.md#tc004)
- [ ] Buttons block - Removing exactly one Button (when Buttons contain more of them) - [TC005](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/buttons.md#tc005)

### Buttons-3

- [ ] Buttons block - Wrapping Buttons - [TC006](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/buttons.md#tc006)
- [ ] Buttons block - Buttons alignment options - [TC007](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/buttons.md#tc007)

### Button-6

- [ ] Buttons block - Settings: Open in new tab - [TC011](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/buttons.md#tc011)
- [ ] Buttons block - Settings: Link rel - [TC012](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/buttons.md#tc012)
- [ ] Buttons block - Settings: Link URL - [TC010](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/buttons.md#tc010)
- [ ] Buttons block - Settings: Remove link - [TC014](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/buttons.md#tc014)
- [ ] Buttons block - Settings: Synchronize with button options - [TC013](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/buttons.md#tc013)

### Color Settings - 1
- [ ] Colors Segmented Controls - [TC001](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/color-settings.md#tc001)
- [ ] Scroll color palette to start - [TC002](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/color-settings.md#tc002)
- [ ] Scroll color palette to the end - [TC003](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/color-settings.md#tc003)

### Image - 1
- [ ] Image block - Insert image from device (failing) - [TC001](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/image.md#tc001)
- [ ] Image block - Insert image from device (cancel) - [TC002](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/image.md#tc002)
- [ ] Image block - Add Caption - [TC003](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/image.md#tc003)
- [ ] Image block - Close/Re-open post with an ongoing image upload - [TC004](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/image.md#tc004)
- [ ] Image block - Close post with an ongoing image upload - [TC005](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/image.md#tc005)

```

## Test Suite 3

- Gallery 2-4
- Columns 2-4
- MediaText 3-4
- Shortcode 1
- Cover 2
- Social Icons 2
- Image 2
- Story block 1

```
### Gallery - 2
- [ ] Gallery block - Insert image from device (failing) - [TC006](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/gallery.md#tc006)
- [ ] Gallery block - Insert image from device (cancel) - [TC009](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/gallery.md#tc009)

### Gallery - 3
- [ ] Gallery block - Add Gallery Caption - [TC003](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/gallery.md#tc003)
- [ ] Gallery block - Add Gallery Image Caption - [TC004](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/gallery.md#tc004)
- [ ] Gallery block - Try adding same images from WP Media library and moving the images around - [TC010](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/gallery.md#tc010)

### Gallery - 4
- [ ] Gallery block - Settings: Link to - [TC012](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/gallery.md#tc012)
- [ ] Gallery block - Settings: Column number - [TC013](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/gallery.md#tc013)
- [ ] Gallery block - Settings: Crop images - [TC014](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/gallery.md#tc014)

### Columns - 2
- [ ] Columns - Max limit of Column number - [steps](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/columns.md#tc005)
- [ ] Columns - Min limit of Column number - [steps](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/columns.md#tc006)
- [ ] Columns - Removing Column with remove button - [steps](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/columns.md#tc007)
- [ ] Columns - Removing the only one left Column with remove button - [steps](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/columns.md#tc008)
- [ ] Columns - Changing alignment on Columns - [steps](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/columns.md#tc009)
- [ ] Columns - Changing alignment on individual Columnn - [steps](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/columns.md#tc010)
- [ ] Columns - Alignment attribute is properly passed when adding Column - [steps](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/columns.md#tc011)
- [ ] Columns - Deep nesting is possible (iOS only)- [steps](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/columns.md#tc012)

### Columns - 3
- [ ] Columns - Check if Column placeholders is visible for the unselected state - [steps](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/columns.md#tc002)
- [ ] Columns - Appearance in vertical device position (vertical layout) - [steps](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/columns.md#tc013)
- [ ] Columns - Appearance in horizontal device position (horizontal layout) - [steps](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/columns.md#tc014)
- [ ] Columns - Mover direction - [steps](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/columns.md#tc015)
- [ ] Columns - Check if Column placeholder is render in nested structure - [steps](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/columns.md#tc016)
- [ ] Columns - Unselected Column placeholder is streched to content in nested structure- [steps](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/columns.md#tc017)

### Columns - 4
- [ ] Columns - Check if in DarkMode all components gets proper colors - [steps](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/columns.md#tc018)

### MediaText - 3
- [ ] Media Text block - Insert video from device (failing) - [TC001-v](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/media-text.md#tc001-v)
- [ ] Media Text block - Close/Re-open post with an ongoing video upload - [TC003-v](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/media-text.md#tc003-v)

### MediaText - 4
- [ ] Media Text block - Media & Text alignment - [TC006](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/media-text.md#tc006)
- [ ] Media Text block - Vertical alignment - [TC007](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/media-text.md#tc007)

### Shortcode-1
- [ ] Shortcode block - Add a youtube link - [steps](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/shortcode.md#tc001)

### Cover - 2

- [ ] Cover - Add Video Background from WordPress Media library - [TC005](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/cover.md#tc005)
- [ ] Cover - Replace media - [TC006](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/cover.md#tc006)
- [ ] Cover - Gradient background is rendered properly - [TC007](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/cover.md#tc007)
- [ ] Cover - Gradient overlay is rendered properly - [TC008](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/cover.md#tc008)

### Social Icons - 2
- [ ] The link sheet is opened automatically when adding new icon - [TC004](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/social-icons.md#tc004)
- [ ] Ghost placeholder is visible when no icon is active - [TC005](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/social-icons.md#tc005)
- [ ] Social icon forwarding to the link - [TC006](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/social-icons.md#tc006)

### Image - 2
- [ ] Image block - Border style setting - [TC006](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/image.md#tc006)
- [ ] Image block - Image size setting - [TC007](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/image.md#tc007)
- [ ] Image block - Link to setting - [TC008](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/image.md#tc008)

### Story block - 1
- [ ] Story block - Verify is available in Block Picker - [TC001](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/jetpack/story.md#tc001)
- [ ] Story block - Verify is not available in Block Picker- [TC002](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/jetpack/story.md#tc002)
- [ ] Story block - Add media to empty Story block - [TC003](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/jetpack/story.md#tc003)
- [ ] Story block - Add media to non-empty Story block - [TC004](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/jetpack/story.md#tc004)
- [ ] Story block - Close/Re-open post with an ongoing Story upload - [TC005](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/jetpack/story.md#tc005)

```

## Test Suite 4

- DarkMode 2
- Group 2
- Spacer 2
- Buttons 4-5-7
- Editor Theme 2
- Color Settings 2

```
### DarkMode - 2

- [ ] Spacer block - Dark mode - [TC004](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/darkmode.md#tc004)
- [ ] Buttons block - Dark mode - [TC005](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/darkmode.md#tc005)
- [ ] Group - Dark mode - [TC006](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/darkmode.md#tc006)
- [ ] Columns - Dark mode - [TC007](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/darkmode.md#tc007)

### Group - 2

- [ ] Group - Navigation up button works as expected - [TC009](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/group.md#tc009)
- [ ] Group - Navigation down works according to parent-first approach - [TC010](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/group.md#tc010)
- [ ] Group - Cross navigation between blocks works as expected - [TC011](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/group.md#tc011)
- [ ] Group - Ungroup button works as expected - [TC012](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/group.md#tc012)
- [ ] Group - Check if in DarkMode all components gets proper colors - [TC013](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/group.md#tc013)
- [ ] Group - Check if nested Placeholder block can be replaced - [TC014](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/group.md#tc014)

### Spacer - 2

- [ ] Spacer block - Settings: Available height range is correct - [TC004](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/spacer.md#tc004)
- [ ] Spacer block - Settings: Height range extends if Spacer comes from the web is higher than 500px - [TC005](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/spacer.md#tc005)
- [ ] Spacer block - Spacer in horizontal layout works as expected - [TC006](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/spacer.md#tc006)

### Buttons - 4

- [ ] Buttons block - Render custom text color - [TC017](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/buttons.md#tc017)
- [ ] Buttons block - Render custom background color - [TC016](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/buttons.md#tc016)
- [ ] Buttons block - Render gradient background color - [TC018](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/buttons.md#tc018)
- [ ] Buttons block - Check if selection / caret color matches font color - [TC020](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/buttons.md#tc020)
- [ ] Buttons block - The newly created Buttons has set background color to the theme-default color in preview - [TC021](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/buttons.md#tc021)

### Buttons - 5

- [ ] Buttons block - Edit text styles - [TC009](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/buttons.md#tc009)
- [ ] Buttons block - Render theme colors - [TC019](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/buttons.md#tc019)
- [ ] Buttons block - Settings: Change Button border radius - [TC015](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/buttons.md#tc015)

### Buttons - 7

- [ ] Buttons block - Link from the clipboard is presented as an option in the link picker - [TC008](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/buttons.md#tc008)
- [ ] Buttons block - Toolbar link button is active when Button has link - [TC022](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/buttons.md#tc022)

### Editor Theme - 2
- [ ] Custom Gradients - Check that custom gradients load in the editor - [TC004](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/editor-theme.md#tc004)
- [ ] Offline Support - [TC005](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/editor-theme.md#tc005)

### Color Settings - 2
- [ ] Pressing color swatch - [TC004](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/color-settings.md#tc004)
- [ ] Customize gradient color - [TC005](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/color-settings.md#tc005)
- [ ] Custom color picker - [TC006](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/color-settings.md#tc006)

```

## Test Suite 4

- Video block 1-2
- File block 1-3
- Audio block 1-4
- Reusable block 1-2
- Embed block 1-2

```
Video block - 1
- [ ] Video block - Insert video from device (failing) - [steps](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/video.md#tc001)
- [ ] Video block - Close/Re-open post with an ongoing video upload - [steps](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/video.md#tc004)

Video block - 2
- [ ] Video block - Insert video from device (cancel) - [steps](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/video.md#tc002)
- [ ] Video block - Close post with an ongoing video upload - [steps](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/video.md#tc005)
- [ ] Video block - Add Caption - [steps](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/video.md#tc003)

File block - 1
- [ ] File block - Upload completes successfully from the device library - [steps](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/file.md#tc001)
- [ ] File block - Insert completes successfully from the WordPress Media library - [steps](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/file.md#tc002)
- [ ] File block - Upload fails from the device library - [steps](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/file.md#tc003)
- [ ] File block - Stop the file upload before it completes - [steps](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/file.md#tc004)

File block - 2
- [ ] File block - Close the post with an ongoing file upload - [steps](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/file.md#tc005)
- [ ] File block - Replace the selected files - [steps](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/file.md#tc006)
- [ ] File block - Change the alignment in the File Block - [steps](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/file.md#tc007)
- [ ] File block - The Link To Block Setting should open - [steps](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/file.md#tc008)

File block - 3
- [ ] File block - Open link in new tab - [steps](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/file.md#tc009)
- [ ] File block - Show/hide download button (Block Settings only) - [steps](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/file.md#tc010)
- [ ] File block - Copy file URL - [steps](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/file.md#tc011)
- [ ] File block - Close/Re-open post with an ongoing file upload - [steps](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/file.md#tc012)

Audio block - 1
- [ ] Audio block - Upload completes successfully from the device library - [steps](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/audio.md#tc001)
- [ ] Audio block - Insert completes successfully from the WordPress Media library - [steps](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/audio.md#tc002)

Audio block - 2
- [ ] Audio block - Upload fails from the device library - [steps](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/audio.md#tc003)
- [ ] Audio block - Stop the audio file upload before it completes - [steps](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/audio.md#tc004)

Audio block - 3
- [ ] Audio block - Close the post with an ongoing audio file upload - [steps](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/audio.md#tc005)
- [ ] Audio block - Replace the selected files - [steps](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/audio.md#tc006)
- [ ] Audio block - Change the alignment in the Audio Block - [steps](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/audio.md#tc007)

Audio block - 4
- [ ] Audio block - Autoplay setting - [steps](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/audio.md#tc008)
- [ ] Audio block - Loop setting - [steps](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/audio.md#tc009)
- [ ] Audio block - Close/Re-open post with an ongoing audio file upload - [steps](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/audio.md#tc010)

Reusable block - 1
- [ ] Reusable block - Add block - [steps](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/reusable.md#tc001)
- [ ] Reusable block - Convert to regular blocks - [steps](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/reusable.md#tc002)

Reusable block - 2
- [ ] Reusable block - Deleted reusable block - [steps](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/reusable.md#tc003)
- [ ] Reusable block - Recursive block rendering - [steps](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/reusable.md#tc004)

Embed block - 1
- [ ] Embed block - Inline previews are rendered correctly for the top 5 most-used providers - [steps](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/embed.md#tc001)

Embed block - 2
- [ ] Embed block - Inline previews are rendered accordingly for each alignment option - [steps](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/embed.md#tc002)
```
# Columns Block - Test Cases

--------------------------------------------------------------------------------

##### TC001

### Columns block is added with default number of Column

- Add a `Columns` block
- Expect `Columns` to have **two** `Column` block inside

Expected look:  
![DefaultColumnNoStacked](../resources/columns-default-number.png)
![DefaultColumnNoHorizontal](../resources/columns-default-number-horizontal.png)

--------------------------------------------------------------------------------

##### TC002

### Check if Column placeholders is visible for the unselected state

- Add a `Columns` block
- Deselect
- Expect to see placeholder for each `Column` added in `Columns`

Expected look:

Portrait | Landscape
-|-
![PlaceholderHorizontal](../resources/columns-placeholder-root-horizontal.png)|![PlaceholderStacked](../resources/columns-placeholder-root.png)


--------------------------------------------------------------------------------

##### TC003

### Adding Column with AppenderButton

- Add a `Columns` block
- Having `Columns` block selected press `AppenderButton`
- Expect new `Column` to be added

Expected look:  
![Appender](../resources/columns-appender.png)

--------------------------------------------------------------------------------

##### TC004

### Adding and removing Column with BottomSheet Stepper control

- Add a `Columns` block
- Open `Columns` settings with option button on toolbar
- Expect to increase `Column` number after press `+` button
- Expect to descrease `Column` number after press `-` button (exception: [see TC007](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/columns.md#tc007))

--------------------------------------------------------------------------------

##### TC005

### Max limit of Column number

- Add a `Columns` block
- Increase number of `Column`
- Expect have **no limit** with possible number of `Column` to add

--------------------------------------------------------------------------------

##### TC006

### Min limit of Column number

- Add a `Columns` block
- Increase number of `Column`
- Start removing `Column` using BottomSheet `Stepper`
- Expect to decrease `Column` number to minimum value of 1

Expected look:  
![StepperMinLimit](../resources/columns-stepper-min.png)

--------------------------------------------------------------------------------

##### TC007

### Removing Column with remove button

- Add a `Columns` block
- Increase number of `Column`
- Select one of the `Column` and press remove button
- Expect `Column` to be removed and selection is moved to previous one

Exception:

- If `Columns` has only one `Column` left [see TC009](https://github.com/wordpress-mobile/test-cases/blob/master/test-cases/gutenberg/columns.md#tc007)

--------------------------------------------------------------------------------

##### TC008

### Removing the only one left Column with remove button

- Add a `Columns` block
- Reduce `Column` number to one
- Having the last one `Column` selected press remove button
- Expect `Column` and whole `Columns` block to be removed

--------------------------------------------------------------------------------

##### TC009

### Changing alignment on Columns

- Add a `Columns` block
- Set `verticalAlignment` on `Columns` block
- Select one of the `Column`
- Expect selected `Column` have the same `verticalAlignment` value
- Expect the same `verticalAlignment` for other `Column` as well

--------------------------------------------------------------------------------

##### TC010

### Changing alignment on individual Columnn

- Add a `Columns` block
- Set `verticalAlignment` on `Columns` block
- Select one of the `Column`
- Set `verticalAlignment` on `Column` block
- Expect new `Column` have proper `verticalAlignment` value
- Go back with the selection to `Columns` block
- Expect `verticalAlignment` on `Columns` block doesn't change
- Select another `Column` block (different than before)
- Expect `verticalAlignment` on selected `Column` block doesn't change

--------------------------------------------------------------------------------

##### TC011

### Alignment attribute is properly passed when adding Column

- Add a `Columns` block
- Set `verticalAlignment` on `Columns` block
- Add new `Column`
- Expect new `Column` have the same `verticalAlignment` value

--------------------------------------------------------------------------------

##### TC012

### Deep nesting is possible (iOS only)

- Add a `Columns` block
- Nest blocks inside multiple `Columns` blocks (at least 3 levels deep)
- Expect app do not crash

--------------------------------------------------------------------------------

##### TC013

### Appearance in vertical device position (vertical layout)

- Add a `Columns` block
- Create some nested structure adding more `Column` and nesting `Columns`
- Expect all `Column` is stacked (only 1 `Column` in row is render)
- Expect space around blocks do not bounce when changing selection (exception is the trasition of the selected block connected with making space for FloatingToolbar)
- Expect no weird/unexpected extra free space around blocks
- Expect the space from screen edge to content should equals `16px`

Exception:

- If there is enought space (more than `480px`) for `Columns` then it will be render in `horizontal` layout

Expected look:  
![ColumnsVertical](../resources/columns-vertical-layout.png)

- Space of `16px` left/right

--------------------------------------------------------------------------------

##### TC014

### Appearance in horizontal device position (horizontal layout)

- Rotate device to horizontal position
- Add `Columns` block
- Create some nested structure adding more `Column` and nesting `Columns`
- Expect all `Column` is distributed in row depending on available space for container:
  - below `480px` then expect 1 `Column` in row to be rendered
  - between `480px` and `768px` then expect  2 `Column` in row to be rendered
  - more than `768px` then expect as much `Column` as possible in row to be rendered
- Expect space around blocks do not bounce when changing selection (exception is the trasition of the selected block connected with making space for FloatingToolbar)
- Expect no weird/unexpected extra free space around blocks
- Expect the space around each `Column` should equals `16px`

Expected look:  
![ColumnsHorizontal](../resources/columns-horizontal-layout.png)

- Space of `16px` left/right/top/bottom

--------------------------------------------------------------------------------

##### TC015

### Mover direction

- Add `Columns` block
- Create some nested structure adding more `Column` and nesting `Columns`
- Make `Column` stacked in `Columns` by rotate device to vertical position
- Select `Column`
- Expect `Mover` controls be in vertical position
- Switch `Columns` to horizontal layout by rotate device to horizontal position
- Select `Column`
- Expect `Mover` controls be in horizontal position
- Expect nested `Column` has proper `Mover` position

Expected look:  
![MoverVertical](../resources/columns-mover-vertical.png)
![MoverHorizontal](../resources/columns-mover-horizontal.png)

--------------------------------------------------------------------------------

##### TC016

### Check if Column placeholder is render in nested structure

- Add a `Columns` block
- Nest some `Columns` inside one of the `Column`
- Select top-most `Columns` block in hierarchy
- Check if you are able to see `Column` placeholder of nested blocks wrapped with dashed border when the parent is selected
- Select one of the `Column`
- Expect to see it's `AppenderButton` after selecting last `Column`  

Expected look:  
![PlaceholderNested](../resources/columns-placeholder-nested.png)

- Post title is not dimmed
- Navigation arrows is not visible
- Only selected block title is visible in breadcrumbs

--------------------------------------------------------------------------------

##### TC017

### Unselected Column placeholder is streched to content in nested structure

- Add a `Columns` block
- Switch to `horizontal` layout
- Add some blocks inside one of the `Column`
- Select top-most `Columns` block in hierarchy
- Expect empty `Column` placeholder to be stretched accordingly
- Select `Column` with the content
- Expect empty `Column` placeholder in the same row to be stretched accordingly

Expected look:  
![PlaceholderStretched](../resources/columns-placeholder-stretched.png)

- Post title is not dimmed
- Navigation arrows is not visible
- Only selected block title is visible in breadcrumbs
- Placeholder (dashed line is stretched to content)

--------------------------------------------------------------------------------

##### TC018

### Check if in DarkMode all components gets proper colors

- Add a `Columns` block
- Create nested structure
- Switch to DarkMode
- Check if all components switch it's color schema to dark

Expected look:  
![DarkMode](../resources/columns-dark-mode.png)
![DarkModeEmpty](../resources/columns-dark-mode-empty.png)

--------------------------------------------------------------------------------

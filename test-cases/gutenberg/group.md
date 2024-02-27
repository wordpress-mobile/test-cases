# Group Block - Test Cases

--------------------------------------------------------------------------------
##### TC001

### Deep nesting is possible (verify iOS does not crash)

-   Add a `Group` block
-   Nest blocks inside multiple `Group` blocks (at least 3 levels deep)
-   Check if app do not crash

--------------------------------------------------------------------------------

##### TC002

### Check if Group placeholder is visible for the unselected state

-   Add a `Group` block
-   Deselect
-   Check if you are able to see `Group` placeholder

Expected look:  
![Progress](../resources/group-placeholder-root.png)

--------------------------------------------------------------------------------

##### TC003

### Check if Group placeholder is render in nested structure

-   Add a `Group` block
-   Nest some `Group` inside
-   Select top-most `Group` block in hierarchy
-   Check if you are able to see `Group` placeholder of nested blocks
-   Go down in the hierarchy observing if margins is kept (the whole UI should remain the same)
-   After selecting last `Group` you should be able to see it's `AppenderButton`

Expected look:  
![PlaceholderNestes](../resources/group-placeholder-nest-1.png)
 - Navigation arrows is not visible
 - Only selected block title is visible in breadcrumbs

![PlaceholderDeepNested](../resources/group-placeholder-nest-deep.png)
 - Navigation arrows is visible
 - Navigation arrows are disable depending on order in block
 - Show parent in breadcrumbs

--------------------------------------------------------------------------------

##### TC004

### Nested block have proper border styling

-   Add a `Group` block
-   Nest some blocks inside
-   Check if each selected block gets solid blue border
-   Select parent block
-   Check if the parent block gets a solid blue border
-   Check if each nested block don't display a border

Expected look:  
![BorderStyling](../resources/group-border-styling.png)

--------------------------------------------------------------------------------

##### TC005

### Breadcrumbs on FloatingToolbar is properly displayed

-   Add a `Group` block
-   Create nested structure
-   Expect only selected block title is visible in `Breadcrumbs` on root list level
-   Expect focused block title and focused block icon are visible in `Breadcrumbs` on deeper levels
-   Expect top most parent block icon is visible in `Breadcrumbs` on deeper levels
-   Expect `Breadcrumbs` renders navigation up button on deeper levels

Expected look:  
![BreadcrumbsRoot](../resources/group-breadcrumbs-root.png)
  
![BreadcrumbsNested](../resources/group-breadcrumbs-nested.png)

--------------------------------------------------------------------------------

##### TC010

### Check if nested Placeholder block can be replaced

-   Open New Post (it is very important to start with blank post)
-   Add a `Group` block
-   Add empty `Paragraph` inside the created block
-   Make sure that the created paragraph is empty and selected
-   Press on `Inserter` button and select block to add
-   The paragraph should be replaced by selected block

--------------------------------------------------------------------------------

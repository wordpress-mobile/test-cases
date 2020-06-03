
# Verse Block - Test Cases

--------------------------------------------------------------------------------

##### TC001

### Tapping return key creates a new line within the block

-   Add a Verse block
-   Type some text and tap the return key
-   Expect the verse block to grow as new lines are created within the block

--------------------------------------------------------------------------------

##### TC002

### Setting text alignment works as expected

- Add a verse block
- Type some text, tap the alignment option in the toolbar and expect a bottom sheet to be shown with alignment options
- Choosing an alignment option should apply that to the block's content 

--------------------------------------------------------------------------------

##### TC003

### Whitespace is preserved when applying formatting options (bold, italics, etc)

- Add a verse block
- Type some spaces and then text, such as:
  `      Hello`
- Bold the Hello portion of the line using the toolbar bold B button (don't use the native iOS edit menu)
- Expect the text to be bolded and the whitespace to be preserved

--------------------------------------------------------------------------------

##### TC004

### The verse block can be merged with the paragraph block

- Add a paragraph block and type some text into it
- Add a verse block and add some text to it
- Position the cursor at the start of the verse block
- Tap backspace until the blocks merge
- Expect the content of the verse block to be appended to the paragraph block content

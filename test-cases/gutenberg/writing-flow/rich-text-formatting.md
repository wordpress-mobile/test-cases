
# Rich Text Formatting - Test Cases

--------------------------------------------------------------------------------

#### **Precondition**

Have a rich-text based component with content (Paragraph, Heading, Quote, Media Caption, etc...)

--------------------------------------------------------------------------------

##### TC007

### Test format detection under the cursor

- On a rich-text based component, add bold, italic, strikethrough and link formatted text, both combined and on different words.
Move the cursor around
- Check that the proper format buttons get selected when the cursor get under a formatted word.

--------------------------------------------------------------------------------

##### TC009

### Test autocorrection doesn't apply formatting to Heading

- Add a Heading block without any formatting applied.
- Type a sentence with a word misspelled that will be autocorrected by the editor.
- Highlight the word that was autocorrected.
- Check that the word has no formatting applied.

--------------------------------------------------------------------------------

##### TC010

### Test autocorrection doesn't remove formatting from Heading

- Add a Heading block and apply any formatting (e.g. bold, italics).
- Type a sentence with a word misspelled that will be autocorrected by the editor.
- Highlight the word that was autocorrected.
- Check that the word's formatting hasn't changed.

--------------------------------------------------------------------------------


# Rich Text Formatting - Test Cases

#### **Precondition**

Have a rich-text based component with content (Paragraph, Heading, Quote, Media Caption, etc...)

##### TC001

**Bold, Italic, strikethrough buttons**

- Press the Bold button and write a bold word.
- Press the Italic button and write an italic word.
- Press strikethrough button and write strikethrough text.

**Known Issues**
- **[Android]** Strikethrough formatting uses a different tag depending on how it is applied and strikethrough button does not always reflect state: [#729](https://github.com/wordpress-mobile/gutenberg-mobile/issues/729).


##### TC002

**Alignment buttons**

- Press Left, Right, Center alignment buttons.
- Check that the text responds accordingly.


##### TC003

**Alignment Split**

- Write some lines on a paragraph block.
- Set an alignment on the block.
- Move the caret by the half of the text and press enter to split it.
- Check that the new block has the same alignment.
- Check that the text alignment corresponds to the setting.


##### TC004

**Link button works without selection**

- Press the links button 
- Fill the options and dismiss to add a link.
- The link formatted word should be added to the block.


##### TC005

**Link button works with a selected word**

- Write a word and select it.
- Press the link format button.
- Check that the `Link Text` field is pre-filled with the selected word.
- Add a URL and dismiss.
- The selected word now should be formatted as a link.


##### TC006

**Adding a link from a copied URL**

- Go to a browser and copy a URL to the clipboard.
- Back to Gutenberg, select a word on a rich-text based component.
- Press the Link format button.
- Check that the copied URL is pre-filled on the URL field.
- Dismiss the bottom-sheet to see the selected word formatted as a link.


##### TC007

**Test format detection under the cursor**

- On a rich-text based component, add bold, italic, strikethrough and link formatted text, both combined and on different words.
Move the cursor around
- Check that the proper format buttons get selected when the cursor get under a formatted word.


**Known Issues**
- **[Android]** Strikethrough button might not be highlighted in some cases. [#729](https://github.com/wordpress-mobile/gutenberg-mobile/issues/729)
- Formating buttons aren’t updated accordingly when text is deleted [#2154](https://github.com/wordpress-mobile/gutenberg-mobile/issues/2154)

##### TC008

**Test formatting doesn't remove leading or trailing whitespace**

- Add a text block, paragraph for example
- Type some spaces, then write some text
- Select the text and apply one format, for example, bold
- Check that the white spaces aren't removed.

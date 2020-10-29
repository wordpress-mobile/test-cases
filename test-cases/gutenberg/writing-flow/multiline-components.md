
# Multiline components - Test Cases

Test the next steps on:
- Quote block
- Verse block
- Preformatted block 
- Code block (DEV only)
- Pullquote block

##### TC001

**Known Issues**
- On Android, tapping Enter to split a quote or pullquote citation both splits the block and adds a newline to the citation ([#2498](https://github.com/wordpress-mobile/gutenberg-mobile/issues/2498))

**New line on multiline components**

- Start typing and press enter to create a new line.
- The new line should be created, without splitting the block.
- On citations, pressing Enter at the end of a citation splits the block, but pressing enter in the middle of a citation creates a new line.
- Check on HTML mode that the resulting HTML code is correct:
  - *Quote*: `<p>` tags per paragraph.
  - *Quote citation*: `<br>` ending lines.
  - *Verse*: `<br>` ending lines.
  - *Preformatted*: `<br>` ending lines.
  - *Code*: (Invisible `\n`) new line character.
  - *Pullquote*: `<p>` tags per non-wrapping "line"
  - *Pullquote citation*: `<br>` ending lines.


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
- On Android, pressing enter multiple times in the content of a Pullquote or Quote block causes unintended behavior ([#27690](https://github.com/WordPress/gutenberg/issues/27690))
- On Android, there is sometimes a loss of lines when entering multiple lines. ([#29861](https://github.com/WordPress/gutenberg/issues/29861))
- There is sometimes inconsistent HTML surrounding newlines in the Pullquote and Quote Block.  ([#1396](https://github.com/WordPress/gutenberg/issues/1396))
- On Android, pressing enter multiple times in a Pullquote removes lines as reported in ([#27690](https://github.com/WordPress/gutenberg/issues/27690)). Once that happens hitting backspace to delete characters adds characters to words being deleted ([#3495](https://github.com/wordpress-mobile/gutenberg-mobile/issues/3495))

**New line on multiline components**

- Start typing and press enter to create a new line.
- The new line should be created, without splitting the block.
- On citations, pressing Enter at the end of a citation splits the block, but pressing enter in the middle of a citation creates a new line.
- Check on HTML mode that the resulting HTML code is correct:
  - *Quote*: `<p>` tags per paragraph.
  - *Quote citation*: `<br>` on line-breaks.
  - *Verse*: `<br>` on line-breaks.
  - *Preformatted*: `<br>` on line-breaks.
  - *Code*: (Invisible `\n`) new line character.
  - *Pullquote*: `<p>` tags per non-wrapping "line"
  - *Pullquote citation*: `<br>` on line-breaks.

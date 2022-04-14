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
- On Android, there is sometimes a loss of lines when entering multiple lines. ([#29861](https://github.com/WordPress/gutenberg/issues/29861))
- On Android, the line spacing between the first two lines in the preformatted and verse blocks appear closer together in the editor than other lines. ([#38636](https://github.com/WordPress/gutenberg/issues/38636))
- There is sometimes inconsistent HTML surrounding newlines in the Pullquote and Quote Block. ([#1396](https://github.com/wordpress-mobile/gutenberg-mobile/issues/1396))

**New line on multiline components**

- Start typing and press enter to create a new line.
- The new line should be created, without splitting the block.
- On citations, pressing Enter at the end of a citation splits the block, but pressing enter in the middle of a citation creates a new line.
- Check on HTML mode that the resulting HTML code is correct:
  - _QuoteV1_: `<p>` tags per paragraph. **(This is for QuoteV1 _only_. QuoteV2 uses inner blocks instead)**
  - _Quote citation_: `<br>` on line-breaks.
  - _Verse_: `<br>` on line-breaks.
  - _Preformatted_: `<br>` on line-breaks.
  - _Code_: (Invisible `\n`) new line character.
  - _Pullquote_: `<p>` tags per non-wrapping "line"
  - _Pullquote citation_: `<br>` on line-breaks.

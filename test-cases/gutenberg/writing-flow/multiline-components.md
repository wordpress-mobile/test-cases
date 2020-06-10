
# Multiline components - Test Cases

Test the next steps on:
- Quote block
- Verse block
- Preformatted block 
- Code block (DEV only)
- Pullquote block

##### TC001

**Known Issues**
- On captions, pressent Enter at the end of a caption splits the block, but pressing enter in the middle of a caption's text does nothing. Discussed in [this comment](https://github.com/WordPress/gutenberg/pull/22928#issuecomment-640879690).

**New line on multiline components**

- Start typing and press enter to create a new line.
- The new line should be created, without splitting the block.
- Check on HTML mode that the resulting HTML code is correct:
  - *Quote*: `<p>` tags per paragraph.
  - *Quote citation*: should _not_ be multiline (see Known Issues)
  - *Verse*: `<br>` ending lines.
  - *Preformatted*: `<br>` ending lines.
  - *Code*: (Invisible `\n`) new line character.
  - *Pullquote*: `<p>` tags per non-wrapping "line"
  - *Pullquote citation*: should _not_ be multiline (see Knwon Issues)

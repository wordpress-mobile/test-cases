
# Multiline components - Test Cases

Test the next steps on:
- Quote block
- Verse block
- Preformatted block 
- Code block (DEV only)
- Image/video/gallery block caption
- Pullquote block

##### TC001

**New line on multiline components**

- Start typing and press enter to create a new line.
- The new line should be created, without splitting the block.
- Check on HTML mode that the resulting HTML code is correct:
  - *Quote*: `<p>` tags per paragraph.
  - *Quote citation*: `<br>` ending lines.
  - *Verse*: `<br>` ending lines.
  - *Preformatted*: `<br>` ending lines.
  - *Code*: (Invisible `\n`) new line character.
  - *Captions (Image, Video, Gallery)*: `<br>` ending lines.
  - *Pullquote*: `<p>` tags per non-wrapping "line"
  - *Pullquote citation*: `<br>` between non-wrapping "lines"

**Known Issues**
- **[Android]** Multiline captions are not working as expected. [#1651](https://github.com/wordpress-mobile/gutenberg-mobile/issues/1651)

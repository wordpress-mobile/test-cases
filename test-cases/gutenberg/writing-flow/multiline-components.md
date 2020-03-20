
# Multiline components - Test Cases

Thest the next steps on:
- Quote block
- Verse block
- Preformatted block
- Code block
- Image/video/gallery block caption.

##### TC001

**New line on multiline components**

- Start typing and press enter to create a new line.
- The new line should be created, without splitting the block.
- Check on HTML mode that the resulting HTML code is correct:
  - *Quote*: `<p>` tags per paragraph.
  - *Quote citation*: `<br>` ending lines.
  - *Verse*: `<br>` ending lines.
  - *Prefirnatted*: `<br>` ending lines.
  - *Code*: (Invisible `\n`) new line character.
  - *Captions (Image, Video, Gallery)*: `<br>` ending lines.



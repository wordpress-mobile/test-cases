# Basic Test Suite

This suite groups the different test cases that are considered the minimum coverage when testing the editor:

- [Writing Flow](https://github.com/wordpress-mobile/test-cases/tree/trunk/test-cases/gutenberg/writing-flow)
- [Unsupported Block Editing](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/unsupported-block-editing.md)
- Gallery Block
    - [Choose from device (stay in editor) - Successful upload](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/gallery.md#tc005)

In the following section you can find a convenient checklist format to paste in PRs:

```
## Basic Test Suite Checklist
### Writing Flow

#### Rich Text Format
- [ ] [TC007](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/writing-flow/rich-text-formatting.md#tc007) - Test format detection under the cursor
- [ ] [TC009](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/writing-flow/rich-text-formatting.md#tc009) - Test autocorrection doesn't apply formatting to Heading
- [ ] [TC010](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/writing-flow/rich-text-formatting.md#tc010) - Test autocorrection doesn't remove formatting from Heading
##### Splitting and merging
- [ ] [TC001](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/writing-flow/splitting-merging.md#tc001) - Merge after writing
  - [ ] Paragraph
  - [ ] Heading
- [ ] [TC002](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/writing-flow/splitting-merging.md#tc002) - Merge after selection
  - [ ] Paragraph
  - [ ] Heading
- [ ] [TC003](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/writing-flow/splitting-merging.md#tc003) - Merge after deleting text
  - [ ] Paragraph
  - [ ] Heading
- [ ] [TC004](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/writing-flow/splitting-merging.md#tc004) - Merge after deleting all
  - [ ] Paragraph
  - [ ] Heading
- [ ] [TC005](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/writing-flow/splitting-merging.md#tc005) - Merge multiple blocks
  - [ ] Paragraph
  - [ ] Heading


### Unsupported Block
- [ ] [TC001](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/unsupported-block-editing.md#tc001) - User can edit unsupported blocks on Simple WP.com sites
- [ ] [TC002](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/unsupported-block-editing.md#tc002) - User can discard edits to an unsupported block on Simple WP.com sites
- [ ] [TC003](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/unsupported-block-editing.md#tc003) - Editing unsupported blocks is allowed on Gutenberg-enabled Atomic sites
- [ ] [TC004](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/unsupported-block-editing.md#tc004) - Editing unsupported blocks is disallowed on Classic-enabled Atomic sites
- [ ] [TC005](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/unsupported-block-editing.md#tc005) - Editing unsupported blocks is enabled on self-hosted sites accessed via Jetpack
- [ ] [TC006](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/unsupported-block-editing.md#tc006) - Editing unsupported blocks is disallowed on self-hosted sites access via their own username and password

### Gallery Block
- [ ] [TC005](https://github.com/wordpress-mobile/test-cases/blob/trunk/test-cases/gutenberg/gallery.md#tc005) - Choose from device (stay in editor) - Successful upload
```
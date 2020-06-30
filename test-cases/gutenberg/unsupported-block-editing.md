# Unsupported Block Editing - Test Cases

--------------------------------------------------------------------------------

##### TC001

### New edits are persisted 

1. Add a block that's not yet supported on mobile (e.g. the Jetpack Markdown `jetpack/markdown` block) — this can be done by switching to HTML mode and pasting in the raw content

    Example HTML:
    ```
    <!-- wp:jetpack/markdown {\"source\":\"Hello\\nWorld\"} -->\n<div class=\"wp-block-jetpack-markdown\"><p>Hello\nWorld</p>\n</div>\n<!-- /wp:jetpack/markdown -->
    ```
2. Switch back to visual Visual mode if needed
3. Expect to see the block rendered as a placeholder with the text "Unsupported"
4. Tap the `(?)` icon and expect the option to edit the block in a web browser to be shown
5. Tap the edit in a web browser and expect the block to be shown, ready to edit, in a new screen
6. Edit the block content (e.g. update its text)
7. Tap the Continue button and expect to be taken back to the block editor
8. Publish the post and verify it contains the edited block content


##### TC002

### Discarded edits are not persisted

1. Repeat steps 1 to 6 above
2. Tap the Cancel button and expect to be taken back to the block editor
3. Publish the post and verify it **does not** contain the edited block content

# Unsupported Block Editing - Test Cases

--------------------------------------------------------------------------------

##### TC001

### Editing changes are persisted 

-   Add a block that's not yet supported on mobile (e.g. the Jetpack Markdown `jetpack/markdown` block) — this can be done by switching to HTML mode and pasting in the raw content

    Example HTML:
    ```
    <!-- wp:jetpack/markdown {\"source\":\"Hello\\nWorld\"} -->\n<div class=\"wp-block-jetpack-markdown\"><p>Hello\nWorld</p>\n</div>\n<!-- /wp:jetpack/markdown -->
    ```
-   Switch back to visual Visual mode if needed
-   Expect to see the block rendered as a placeholder with the text "Unsupported"
-   Tap the `(?)` icon and expect the option to edit the block in a web browser to be shown
-   Tap the edit in a web browser and expect the block to be shown, ready to edit, in a new screen
-   Edit the block content (e.g. update its text)
-   Tap the Continue button and expect to be taken back to the block editor
-   Publish the post and verify it contains the edited block content


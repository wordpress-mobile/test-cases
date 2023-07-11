
# Synced patterns - Test Cases

## Preparation

**For testing this, it's required to create a pattern via the web version, here are the steps:**

- On a web browser, navigate to the [patterns page](https://wordpress.com/types/wp_block).
- Select the WP.com site for testing.
- Click on "Add new pattern".
- Add a title.
- Add some blocks.
- Publish it.

The pattern page can be also used for editing and deleting patterns.

##### TC001

**Add pattern**

**Steps**
- Tap on ➕ button.
- Tap on "Synced patterns" tab.
- Tap one of the items.
- Once inserted, tap on the block to edit it.

**Expected Behavior**
- Expect to see the pattern and its content.
- Expect to see the block's name in the block's header.

<kbd><img src="../resources/rb-inserter-menu.png" width="320"></kbd>
<kbd><img src="../resources/rb-preview-content.png" width="320"></kbd>

- Expect to see a warning message when trying to edit the block.

<kbd><img src="../resources/rb-edit-block-warning-message.png" width="320"></kbd>

--------------------------------------------------------------------------------

##### TC002

**Detach pattern**

**Steps**
- Open the block settings.
- Tap on "Detach pattern".

**Expected Behavior**
- Expect to see the content of the block as individual blocks.

<kbd><img src="../resources/rb-convert-to-regular-blocks.gif" width="320"></kbd>

**Next Steps**

- Tap the undo button.

**Expected Behavior**
- Expect to restore the pattern.

<kbd><img src="../resources/rb-convert-to-regular-blocks-undo.gif" width="320"></kbd>

**Next Steps**

- Tap the redo button.

**Expected Behavior**
- Expect to see the same blocks as after the conversion.

<kbd><img src="../resources/rb-convert-to-regular-blocks-redo.gif" width="320"></kbd>

--------------------------------------------------------------------------------

##### TC003

**Deleted pattern**

**Steps**
- On a web browser, navigate to the [patterns page](https://wordpress.com/types/wp_block).
- Select the WP.com site for testing.
- Create two patterns (you can find more info about creating a pattern in the <a href="#preparation">`Preparation` section</a>).
- Add the second pattern as part of the content of the first one and update it.
- Delete the second pattern from the "Patterns page" (referenced above).
- The second pattern will go to the trashed tab, delete it permanently.
- Switch to mobile device for the last step.
- Add the first pattern to a post/page.

**Expected Behavior**
- Expect to see a warning box within the block content referencing the deleted block.

<kbd><img src="../resources/rb-deleted-reusable-block.png" width="320"></kbd>

--------------------------------------------------------------------------------

##### TC004

**Recursive block rendering**

**Steps**

- On a web browser, navigate to the [patterns page](https://wordpress.com/types/wp_block).
- Select the WP.com site for testing.
- Create a pattern (you can find more info about creating a pattern in the <a href="#preparation">`Preparation` section</a>).
- Edit the pattern, add the same pattern as part of the content and update it.
- Observe that the block will show a warning box with text: `Block cannot be rendered inside itself.`.
- Switch to mobile device for the last step.
- Add the pattern to a post/page.

**Expected Behavior**

- Expect to see a warning box (same as it's shown in the web version) within the block content instead of rendering multiple times the same block.

<kbd><img src="../resources/rb-recursive-block-rendering.png" width="320"></kbd>

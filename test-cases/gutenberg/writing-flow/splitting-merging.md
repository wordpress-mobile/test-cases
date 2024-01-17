# Splitting and merging - Test Cases

**Known Issues**
- **[Android]** Splitting block before "swiped" word loses "swiped" word https://github.com/wordpress-mobile/gutenberg-mobile/issues/2373

--------------------------------------------------------------------------------

#### **Precondition**

Start from an empty post.

*Initial steps* 

- Repeat the next steps on a Paragraph and Heading block
- Write (or paste) a paragraph with a few lines
- Set the caret by the half of the paragraph
- Press Enter (Intro) to split the block into two.

--------------------------------------------------------------------------------

##### TC001

**Known Issues**

- **[Android]** Deleting "swiped" or selected words can prevent merging two blocks https://github.com/wordpress-mobile/gutenberg-mobile/issues/2375

**Merge after writing**
- Follow the initial steps.
- Expect the keyboard to not hide and show while splitting the blocks, it should be always visible.
- Write some more text where the caret is placed (beginning of new block).
- Delete all new text using the delete button until the blocks are merged again.
- Check that the blocks were merged.
- Expect the keyboard to not hide and show while merging the blocks, it should be always visible.

--------------------------------------------------------------------------------

##### TC002

**Known Issues**
- **[Android]** Deleting "swiped" or selected words prevents merging blocks https://github.com/wordpress-mobile/gutenberg-mobile/issues/2375
  - In some cases, this test will fail for words typed character by character, for example with gboard, but may succeed with other keyboards (such as [hacker keyboard](https://play.google.com/store/apps/details?id=org.pocketworkstation.pckeyboard&hl=en_US&gl=US)).

**Merge after selection**
- Follow the initial steps.
- Expect the keyboard to not hide and show while splitting the blocks, it should be always visible.
- Write some more text where the caret is placed (beginning of new block)
- Select all the newly written text,
- Press delete to remove all selected text.
- Press delete once again to merge the blocks.
- Check that the blocks were merged.
- Expect the keyboard to not hide and show while merging the blocks, it should be always visible.

--------------------------------------------------------------------------------

##### TC003

**Known Issues**
- **[Android]** Deleting "swiped" or selected words prevents merging blocks https://github.com/wordpress-mobile/gutenberg-mobile/issues/2375
- **[Android]** Heading block stops being rendered as a header when deleting the first word https://github.com/wordpress-mobile/gutenberg-mobile/issues/3106

**Merge after deleting text**
- Follow the initial steps.
- Expect the keyboard to not hide and show while splitting the blocks, it should be always visible.
- Move the caret a few words.
- Delete all those words until the blocks merge.
- Check that the blocks were merged.
- Expect the keyboard to not hide and show while merging the blocks, it should be always visible.

--------------------------------------------------------------------------------

##### TC004

**Known Issues**
- **[Android]** Deleting "swiped" or selected words prevents merging blocks https://github.com/wordpress-mobile/gutenberg-mobile/issues/2375

**Merge after deleting all**
- Follow the initial steps.
- Expect the keyboard to not hide and show while splitting the blocks, it should be always visible.
- Select and remove all content of the new block
- Press delete to remove the empty block.
- Check that the previous block was selected.
- Expect the keyboard to not hide and show while deleting and merging with the previous block, it should be always visible.

--------------------------------------------------------------------------------

##### TC005

**Merge multiple blocks**
- Follow the initial steps.
- Press enter two times to create an empty block in between.
- Expect the keyboard to not hide and show while splitting the blocks, it should be always visible.
- Press back two times to merge everything again.
- Check that the blocks were merged.
- Expect the keyboard to not hide and show while merging the blocks, it should be always visible.


# Splitting and merging - Test Cases

#### **Precondition**

Start from an empty post.

*Initial steps* 

- Repeat the next steps on a Paragraph and Heading block
- Write (or paste) a paragraph with a few lines
- Set the caret by the half of the paragraph
- Press Enter (Intro) to split the block into two.


##### TC001

**Known Issues**

- [Android] If you enter text by swiping after the split, you cannot merge after deleting the text. [issue comment](https://github.com/wordpress-mobile/gutenberg-mobile/issues/1873#issuecomment-608070758)

**Merge after writing**
- Follow the initial steps.
- Write some more text where the caret is placed (beginning of new block).
- Delete all new text using the delete button until the blocks are merged again.
- Check that the blocks were merged.


##### TC002

**Merge after selection**
- Follow the initial steps.
- Write some more text where the caret is placed (beginning of new block)
- Select all the newly written text,
- Press delete to remove all selected text.
- Press delete once again to merge the blocks.
- Check that the blocks were merged.

**Known Issues**
- **[Android]** Described on https://github.com/wordpress-mobile/WordPress-Android/pull/11572#issuecomment-607352657, also noted on [this ticket](https://github.com/wordpress-mobile/gutenberg-mobile/issues/1873#issue-561855507).

##### TC003

**Merge after deleting text**
- Follow the initial steps.
- Move the caret a few words.
- Delete all those words until the blocks merge.
- Check that the blocks were merged.

**Known Issues**
- **[Android]** Does not merge on Android after deleting either styled text or a selection containing multiple charaacters (instead of single characters): [#1873](https://github.com/wordpress-mobile/gutenberg-mobile/issues/1873#issuecomment-608070758).


##### TC004

**Merge after deleting all**
- Follow the initial steps.
- Select and remove all content of the new block
- Press delete to remove the empty block.
- Check that the previous block was selected.

**Known Issues**
- **[Android]** Described on https://github.com/wordpress-mobile/WordPress-Android/pull/11572#issuecomment-607352657, also noted on [this ticket](https://github.com/wordpress-mobile/gutenberg-mobile/issues/1873#issue-561855507).

##### TC005

**Merge multiple blocks**
- Follow the initial steps.
- Press enter two times to create an empty block in between 
- Press back two times to merge everything again.
- Check that the blocks were merged.


##### TC006

**Splitting/merge list block**

- Write some items on a list block
- Put the caret by the half of them (at the end of the item) and press Enter to create a new item.
- Press Enter again to split the block into two, with an empty paragraph block in the middle. The paragraph block at the middle should be focused.
- Write something on that newly created paragraph block.
- Move the cursor to the beginning of the paragraph block
- Press delete to merge the paragraph block with the upper list block.
- Check that the new word should be a new list item.
- Move the caret to the beginning of the second list block.
- Press delete once to merge it back into the first list block.
- Check that everything was merged and there’s just one list block.


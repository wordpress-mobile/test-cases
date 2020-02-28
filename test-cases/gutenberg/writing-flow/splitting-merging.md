
# Splitting and merging - Test Cases

#### **Precondition**

Start from an empty post, and follow this starting steps on every test case:
- Repeat the next steps on a Paragraph and Heading block
- Write (or paste) a paragraph with a few lines
- Set the caret by the half of the paragraph
- Press Enter (Intro) to split the block into two.


##### TC001

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


##### TC003

**Merge after deleting text**
- Follow the initial steps.
- Move the caret a few words.
- Delete all those words until the blocks merge.
- Check that the blocks were merged.


##### TC004

**Merge after deleting all**
- Follow the initial steps.
- Select and remove all content of the new block
- Press delete to remove the empty block.
- Check that the previous block was selected.


##### TC005

**Merge multiple blocks**
- Follow the initial steps.
- Press enter two times to create an empty block in between 
- Press back two times to merge everything again.
- Check that the blocks were merged.





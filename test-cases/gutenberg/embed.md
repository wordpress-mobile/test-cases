# Embed Block - Test Cases
##### TC001

**Inline previews are rendered correctly for the top 5 most-used providers**

#### **Precondition**

Perform these tests for each of the top 5 most-used providers below. 
 1. YouTube
 2. Twitter
 3. Instagram
 4. WordPress
 5. Vimeo

*Initial steps* 

- Open the Inserter. 
- Add a specific provider from the list above. 

**Steps**
- Add a link to be previewed. 

**Expected Behavior**
- Verify that there are no style issues and the preview is rendered as expected.

--------------------------------------------------------------------------------

##### TC002

**Inline previews are rendered accordingly for each alignment option.**

#### **Precondition**

*Initial steps* 

- Add an Embed block
- Add a valid embed URL.


### 1. Default alignment

**Expected Behavior**
- Observe that the preview content is centered and covers the entire block.

### 2. Align left

**Steps**
- Tap on the align options located in the toolbar.
- Tap on "Align left".

**Expected Behavior**
- Observe that the preview content is aligned left and only covers part of the block.

### 3. Align center

**Steps**
- Tap on the align options located in the toolbar.
- Tap on "Align center".

**Expected Behavior**
- Observe that the preview content is centered and covers the entire block.

### 4. Align right
- Tap on the align options located in the toolbar.
- Tap on "Align right".

**Expected Behavior**
- Observe that the preview content is aligned right and only covers part of the block.

### 5. Wide width
**Steps**
- Tap on the align options located in the toolbar.
- Tap on "Wide width".

**Expected Behavior**
- Observe that the block's width is wider than the rest of the content and that the preview content covers the entire block.

**NOTE:** Some embed content like Tweets won't cover the entire block because it's not designed for that purpose.

### 6. Full width
**Steps**
- Tap on the align options located in the toolbar.
- Tap on "Full width".

**Expected Behavior**
- Observe that the block's width covers the entire editor and that the preview content covers the entire block.


--------------------------------------------------------------------------------

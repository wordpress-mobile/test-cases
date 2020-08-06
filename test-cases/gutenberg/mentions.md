# User Mentions - Test Cases

## Preconditions
- User mentions are only available on WP.com or Jetpack-connected sites
- User mentions are only available on blocks that permit rich-text formatting

-----------

## Loading The Mentions UI

-----------

##### TC0001

**Mentions UI is triggered using "@" character at the beginning of a block**

**Known Issues**
- **Android:** When deleting all the text in a block, it takes an extra backspace to get the block into a truly "emtpy" state where the "@" character will trigger mentions, see https://github.com/wordpress-mobile/gutenberg-mobile/issues/1524#issuecomment-670155938.

**Steps**
- Type an "@" character at the beginning of a rich-text block
    
**Expected Behavior**
The mentions UI should load.

-----------

##### TC0002

**Mentions UI is triggered using "@" character after whitespace**

**Steps**
- Type an "@" character immediately following whitespace in a rich-text block
    
**Expected Behavior**
The mentions UI should load.
    
-----------

##### TC0003

**Mentions UI is triggered using "@" button on toolbar**

**Steps**
- Tap the "@" button on the format toolbar of a rich-text block (you will probably need to scroll the format toolbar to see the button).
    
**Expected Behavior**
The mentions UI should load.
    
-----------

## Selecting a Mention

-----------

##### Precondition

Each of these tests assume the mentions UI is already open

-----------

##### TC0004

**Tapping on an available mention**

**Steps**
- Tap on an available mention in the mentions UI

**Expected Behavior**
- The mentions UI should close
- The selected mention should be inserted into the block's text
- The cursor should be positioned after the mention with a single whitespace between the mention and the cursor

-----------

##### TC0005

**Typing an available mention**

**Steps**
- Type text in the mentions UI until there **is only a single matching mention**.
- Tap the Enter key

**Expected Behavior**
- The mentions UI should close
- The selected mention should be inserted into the block's text
- The cursor should be positioned after the mention with a single whitespace between the mention and the cursor

-----------

##### TC0006

**Typing text that matches no mentions**

**Steps**
- Type text in the mentions UI until there are **no matching users available**.
- Tap the Enter key

**Expected Behavior**
- The mentions UI should remain open

-----------

## Canceling the Mentions UI

-----------

##### TC0007

**Tapping backspace to cancel the mentions UI**

**Steps**
- Tap backspace when the mentions UI text field is empty (only has a "@")

**Expected Behavior**
- The mentions UI should close
- If the mentions UI was opened by typing an "@" character, an "@" character should have been inserted into the block's text. If the mentions UI was triggered by tapping the "@" button, there should be no change to the block's text.

-----------

##### TC0008

**Tapping the "background" to cancel the mentions UI**

**Steps**
- Type text to filter the mentions UI so the list of users does not fill the entire screen
- Tap on the "background"

**Expected Behavior**
- The mentions UI should close
- If the mentions UI was opened by typing an "@" character, an "@" character should have been inserted into the block's text. If the mentions UI was triggered by tapping the "@" button, there should be no change to the block's text.

# Block Inserter - Test Cases

##### TC0001

**Blocks are sorted properly in the inserter**

**Steps**
1. Open the block inserter

**Expected Behavior**
Core blocks should be listed before non-core blocks in [the order that they are registered](https://github.com/WordPress/gutenberg/blob/trunk/packages/block-library/src/index.native.js).
# Block Inserter - Test Cases

##### TC0001

**Blocks Are Sorted Properly In The Inserter**

**Steps**
1. Open the block inserter

**Expected Behavior**
Core blocks should be listed before non-core blocks in [the order that they are registered](https://github.com/WordPress/gutenberg/blob/trunk/packages/block-library/src/index.native.js#L234-L270).
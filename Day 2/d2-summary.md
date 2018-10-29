## Max/Min Heap 
- A sorted tree s.t. parents node always has greater/smaller key then child nodes.

## The power of balanced Trees
- a balanced tree is key to an efficient search algorithm, and will lead to the fastest runtime.

## (Max)Heap Insertion 
Run time: $ O(log n) $a
1. Add the new key to the last leaf.
2. Compare the node with its parent node
3. If child node is bigger, switch the node with parent node.
4. Otherwise, insertion finished.


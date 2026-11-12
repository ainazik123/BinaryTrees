
Binary Tree Paths

Description
Return all root-to-leaf paths in a binary tree.

Algorithm
1. Start with an empty path.
2. Add the current node value.
3. If the node is a leaf, save the path.
4. Otherwise, recursively visit both subtrees.

Example
Input:[1, 2, 3, null, 5]

Output:["1->2->5", "1->3"]

Complexity
- Time:O(n * h)
- Space:O(n * h)

Where n is the number of nodes and h is the tree height.

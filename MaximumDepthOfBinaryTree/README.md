
Maximum Depth of Binary Tree

Description
Find the maximum depth of a binary tree.

Algorithm
1. If the node is null, return 0.
2. Find the left subtree depth.
3. Find the right subtree depth.
4. Return 1 + the maximum depth.

Example
Input:[3, 9, 20, null, null, 15, 7]

Output:3

Complexity
- Time: O(n)
- Space: O(h)

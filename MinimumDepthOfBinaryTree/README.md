
Minimum Depth of Binary Tree

Description
Find the minimum depth from the root to the nearest leaf.

Algorithm
1. If the node is null, return 0.
2. If the left child is null, calculate the right depth.
3. If the right child is null, calculate the left depth.
4. Otherwise, return 1 + the minimum of both depths.

Example
Input:[3, 9, 20, null, null, 15, 7]

Output:2

Complexity
- Time: O(n)
- Space: O(h)

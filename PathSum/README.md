
Path Sum

Description
Check whether a root-to-leaf path has a given sum.

Algorithm
1. Return false if the node is null.
2. Check if the current node is a leaf.
3. Subtract the current value from targetSum.
4. Recursively check the left and right subtrees.

Example
Input:[5, 4, 8, 11, null, 13, 4, 7, 2, null, null, null, 1]
Target Sum:22

Output:true

Complexity
- Time: O(n)
- Space: O(h)

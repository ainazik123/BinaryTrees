
Merge Two Binary Trees

Description
Merge two binary trees into one tree.

Algorithm
1. If the first node is null, return the second node.
2. If the second node is null, return the first node.
3. Add both node values.
4. Merge the left subtrees.
5. Merge the right subtrees.
6. Return the merged root.

Example
Input:
Root1=[1, 3, 2, 5]
Root2=[2, 1, 3, null, 4, null, 7]

Output:[3, 4, 5, 5, 4, null, 7]

Complexity
- Time:O(min(n, m))
- Space:O(min(h1, h2))

Where n and m are the numbers of nodes,and h1 and h2 are the tree heights.

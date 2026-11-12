
Sum of Left Leaves

Description
Find the sum of all left leaf nodes.

Algorithm
1. Check if the left child exists.
2. If it is a leaf, add its value.
3. Otherwise, search its subtree recursively.
4. Search the right subtree recursively.
5. Return the total sum.

Example
Input:[3, 9, 20, null, null, 15, 7]

Output:24

Complexity
- Time:O(n)
- Space:O(h)

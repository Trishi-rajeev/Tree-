Approach
This code uses a depth-first recursive approach, which means:

It starts at the root.

It recursively goes down to both left and right subtrees.

At each node, it:

Calculates the depth of the left subtree (l)

Calculates the depth of the right subtree (r)

Then it takes 1 + max(l, r) → the +1 is for the current node.

Complexity
Time complexity:
O(N)

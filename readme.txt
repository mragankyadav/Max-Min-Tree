Sample Input and Output to help in understanding its working.
The input format is default lisp format of entering a tree. Please read it in order to understand the tree structure from the given format.
Input:
’((4 (7 9 8) 8) (((3 6 4) 2 6) ((9 2 9) 4 7 (6 4 5))))
Output:
Cut after 7 in subtree (7 9 8)
Cut after 3 in subtree (3 6 4)
Cut after 2 in subtree (9 2 9)
Cut after 7 in subtree ((9 2 9) 4 7 (6 4 5)) Path=[2, 1, 3]
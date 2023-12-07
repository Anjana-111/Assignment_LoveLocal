# Assignment_LoveLocal
1. A binary search tree (BST) is a data structure that organizes elements in a hierarchical structure. Each node in a BST has at most two children: a left child and a right child. The BST has a special property: the value of nodes in the left subtree of a node is less than the value of the node, and the value of nodes in the right subtree is greater than the value of the node.
   Algorithm where the elements are sorted in ascending order converting it into a height balanced binary search tree
   a) Define a function sortedArrayToBST that takes in the sorted array nums.
   b) Find the middle element of the array, which will be the root of the binary search tree.
   c) Create a node for the root, assign the middle element as the value.
   d) Recursively construct the left subtree by calling the sortedArrayToBST function on the left half of the array (elements to the left of the middle element).
   e) Recursively construct the right subtree by calling the sortedArrayToBST function on the right half of the array (elements to the right of the middle element).
   f) Return the root node of the constructed tree.

   
3. for Count digit we use the algorithm as
   while number > 0:
        count += 1
        number //= 10 
    
    return count
2.  Algorithm for counting the total number of digit 1 appearing in all non negative integers less than or equal to n
   a) Initialize a variable count to 0 to keep track of the total count of digit '1'.
   b) Iterate from 1 to n.
   c) Within each iteration, convert the current number to a string to analyze each digit.
   d) For each digit in the string representation of the number, increment the count variable if the digit is '1'.
   e) Finally, return the count variable which holds the total count of the digit '1' in all numbers up to 'n'. 




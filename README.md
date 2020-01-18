# Recursion-practice-C-
Solved 5 tasks using recursion in C++.

The Tasks:
1) Write a recursive function to determine if a non-negative integer has an even number of ones in its binary representation. Return true if it does and false otherwise.

2) Write a recursive function to create and return a new list that is the sum of the values in the two lists passed in. Do not assume that the two lists are the same length. (By a list, I mean a Node*, not an instance of a list class.)

3) Write a recursive function to return the maximum of the values in a binary tree.
We will assume there is no meaningful value for the maximum of an empty tree. You should throw an appropriate exception for C++'s exception hierarchy.

4) Write a recursive function called palindrome. It will be passed an array. Note that when an array is passed to a function, only the address of the first element is passed. So, what your function is really being passed is the starting point of the array and how many characters there are. Of course, to use it you can just pass in the name of the array, as the name is equivalent to its address.
Your recursive calls only need to be passed the address of the portion of the array you want to process and the number of characters.
An example of calling your function might be:
char s[] = "racecar";
if (palindrome(s, 7)) { cout << "Yes!\n"; }
It of course would also return true for "noon".

5) Implement a recursive function to solve the towers of hanoi problem. However, your function should not print anything. Instead it should just return the number of moves needed.

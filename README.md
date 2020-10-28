# Palindrome-Tree

This code is a python realization of a data structure, called Palindrome Tree. For details on what this data structure is, see 
http://adilet.org/blog/palindromic-tree/

An object of the class PalindromeTree is instantiated with a string s as a constructor argument. 

Each node (object of the class PalindromicNode) of the Palindrome Tree corresponds to some palindrome from s. The attribute CurrentLetter of a PalindromeTree identifies the part of s, that has been scanned for palindromes (s[:CurrentLetter] has been scanned). The attribute CurrentNode of a PalindromeTree is the longest palindrome, that is also a suffix of s[:CurrentLetter].

The method addNode of a PalindromeTree increases CurrentLetter by 1, thus modifying CurrentNode, adding new node and constructing links if necessary.
The method printtree of a PalindromeTree prints the tree in the formatted form by calling a recursive method printNode of a class PalindromicNode.




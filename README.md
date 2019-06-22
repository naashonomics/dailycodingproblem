# dailycodingproblem

5/26 [Hard] [Amazon]:

Return a new sorted merged list from K sorted lists, each with size N

For example, if we had [[10, 15, 30], [12, 15, 20], [17, 20, 32]], the result should be [10, 12, 15, 15, 17, 20, 20, 30, 32].

5/27 [Hard][Uber]:

Given an array of integers, return a new array such that each element at index i of the new array is the product of all the numbers in the original array except the one at i.

For example, if our input was [1, 2, 3, 4, 5], the expected output would be [120, 60, 40, 30, 24]. If our input was [3, 2, 1], the expected output would be [2, 3, 6].

Follow-up: what if you can't use division?

5/28 [Medium] [Google]

Given the root to a binary tree, implement serialize(root), which serializes the tree into a string, and deserialize(s), which deserializes the string back into the tree.

For example, given the following Node class

class Node:

def __init__(self, val, left=None, right=None):

  self.val = val
  
  self.left = left
  
  self.right = right

The following test should pass

node = Node('root', Node('left', Node('left.left')), Node('right'))

assert deserialize(serialize(node)).left.left.val == 'left.left'


5/29 [Hard] [Stripe]

Given an array of integers, find the first missing positive integer in linear time and constant space. In other words, find the lowest positive integer that does not exist in the array. The array can contain duplicates and negative numbers as well.

For example, the input [3, 4, -1, 1] should give 2. The input [1, 2, 0] should give 3.

You can modify the input array in-place.

5/31 [Hard] [Google]

An XOR linked list is a more memory efficient doubly linked list. Instead of each node holding next and prev fields, it holds a field named both, which is an XOR of the next node and the previous node. Implement an XOR linked list; it has an add(element) which adds the element to the end, and a get(index) which returns the node at index.

If using a language that has no pointers (such as Python), you can assume you have access to get_pointer and dereference_pointer functions that converts between nodes and memory addresses.


6/1 [medium] [Facebook] : https://github.com/naashonomics/dailycodingproblem/blob/master/6_1_2019_Facebook.ipynb

Given the mapping a = 1, b = 2, ... z = 26, and an encoded message, count the number of ways it can be decoded
.
For example, the message '111' would give 3, since it could be decoded as 'aaa', 'ka', and 'ak'.

You can assume that the messages are decodable. For example, '001' is not allowed.


6/3: [hard] [Airbnb] https://github.com/naashonomics/dailycodingproblem/blob/master/6_3_2019_Airbnb.ipynb

Given a list of integers, write a function that returns the largest sum of non-adjacent numbers. Numbers can be 0 or negative.

Exmaple: For example, [2, 4, 6, 2, 5] should return 13, since we pick 2, 6, and 5. [5, 1, 1, 5] should return 10, since we pick 5 and 5.

Follow-up: Can you do this in O(N) time and constant space?

6/5: [medium] [Twitter]

Implement an autocomplete system. 

That is, given a query string s and a set of all possible query strings, return all strings in the set that have s as a prefix.

For example, given the query string de and the set of strings [dog, deer, deal], return [deer, deal].

Hint: Try preprocessing the dictionary into a more efficient data structure to speed up queries.

6/21 [easy] [Facebook]

This problem was asked by Facebook.

Given a string of round, curly, and square open and closing brackets, return whether the brackets are balanced (well-formed).

For example, given the string "([])[]({})", you should return true.

Given the string "([)]" or "((()", you should return false.



6/12 [hackerrank] [VMware]

Converting Decimal Number lying between 1 to 3999 to Roman Numerals

https://www.geeksforgeeks.org/converting-decimal-number-lying-between-1-to-3999-to-roman-numerals/ 

Print a given matrix in spiral form

https://www.geeksforgeeks.org/print-a-given-matrix-in-spiral-form/

Condense elemnts in a list

User Company wise guide : https://www.ocf.berkeley.edu/~marsy/resources/interviews/CSInterviewQuestions.pdf

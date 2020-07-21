# Good-String
HackerEarth


Question:

A string is called a  string if it has the following properties:
The length of the string is >=2
The first and the last character of the string are identical.
You are given a string S of length N (N >=2) . You have to make it  string using the following operations.
: Remove a letter from the beginning of the string.
: Remove a letter from the end of the string.
You can apply the  or  or both on the string S. Now your task is to find out the minimum number of operations to make the string S a  string.

Input:
The first line of the input will contain T , the number of testcases.
Next line will contain a string of a certain length. The string will consist of only lower case letters from 'a' to 'z'.

Output:
Print the minimum no of operations required. If impossible print "-1", without quotes .

Constraints:

SAMPLE INPUT 

4
abcda
abcdefghiab
pqr
bacdefghipalop

SAMPLE OUTPUT 

0
1
-1
4

Explanation

For 1st test case:
The string is  , we don't need to do any operations as the the string is already satisfying the criteria
For 2nd test case:
Here we have two options either remove the last b and make the string  , or remove the first a and make the original string  , hence we need only 1 operation.
For 3rd test case:
No  string could be made
For 4th test case:
Remove the b from the beginning , and remove p , o , l from the end to make the string  (a  string ) hence total no of operations= .

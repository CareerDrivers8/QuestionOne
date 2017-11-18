# QuestionOne

Fredo and Two Strings <Paysafe>
Fredo has got two strings ss and tt. Playing around with them, he came up with the following question: Will string tt be a subsequence of string ss if he removes substring [si,si+1,....,sj−1,sj][si,si+1,....,sj−1,sj] from string ss ?
Given qq queries, each query consists of indices ii and jj, you have to answer "Yes" if string tt is a subsequence of remaining string ss else answer "No".
Note: Each query is independent of each other.
Input Format:
First line of input consists of string ss. Next line consists of string tt. Next line consists of two integers qq 22 (qq denoting number of queries and second integer always having value 22). Each of following qq lines consists of two integers ii and jj, denoting starting and ending indices of substring to be deleted from string ss.
Output Format: For each query , output "Yes" if t is a subsequence of remaining string ss, else output "No". Answer for each query should come in a new line.
Input Constraints:
1≤|s|≤1051≤|s|≤105 1≤|t|≤|s|1≤|t|≤|s| 1≤q≤1051≤q≤105 1≤i≤j≤|s|1≤i≤j≤|s| Both strings ss and tt contain lowercase English alphabets.

Sample Input
(Plaintext Link)
abcabcxy
ax
2 2
2 6
6 7
Sample Output
(Plaintext Link)
Yes
No
Explanation
Query 1: Remaining string s= "axy", clearly "ax" is a subsequence of this string.
Query 2: Remaining string s="abcaby", clearly "ax" is not a subsequence of this string.

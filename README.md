# Abbreviation
Abbreviation
描述
As we know, we often use a short sequence of characters in place of some words with a very long name. For example, ACM is an abbreviation of “Association for Computing Machinery”. Now we are using an acronymic method to get the abbreviation. An acronym is generated from a long name by capitalizing the first letter of every word in the name and concatenating them together. There is an exception: some words are ignored when generating the abbreviation. These words( case insensitive) meet the following rules:

 1. The common words “and”, “for”, and “the”.

 2. The words with length less than 3, such as “a”, “of”, “to”. Your job is to get the abbreviation of a given string by using the acronymic method.

输入
Input starts with an integer T (T <= 100), denoting the number of test cases. Each case contains a line with several words seperated by space(s). The length of each line is less than 100. And you can assume that there is at least one available word for each case.
输出
For each case, print the abbreviation of the word.
样例输入
5
Online Judge
Association for Computer Machinery
Institute of Electrical and Electronics Engineers
The Lord of the Rings
netease
样例输出
OJ
ACM
IEEE
LR
N

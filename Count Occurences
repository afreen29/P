'''
Problem Name: Count Occurences

You are given a particular string S, which contains only lowercase English alphabets. Your task is to calculate all the occurrences of 
the character and print the character in the order in which it appears in the string S followed by the number of occurrences.
Each character should appear only once in the output.

Input format:
● First line: A single integer T denoting the number of test cases.
● Next T lines: contain string S each.

Output format:
For each test case, print the output in a new line.

Constraints:
1≤T≤1000
1≤|S|≤1000 where S denotes the length of the string.

Sample Testcase:
Input:
1
occurrences
Output:
o1c3u1r2e2n1s1

'''


from collections import Counter
testcases=int(input())
while testcases!=0:
    str1=input()
    str2=Counter(str1)
    list1=[]
    for i in str1:
        if i in str2:
            if i not in list1:
                print(i,str2[i],sep="",end="")
            list1.append(i)
    print(" ")
    testcases-=1

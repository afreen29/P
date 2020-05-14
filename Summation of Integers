'''
Problem Name: Summation of integers

You are given an array A of N integers. Your task is to print the sum of numbers that occurs for an even number of times in the array.

Input format:
● First line: A single integer N denoting the number of integers or elements in the array.
● Second line: N space-separated integers denoting elements of array A.

Output format:
Print a single integer denoting the sum of numbers that appeared for even times in the array.

Constraints:
1 ≤ N ≤ 10^5
1 ≤ Ai ≤ 10^9

Sample Testcase:
Input:
5
1 2 2 3 1
Output:
3
Explanation:
Here the numbers 2 and 1 appear twice. Hence, the answer will be 2+1 = 3.
'''

from collections import Counter
def fun(arr):
    ans=0
    arr.sort()
    n=len(arr)
    count_dict=Counter(arr)
    for i in count_dict:
        k=0
        k=count_dict[i]
        if k%2 ==0:
            l=count_dict[i]
            ans=ans+i
    return ans
n= int(input())
arr = list(map(int,input().split()))
print(fun(arr))

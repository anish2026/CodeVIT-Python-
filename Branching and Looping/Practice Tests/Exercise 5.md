## Exercise 5

Task is to count the number of even number and odd number in given input.First line will take number of inputs.

```python
n=int(input())
s=list(map(int,input().split()))
count=0
for i in range(n):
    if s[i]%2==0:
        count+=1
    
print(count,n-count,end=" ")
```
Input
```
3
1 4 10
```
Output
```
2 1
```

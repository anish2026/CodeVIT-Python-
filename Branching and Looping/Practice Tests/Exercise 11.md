## Exercise 11

Task is to find all the divisors of given input.

```python
n=int(input())
i=1
list=[]
while(i<=n):
    if n%i==0:
        list.append(i)
    i+=1
for x in list:
    print(x,end=" ")
```
Input
```
100
```
Output
```
1 2 5 10 20 25 50 100
```

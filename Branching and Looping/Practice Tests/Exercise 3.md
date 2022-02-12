## Exercise 3

Task is to find the values of series given as 1 - x + x^2 - x^3........x^n , n and x is given.

```python
x=int(input())
n=int(input())
i=0
sum1=0
sum2=0
while(i<=n):
    if i%2==0:
        sum1=sum1 + x**i
    else:
        sum2=sum2 + x**i
    i+=1
print(sum1-sum2)
```
Input
```
3
3
```
Output
```
-20
```

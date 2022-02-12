## Exercise 6

Task is to take two numbers and return their sum if their product is greater than 1000 , otherwise return their sum.

```python
a=int(input())
b=int(input())
def f(a,b):
     
    if a*b > 1000:
         return a+b
    else:
        return a*b
print(f(a,b))
```
Input
```
5
123
```
Output
```
615
```

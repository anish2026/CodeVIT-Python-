## Exercise 4

Task is to check whether the number is pallindrome or not.

```python
n=int(input())
n=str(n)
def f(n):
    rev = ''.join(reversed(n))
    if n==rev:
        return n + " is palindrome"
    else:
        return n + " is not palindrome"
print(f(n))
```
Input
```
1221
```
Output
```
Yes
```

## Exercise 2

Task is to design a calculator with basic operations.

```python
n=list(map(float,input().split()))
ch=input()

if ch=='+':
    print(sum(n))
elif ch=='-':
    print(float(n[0])-float(n[1]))
elif ch=='*':
    print(float(n[0])*float(n[1]))
else:
    print(float(n[0])/float(n[1]))
```
Input
```
20 8
+
```
Output
```
28.0
```

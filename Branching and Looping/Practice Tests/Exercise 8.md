## Exercise 8

Bonanza,double bonanza and no Bonanza problem.

```python
a=list(map(str,input().split()))
b=list(map(str,input().split()))
c=list(map(str,input().split()))



if a[0]==b[0] and b[0]==c[0] and a[1]==b[1] and b[1]==c[1]:
    print("Double Bonanza")

elif (a[0]==b[0] and b[0]==c[0]) or (a[1]==b[1] and b[1]==c[1]):
    print("Bonanza")
    
else:
    print("No Bonanza")
 ```
 Input
 ```
 S 4
 S 4
 S 4
 ```
 Output
 ```
 Double Bonanza
 ```

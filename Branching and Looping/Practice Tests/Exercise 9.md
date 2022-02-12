## Exercise 9

Task is to find that party was successful or not.

```python
s=input()
n=int(input())

if s=='MON' or s=='TUE' or s=='WED' or s=='THU' or s=='FRI' or s=='SAT' or s=='SUN':
    

    if s=='MON' or s=='TUE' or s=='WED' or s=='THU':
        if n>=700 and n<=1000:
            print("Successful")
        else:
            print("Unsuccessful")
    else:
        if n>=1500:
            print("Successful")
        else:
            print("Unsuccessful")
else:
    print("Invalid Input")
```
Input
```
MON
800
```
Output
```
Successful
```

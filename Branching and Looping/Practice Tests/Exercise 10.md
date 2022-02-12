## Exercise 10

Richie and Riya's game problem.

```python
n=list(map(int,input().split()))
temp=0
while(temp<n[2]):
    
    n[0]=2*n[0]
    n[2]=n[2]-1
    if temp>=n[2]:
        break
    else:
        n[1]=2*n[1]
        n[2]=n[2]-1
    
    
print(n[0]+n[1])
```
Input
```
3 2 3
```
Output
```
16
```

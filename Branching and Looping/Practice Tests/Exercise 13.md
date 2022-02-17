### Problem

Given a Indian train seat number, tell who is the co-neighbour of given seat number.
For eg, 1LB --> 4LB
        2MB --> 5MB
        3UB --> 6UB
        7SL --> 8SU
        
```python
seat=int(input())
while(True):
    if seat%8==1:
        print(str(seat+3)+"LB")
        break
    elif seat%8==2:
        print(str(seat+3)+"MB")
        break
    elif seat%8==3:
        print(str(seat+3)+"UB")
        break
    elif seat%8==4:
        print(str(set-3)+"LB")
        break
    elif seat%8==5:
        print(str(seat-3)+"MB")
        break
    elif seat%8==6:
        print(str(seat-3)+"UB")
        break
    elif seat%8==7:
        print(str(seat+1)+"SU")
        break
    elif seat%8==0:
        print(str(seat-1)+"SL")
        break
    

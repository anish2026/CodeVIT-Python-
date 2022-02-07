### Question 1

```python


class Circle:
    def __init__(self,r):
        self.r = r
        
    def area(self,r):
        return (3.14*self.r*self.r)
        
    def perimeter(self,r):
        return (2*3.14*self.r)
 
r = int(input())
obj=Circle(r)
print(obj.area(r))
print(obj.perimeter(r))

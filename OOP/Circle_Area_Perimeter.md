### Question 1

Write a program with class named Circle constructed by a radius methods which will compute the area and the perimeter of a circle. 

*Class Name: Circle*

*Method1: area*

*Method2: perimeter*

Create an object for the class Circle and display the area and perimeter of a circle. 

Note: Use pl = 3.14

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

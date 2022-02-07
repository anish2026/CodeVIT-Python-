### Convert an int into Roman 

Given an integer , convert it into Roman number.

```python 
class intToromanConvertor:
    def _init_(self,n):
        self.n = n
        
    def int_to_Roman(self):
        
        list1 = [1,4,5,9,10,40,50,90,100,400,500,900,1000]
        list2 = ["I","IV","V","IX","X","XL","L","XC","C","CD","D","CM","M"]
        i=12
        
        while self.n:
            div = self.n // list1[i]
            self.n = self.n % list1[i]
            
            while div:
                print(list2[i],end="")
                div -= 1
                
            i -= 1

n=int(input())
obj = intToromanConvertor(n)
obj.int_to_Roman()

### Country code question 

Create a class country with few attributes given and show them with a method inside the country class.

```python
class Country:
    def _init_(self,name,countryCode,isdCode):
        self.name = name
        self.countryCode = countryCode
        self.isdCode = isdCode
        
    def show(self):
        print("Country Name:"+self.name)
        print("Country Code:"+self.countryCode)
        print("ISD Code:"+self.isdCode)

name=input()
countryCode = input()
isdCode = input()

obj=Country(name,countryCode,isdCode)
obj.show()

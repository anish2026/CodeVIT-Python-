### Bank Account

class --> Account

Child class --> AI1 and AI2

Refer codeVIT for full question 


```python
class Account:
    
    def _init_(self,name,no,bank):
        self.name = name
        self.no = no
        self.bank = bank
        
    def display(self):
        
        print("Account Holder Name:"+self.name)
        print("Account Number:"+self.no)
        print("Bank Name:"+self.bank)
        
class AI1(Account):
    
    def _init_(self,name,no,bank,tinNumber):
        super()._init_(name,no,bank)
        self.tinNumber = tinNumber
        
    def display(self):
        super().display()
        print("Tin Number:"+self.tinNumber)
        
class AI2(Account):
    
    def _init_(self,name,no,bank,orgName):
        super()._init_(name,no,bank)
        self.orgName = orgName
        
    def display(self):
        super().display()
        print("Organization Name:"+self.orgName)
        
name=input()
no=input()
bank=input()
tinNumber=input()
orgName=input()
select=input()

obj = Account(name,no,bank)
obj1 = AI1(name,no,bank,tinNumber)
obj2 = AI2(name,no,bank,orgName)

if select == "1":
     obj.display()
     
elif select == "2":
     obj1.display()
     
else :
     obj2.display()

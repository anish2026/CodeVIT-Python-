### Reverse words 

Reverse the word of given string , for example , s= coder good a is Anish then output should Anish is a good coder.

```python
class python_string:
    
    def _init_(self,s):
        self.s = s
        
    def reverse_words(self):
        words = self.s.split(' ')
        print(' '.join(reversed(words)))

s=input()
obj=python_string(s)
obj.reverse_words()

# Palindrome Checker 🔁  

This repository contains a simple script that checks if a word or phrase is a palindrome (reads the same forward and backward).  

## Code in This Repo  
```python
text = input("Enter a word or phrase: ").replace(" ", "").lower()  
if text == text[::-1]:  
    print("It's a palindrome! 🎉")  
else:  
    print("Not a palindrome. ❌")  

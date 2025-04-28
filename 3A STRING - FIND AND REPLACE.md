# Exp.No:3a
## STRING - FIND SEQUENCES OF LOWERCASE LETTERS JOINED WITH '@'

---

### AIM  
To write a Python function to find sequences of lowercase letters that are joined with a '@'.


---

### ALGORITHM

1.Begin the program.
2.Input the string text to search for lowercase sequences joined by '@'.
3.Use regular expressions (re) to find all occurrences of lowercase letters followed by '@' and more lowercase letters.
4.Display all matched sequences found in the string.
5.Terminate the program.

---

### PROGRAM
Reg no: 212223020021
Name: Ranjith P
```
import re
a=input()
b='[a-z]+@'
if re.search(b,a):
    print('Found a match!')
else:
    print('Not matched!')
```

### OUTPUT
![Screenshot 2025-04-28 161241](https://github.com/user-attachments/assets/6c7df35e-1e9f-4e86-a6b5-71fde4a3fa85)


### RESULT
The program finds and displays all sequences of lowercase letters joined with '@' from the input string.



# Exp.No:3b  
## REGEX - PATTERN MATCHING USING REGEX

---

### AIM  
To write a Python program that finds sequences of one uppercase letter followed by a number.

---

### ALGORITHM

1.Begin the program.
2.Accept a string str1 from the user.
3.Define the regular expression pattern as r"[A-Z]\d", which matches one uppercase letter followed by a digit.
4.Use the re.findall() function to find all sequences in the string that match the pattern.
5.If sequences are found, print them.
6.If no sequences are found, print "No match found!".
7.Terminate the program.


---

### PROGRAM
Reg no: 212223020021
Name: Ranjith P
```
import re
a=input()
x=re.search('[A-Z]+[0-9]',a)
if x:
    print('Found a match!')
else:
    print('Not matched!')
```
### OUTPUT
![Screenshot 2025-04-28 181359](https://github.com/user-attachments/assets/27b46fe6-a495-4d07-a06e-69ef92dd0332)


### RESULT
The program finds and displays all sequences of one uppercase letter followed by a number from the input string.


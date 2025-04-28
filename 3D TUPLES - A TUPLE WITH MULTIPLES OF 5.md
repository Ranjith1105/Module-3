# Exp.No:3d  
## TUPLES - String in a tuple

---

### AIM  
To write a Python program that prints the minimum and maximum value of characters in a string in a tuple, based on their ASCII values

---

### ALGORITHM

1.Begin the program.
2.Accept a string input from the user.
3.Find the character with the minimum ASCII value using the min() function.
4.Find the character with the maximum ASCII value using the max() function.
5.Create a tuple with the minimum and maximum characters.
6.Print the tuple.
7.End the program.


---

### PROGRAM
Reg No: 212223020021
Name: Ranjith P

```
def min_max(t):
    sort=sorted(t)
    return(sort[0],sort[-1])
n=int(input())    
t=()
for i in range(n):
    t=t+(input(),)
print(t)    
min_a,max_a= min_max(t)
print("Minimum:",min_a)
print("Maximum:",max_a)
```

### OUTPUT
![Screenshot 2025-04-28 182348](https://github.com/user-attachments/assets/001306a2-a5e3-4831-a74a-c49cb74b2e28)


### RESULT
The program finds and prints a tuple containing the character with the minimum ASCII value and the character with the maximum ASCII value from the input string

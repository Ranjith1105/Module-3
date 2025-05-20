# Exp.No:3c
## LIST - Sum of all the values

---

### AIM  
To write a Python program that displays the sum of all the values that end with the digit 2 from a list.

---

### ALGORITHM

1.Begin the program.

2.Define a list of numbers.

3.Loop through each number in the list.

4.Check if the number ends with the digit 2 (i.e., number % 10 == 2).

5.If it ends with 2, add it to the sum.

6.Display the sum.

7.End the program.


---

### PROGRAM
Reg no: 212223020021
Name: Ranjith P
```
def sum_values(lst):
    sum=0
    for num in lst:
        if num%10==2:
            sum+=num
    print("Sum=",sum)        
numbers=eval(input())    
sum_values(numbers)
```

### OUTPUT
![Screenshot 2025-04-28 181941](https://github.com/user-attachments/assets/95101f95-3b24-445d-b7bc-59f3e8c95d74)

### RESULT
The program calculates and displays the sum of all numbers that end with the digit 2 from the given list.




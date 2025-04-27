# Exp.No:2b  
## FUNCTIONS - FACTORIAL NUMBER

### AIM  
To write a Python program to define a function that returns factorial of a number.
### ALGORITHM
1. Begins the program.
2. Import the math module.
3. Define a function factorial(num) that:
     Returns math.factorial(num).
4. Input an integer num from the user.
5. Call the factorial function with num and store the result in a variable tot.
6. Print the result tot with a message "Factorial is".
7. Terminal the program.
### PROGRAM
```
def factorial(num):
    fact = 1
    while(num!=0):
        fact *= num
        num = num - 1
    print("Factorial is",fact)

num = int(input())
factorial(num)

```
### OUTPUT
![Screenshot 2025-04-27 133938](https://github.com/user-attachments/assets/16c4f23e-c43e-47f9-9770-0785523af93b)
### RESULT
Thus the program program to define function that returns factorial of a number heas been implemented and executed successfully.

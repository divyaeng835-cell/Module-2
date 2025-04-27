# Exp.No:2d
## LOOPING PATTERNS - PRINTING PATTERN
### AIM  
To write a Python program to print the downward pyramid pattern of stars
### ALGORITHM

1. Begin the program.  
2. Input an integer n (number of rows). 
3. Loop from i= n down to 1 (decreasing by 1 each time):  
   - Print i stars(*),all in the same line.  
4. Terminate the program.

### PROGRAM
```
rows = int(input())
for i in range(rows + 1, 0, -1):
    for j in range(0, i - 1):
        print("*", end=' ')
    print(" ")

```
### OUTPUT
![Screenshot 2025-04-27 144758](https://github.com/user-attachments/assets/256a387a-0829-4a8c-a041-b48bd6b4a131)
### RESULT
Thus the python program for printing the downward pyramid pattern of stars has been implemented and executed successfully.

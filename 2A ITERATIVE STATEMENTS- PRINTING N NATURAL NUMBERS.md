# Exp. No: 2a  
## ITERATIVE STATEMENTS – PRINT 1 TO N ODD NUMBERS IN REVERSE ORDER

###  Aim
To create a Python program for printing 1 to n Odd numbers in reverse order.
###  Algorithm

1. Begin the program.
2. Input an interger n.
3. Loop from i = n down to 1 (decreasing by 1 each time):
           if i is odd (i.e., i%2!=0
4. Print i
5. Terminate the program.

---

###  Program

```python
n=int(input())

for i in range(n,0,-1):
    if i%2!=0:
        print(i)
```
### OUTPUT
![Screenshot 2025-04-27 132617](https://github.com/user-attachments/assets/732cbc1a-c56e-4ac4-8e1e-55d08249d8a2)
### RESULT
Thus the python program to print 1 to n odd numbers in reverse order has been implemented and executed successfully.


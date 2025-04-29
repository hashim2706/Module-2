# Exp.No:2e  
## SEB - SUM OF THE SERIES

---

### AIM  
Python Program to find the sum of series 1+3+5+7.......+N 

---

### ALGORITHM

1. **Start** the program.
2. **Input** the value of `N` from the user.
3. **Initialize** a variable `sum = 0`.
4. **Loop** from `i = 1` to `N`, incrementing by 2 (to get only odd numbers).
   - On each iteration, **add `i` to `sum`**.
5. **After the loop**, print the value of `sum`.
6. **End** the program.

---

### PROGRAM

```
n=int(input())
sum=0
for i in range(1,n+1,2):
    sum=sum+i
print("The sum of the series = ",sum)
```
### OUTPUT

![Screenshot (193)](https://github.com/user-attachments/assets/9795d6ac-9a86-40da-ad22-0a33bce3ddc3)

### RESULT
Thus,the program to find the sum of series 1+3+5+7.......+N was implemented and executed successfully.

# Exp.No:2d
## LOOPING PATTERNS - PRINTING PATTERN

---

### AIM  
Write a python program  to print the downward pyramid pattern of stars

---

### ALGORITHM

1. **Start** the program.
2. **Input** the number of rows for the pyramid (say `n`).
3. **Loop** from `i = n` down to `1`:
   - Print `(n - i)` spaces to center the stars.
   - Print `(2 * i - 1)` stars on the current row.
4. **Repeat** until all rows are printed.
5. **End** the program.


---

### PROGRAM
```
n=int(input())
for i in range (1,n+1,1):
    for j in range (i,n+1,1):
        print(end="* ")
    print(end="\n")
    

```

### OUTPUT

![Screenshot (192)](https://github.com/user-attachments/assets/b5a69f65-934d-494f-aff4-85f24f38c9c5)

### RESULT
Thus,the program to print the downward pyramid pattern of stars was implemented and executed successfully.

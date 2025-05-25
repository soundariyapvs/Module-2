# Experiment No: 2d Inverted Pyramid Pattern of Numbers

## AIM  
To write a Python program to print an inverted pyramid pattern of numbers based on user input.

---

### ALGORITHM  
1. Begin the program.
2. Use `input()` to read the number of rows, `a`, from the user.
3. Convert the input to an integer.
4. Initialize a variable `num` to 1 for the first number to print.
5. Use a nested `for` loop:
   - The outer loop runs from `1` to `a`.
   - The inner loop prints the current number `num` repeatedly, with the number of repetitions decreasing each row.
6. Increment `num` after each row.
7. Print a newline after each row.
8. Terminate the program.

---

### 🧾 PROGRAM

```python
a = int(input())

num = 1
for i in range(1, a + 1):
    for j in range(i, a + 1):
        print(num, end=" ")
    num += 1
    print("")

```

### OUTPUT
![image](https://github.com/user-attachments/assets/fbe84cf0-0cae-4713-ae7c-a4056a477812)

### RESULT
Thus, the Python program to print an inverted pyramid pattern of numbers has been implemented and executed successfully.

# Experiment No: 2e – SEB-Mean Value Calculation

## AIM  
To write a Python program to define a function that accepts 3 values and returns their mean value.

---

### ALGORITHM  
1. Begin the program.  
2. Define a function `result(a, b, c)` that accepts three numbers as arguments.
3. Inside the function:
   - Calculate the sum of `a`, `b`, and `c`.
   - Compute the mean by dividing the sum by 3.
   - Return the calculated mean value.
4. Use `input()` to read three numbers from the user.
5. Convert the inputs to integers.
6. Call the `result()` function with the three numbers as arguments and display the returned mean value.
7. Terminate the program.

---

### 🧾 PROGRAM

```python
def result(a, b, c):
    sum = a + b + c
    mean = sum / 3
    return mean

a = int(input())
b = int(input())
c = int(input())

print(f"mean is {result(a, b, c)}")

```
### OUTPUT
![image](https://github.com/user-attachments/assets/f4f2b95a-dde8-41bf-999d-ffa9b0db735f)

### RESULT
Thus, the Python program to define a function that accepts 3 values and returns their mean value has been implemented and executed successfully.

# Experiment No: 2b Strong Number Check

## AIM  
To write a Python program to check if a number is a strong number using a function.

---

### ALGORITHM  
1. Begin the program.  
2. Define a function `strong(num)` to check if the given number is a strong number.
3. Inside the function:
   - Initialize a variable `sum1` to store the sum of the factorials of digits.
   - Copy the input number to a temporary variable `temp`.
   - Extract each digit of the number.
   - For each digit, calculate the factorial and add it to `sum1`.
4. Compare `sum1` with `temp`. If they are equal, the number is a strong number.
5. If the number is a strong number, print **"The number is a strong number"**. Otherwise, print **"The number is not a strong number"**.
6. Terminate the program.

---

### 🧾 PROGRAM

```python
def strong(num):
    sum1 = 0
    temp = num
    while(num):
        i = 1
        f = 1
        r = num % 10
        while(i <= r):
            f = f * i
            i = i + 1
        sum1 = sum1 + f
        num = num // 10
    if(sum1 == temp):
        print("The number is a strong number")
    else:
        print("The number is not a strong number")
    
n = int(input())
strong(n)
```

## OUTPUT
![image](https://github.com/user-attachments/assets/0b428a0c-cb1c-424e-a495-f98e8dfc8968)

## RESULT
Thus, the Python program to check if a number is a strong number using a function has been implemented and executed successfully.

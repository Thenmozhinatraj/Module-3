# Exp.No:3d  
## TUPLES - A TUPLE WITH MULTIPLES OF 5

---

### AIM  
To write a Python program to create a tuple containing all multiples of 5 up to a given number **N**.

---

### ALGORITHM

1. Begin the program.  
2. Accept an integer `N` from the user.  
3. Use a generator expression inside the `tuple()` function to create a tuple `multiples_of_5` with values starting from `5` up to `N - 1`, stepping by `5`.  
4. Return the tuple `multiples_of_5`.  
5. Print the resulting tuple.  
6. Terminate the program.

---

### PROGRAM

```python
N = int(input("Enter an integer: "))
mul_of_5 = tuple(i for i in range(5, N, 5))
print(mul_of_5)
```

### OUTPUT
![Screenshot 2025-05-01 130258](https://github.com/user-attachments/assets/bf0931d0-a9cd-4b52-88df-deb6fb6fb543)

### RESULT
Thus, The program executed successfully, and the output is verified.

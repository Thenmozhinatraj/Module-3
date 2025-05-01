# Exp.No:3e
## SEB - STRING SLICING

---

### AIM  
To write a Python function that accepts a string and forms a new string by reversing the characters from the **4th position to the 10th position** with **alternate characters**, and then prints the new string.

---

### ALGORITHM

1. Begin the program.  
2. Accept a string as input.  
3. Take a slice of the input string from index **2** to **10** (Python uses 0-based indexing, so index 2 refers to the 3rd character, i.e., the 4th character in natural terms).  
4. Reverse the sliced substring.  
5. Extract every second character from the reversed substring using slicing (`[::2]`).  
6. Print the final processed string.  
7. Terminate the program.

---

### PROGRAM

```python
input_string = input("Enter a string: ")
sliced_string = input_string[2:10]
reversed_string = sliced_string[::-1]
processed_string = reversed_string[::2]
print(processed_string)
```

### OUTPUT
![Screenshot 2025-05-01 130758](https://github.com/user-attachments/assets/5e929ba9-4160-4d71-9f6a-a80ba6173cef)
### RESULT
Thus, the program executed successfully and the output is verified.

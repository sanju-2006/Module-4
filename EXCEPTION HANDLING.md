# Exp.No:17  
## EXCEPTION HANDLING

---

### AIM  
write a python program for solving following error using exception handling. Accept two variables a and b eg. a value 5 and b value  hello. 

---

### ALGORITHM

1. Begin the program.  
2. Read a string `input_str` from the user using `input()`.  
3. Split the input string using commas (`,`) to create a list of grades.  
4. Use a `try` block to attempt converting each item in the grades list to an integer and store the result in `l1`.  
5. If the conversion is successful, print the list `l1` containing the integer values.  
6. If an error occurs during conversion (for example, if the input is not a valid number), catch the exception and print an error message: `"The grades you entered were in an invalid format."` along with the original grades list.  
7. Terminate the program.

---

### PROGRAM

```
try:
    a=eval(input())
    b=eval(input())
    print(a+b)
except:
    print("cannot add integer with string")

```

### OUTPUT

cannot add integer with string

### RESULT

<img width="742" height="293" alt="image" src="https://github.com/user-attachments/assets/e3e9dd51-e8be-4ee0-bb07-0d7efb77309c" />

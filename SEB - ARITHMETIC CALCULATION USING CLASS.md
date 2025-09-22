# Exp.No:20  
## SEB - ARITHMETIC CALCULATION USING CLASS

---

### AIM  
write a python program to perform modulo and floor division operation using class and if,elif..

note:

class name should be SEC, function name should be setvalues( to se the values of a and b) ,rem and div

case : choice 1 ->perform modulo operation ,choice 2-> perform division ,  choice 0 -> exiting, other choices -> print 'invalid choice'

---

### ALGORITHM

1. Begin the program.  
2. Create a class `Saveetha`.  
3. Define the following methods inside the `Saveetha` class:  
   - `__init__(self)`: Initializes `a` and `b` to zero.  
   - `setvalues(self, a, b)`: Sets the values of `a` and `b`.  
   - `add(self)`: Performs the addition operation.  
   - `div(self)`: Performs the division operation. If `b` is zero, returns an error message for division by zero.  
4. Create a `main()` function.  
5. Take input from the user for the values of `a` and `b` using `setvalues(a, b)` method.  
6. Use a `while True` loop to repeatedly ask the user for a choice:  
   - If the choice is 1, call the `add()` method and print the result.  
   - If the choice is 2, call the `div()` method and print the result. Handle division by zero.  
   - If the choice is 0, print "Exiting!" and exit the loop.  
   - If the choice is not 1, 2, or 0, print "Invalid choice".  
7. Terminate the program.

---

### PROGRAM

```

class sec:
    def __init__(self,a,b):
        self.a=a
        self.b=b
        c=1
        while c!=0:
            c=int(input())
            if c==1:
                print("Result: ",a%b)
            elif c==2:
                print("Result: ",int(a/b))
            elif c==0:
                print("Exiting!")
            else:
                print("Invalid Choice")
                
                
a=int(input())
b=int(input())
obj=sec(a,b)

```

### OUTPUT

Result:  0
Exiting!

### RESULT

<img width="410" height="339" alt="image" src="https://github.com/user-attachments/assets/6df4b16b-4896-4cf8-9864-72b755c615e4" />

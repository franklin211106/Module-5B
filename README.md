 # NUMPY AND PANDAS 
 # AIM:
 To write a python program to add the give series.
 # ALGORITHM:
 1)Start

2)Import the pandas library as pd.

3)Read the first list of numbers from the user:

   Use input() to accept a string representing a Python list (e.g., [1, 2, 3])

   Use eval() to convert the string into a Python list.

4)Create a Pandas Series a1 from the list.

   Read the second list of numbers from the user:

   Use input() and eval() similarly to step 3.

5)Create a second Pandas Series a2.

6)Add the two Series element-wise:

  Use a1 + a2 and store the result in a variable addition.

7)Print the message: "Addition of two Series:"

8)Print the resulting Series addition.

9)End

# PROGRAM:
```
import pandas as pd
a1 = pd.Series(eval(input()))
a2 = pd.Series(eval(input()))
addition=a1+a2
print("Addition of two Series:")
print(addition)
```
# OUTPUT:
![image](https://github.com/user-attachments/assets/5bc934e4-38b4-44d6-9dc5-15f322043cd2)
![image](https://github.com/user-attachments/assets/735bf5c9-0402-4ccd-844e-be6b73b8b25d)

# RESULT:
Thus expected output is acheived.



 


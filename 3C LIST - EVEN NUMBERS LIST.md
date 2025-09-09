# Exp.No:3c LIST - EVEN NUMBERS LIST
# AIM
To write a Python function that creates a list of even numbers from 12 to n and prints the list and its sum.

# ALGORITHM
Start the program. Define a function named createlist that accepts a single parameter n. Initialize an empty list l. Iterate from 12 to n-1 using a for loop: For each number i in the range: Check if i is even using the condition i % 2 == 0. If the condition is true, append i to the list l. After the loop ends, print the list using print("List =", l). Calculate the sum of the list using sum(l) and print the result. End the function. Terminate the program.

# PROGRAM
~~~
# 212222060245-Singamala Rakshitha


def createlist(n):
    l=[]
    for i in range(12,n):
        if i%2==0:
            l.append(i)
    print("List =",l)
    print("Sum of the list",sum(l))
~~~
# OUTPUT
<img width="1256" height="312" alt="image" src="https://github.com/user-attachments/assets/56a8bf04-c607-4adc-81b7-ba5b1187a145" />

# RESULT
Thus the program that creates a list of even numbers from 12 to n and prints the list and its sum has been implemented and executed successfully.

# Exp.No:3d TUPLES - A TUPLE WITH MULTIPLES OF 3
# AIM
To create a tuple of multiples of 3 up to N and print the tuple and its length.

# ALGORITHM
Start the program. Accept input from the user for the value of N. Initialize an empty list a. Loop from 1 to N - 1: For each number i, check if it is divisible by 3 using i % 3 == 0. If true, append i to the list a. Convert the list a into a tuple b. Print the tuple b. Print the length of the tuple using len(b). End the program.

# PROGRAM
~~~
# 212222060245-Singamala Rakshitha


n=int(input())
a=[]
sum=0
for i in range(3,n):
    if(i%3==0):
        a.append(i)
        sum+=i
b=tuple(a)
print(b)
print(f"Sum is",sum)
~~~
# OUTPUT
<img width="1187" height="354" alt="image" src="https://github.com/user-attachments/assets/7d98a703-1c6e-4c4d-8fae-a177b34d1251" />

# RESULT
Thus the program to create a tuple of multiples of 9 up to N and print the tuple and its length has been implemented and executed successfully.

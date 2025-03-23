# Conditional-statements-in-py
#Quize.py

answer = input("When was the first known use of the word 'quiz'? ")
if answer=='1781':
    print('Correct!')
else:
    print('Wrong answer, the correct answer is 1781')

answer = input("Which built-in function can get information from the user? ")
if answer=="input":
    print('Correct!')
else:
    print('Wrong answer, the correct answer is input')

#new work
CP = int(input("Enter the CP : "))
SP = int(input("Enter the SP : "))
if(SP>CP):
    print("Profit!")
    Profit = SP-CP
    print(Profit)
else:
    print("No Profit!")

#new work
#if else masti
n = int(input("Enter the number : "))
if(n%2==0):
    print("The Number is Even!")
else:
    print("The Number is Odd!")

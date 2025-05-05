# ASSENMENT-3


#it gives factorial value of a number 
#factorial
n=int(input('enter a number:'))
def factorial(n):
    if n<2:
        return 1
    else:
        return n*(factorial(n-1))
result=factorial(n)
print("The factorial of",n,"is",result)


#it gives square root , log and sin value of a number
n=int(input("Enter the number:"))

from math import sqrt , log , sin
print("sqrt:",sqrt(n))
print("log:",log(n))
print("sin:",sin(n))


# Developing-calculator-
def add(a, b):
     return a+b
def subtract (a, b):
     return a-b
def multiply(a, b):
     return a*b
def divide(a, b):
     return a/b

n = (''' 1) adding
2) Subtract
3) Multiply
4) Divide ''')

Select = int(input("Select an option: ")

a = int(input("Enter first number:")
b = int(input("Enter second number:")
if select == 1:
   print("Addition: ",add(a, b))
elif select == 2:
   print("Subtraction:",subtract(a, b))
elif select == 3:
   print("Multiplication:",multiply(a,b))
elif select == 4:
   print(" Division:",divide(a,b)
else:
   print(" Invalid input")

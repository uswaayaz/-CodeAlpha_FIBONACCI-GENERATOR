# -CodeAlpha_FIBONACCI-GENERATOR
"""fibonacci series is [0 1 1 2 3 5 8 13 21 34 55 89 144 233 377.........]
where F0=0 and F1=1
Fn=Fn-1 + Fn-2"""

def fib_recursion(n):
 if (n==0):
   return 0
 elif (n==1):
  return 1
 else:
     return fib_recursion(n-1) + fib_recursion(n-2)
number = int(input("enter the positive number:"))
print(f" using recursive function the value of fib({number}) is:{fib_recursion(number)}")


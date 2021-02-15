# fib_series
Fibonacci series in python
#Fibonacci series 

n = int(input("enter no. of terms "))

n1= 0
n2=1
i = 0


if n<= 0:
   print("Please enter a positive integer")
elif n== 1:
   print("Fibonacci sequence upto",n,":")
   print(n1)
else:
   print("Fibonacci sequence:")
   while i< n:
       print(n1)
       nth = n1 + n2
       n1 = n2
       n2 = nth
       i += 1

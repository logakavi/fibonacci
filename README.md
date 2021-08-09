# fibonacci
Write a code to generate a series of 100 Fibonacci numbers with first two numbers as 3 and 4. It should be 3,4,7,11,18,.... 
n=int(input("Enter the nth value:"))
n1=1
n2=3
while n2<=n:
    print(n2)
    n3=n2
    n2+=n1
    n1=n3
   

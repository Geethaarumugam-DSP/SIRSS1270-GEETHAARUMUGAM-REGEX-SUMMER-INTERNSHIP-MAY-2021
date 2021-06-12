# SIRSS1270-GEETHAARUMUGAM-REGEX-SUMMER-INTERNSHIP-MAY-2021
Assignment 3- Functions
# Summer Training/Internship Program May 2021- MACHINE LEARNING & DEEP LEARNING

Registration Id: SIRSS1270

Name: Geethaarumugam

Assignment 3



# Q1. Write a function to return nth term of Fibonacci sequence.

def Fibonacci(x):
    fib = 1
    seq = 0
    if x<= 2:
        return 1
    for i in range(2, x):
        value = fib + seq
        fib = seq
        seq = value
    return value

num = input("enter value of x - ")
print("nth term Fibonacci is" , Fibonacci(int(num)))

# Q2. Write a function to find out GCD of two numbers using EUCLID'S algorithm.

def GCD(n, n1):
    if n1 == 0:
        return n
    else :
        return GCD(n1, n // n1)
inp = int(input('Enter First Number:'))
inp1 = int(input(" Enter Second Number:"))
print("GCD of", inp, "and", inp1, "is", GCD(inp, inp1))

    

# Q3. Write a function to find LCM of two number in most optimizers way.


def LCM(a,b):
    return(a / GCD(a,b))*b
a = 15
b = 25
c = 40
print('LCM of', a, 'and', b, 'is', LCM(a,b))

# THANK YOU


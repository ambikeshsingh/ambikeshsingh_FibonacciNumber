# ambikeshsingh_FibonacciNumber
Fibonacci Function 
Type any number to get fibonacci number
***************************************************


def fibonacci(n):

    if 0<=n<=1:
        return n

    num,num1=1,0
    result=None
    for i in range(n-1):
        result=num1+num
        num1=num
        num=result
    
    return result


n=int(input("Enter any number : "))
for j in range(n):
    print(j,fibonacci(j))



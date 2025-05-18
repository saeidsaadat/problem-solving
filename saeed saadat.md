
def rev (x):
    if len(x) ==0:
        return x
    else :
        return rev (x[1:])+x[0]
rev ("amin")

def fib (x):
    if x==1:
        return 0
    elif x==0:
        return 1
    else:
        return fib(x-1) + fib(x-2)
fib(7)

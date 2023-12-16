#scope

def f1():
    global x 
    x = x + 1 
    return x
def f2():
    return x+1 
def f3():
    x = 5 
    return x+1

x = 0 
print (f1())
print (f2())
print (f3())

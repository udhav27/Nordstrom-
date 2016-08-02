# Nordstrom-
l=[]
for i in range(2000, 3201):
    if (i%7==0) and (i%5!=0):
        l.append(str(i))
        
        def fact(x):
    if x == 0:
        return 1
    return x * fact(x - 1)

x=int(raw_input())
print fact(x)

n=int(raw_input())
d=dict()
for i in range(1,n+1):
    d[i]=i*i
values=raw_input()
l=values.split(",")
t=tuple(l)
print l
print t
class InputOutString(object):
    def __init__(self):
        self.s = ""

    def getString(self):
        self.s = raw_input()

    def printString(self):
        print self.s.upper()

strObj = InputOutString()
strObj.getString()
strObj.printString()

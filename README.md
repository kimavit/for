Cycle "for".
=============
for and math 
------------
````````````ruby
n = int(input())
for i in range(n+1):
    print("Квадрат числа", i, "равен", pow(i, 2))
``````````````````
````````````ruby
a = int(input())
for i in range (a):
    print ((a-i)*"*")
``````````````````
````````````ruby
m = int(input())
p = int(input())
n = int(input())
for i in range (n):
    print(i+1, (m*(p/100+1)**i))
``````````````````
Cycle for + if
--------------
``````````````ruby
m = int(input())
n = int(input())
if m <= n :
    for i in range(m,n+1):
        print(i)
else:
    for i in range (m,n-1,-1):
        print (i)
``````````````````

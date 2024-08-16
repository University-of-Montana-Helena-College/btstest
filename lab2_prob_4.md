Integer or Floor Divison
=
Use // operator to do integer divison.  With integer division the remainder is thrown away.  

So for example:

5 // 4 would result in 1 because 4 goes into 5 one time
10 // 4 would result in 2 because 4 goes into 10 two times

example:
```
num1 = 5
num2 = 4
num3 = num1 // num2
print(num3)    # this would print 1
```
Regular or Float Divison
=
Use / operator to do regular divison you have used for years.

So for example:

5 / 4 would result in 1.25 because 4 goes into 5 1.25 times when including remainder
10 / 4 would result in 2.5 because 4 goes into 10 2.5 times when including remainder

example:
```
num1 = 5
num2 = 4
num3 = num1 / num2
print(num3)    # this would print 1.25
```
Order of Operations
=
Use calculation enclosed in parenthesis to make that operation happen before the others.  This works just like parenthesis in math class.
example:
```
num1 = 6
num2 = 4
num3 = 2
num4 = (num1 - num2) * num3   
print(num4)    # this would print 4 because 6 minus 4  then times 2 is 4

num5 = num1 - num2 * num3   
print(num5)    # this would print -2 because 6 minus the result of 4 times 2 is -2

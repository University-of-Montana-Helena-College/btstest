Multiple operations on one line
=
You can do many operations on one line.  Be carful not to overdo it.  Good code is readable code.
example:
```
num1 = 6
num2 = 2
num3 = 8
num4 = num1 * num2 + num3
print(num4)     # would print 20 
```

You could break the operations down to seperate lines
example:
num1 = 6
```
num2 = 2
num3 = 8
num4 = num1 * num2 
num5 = num4 + num3
print(num5)     # would still print 20 
```

Compound Operators
=
You can use +=  to add to variable.
example:
```
num1 = 6
num2 = 2
num2 += num1       # same as num2 = num2 + num1
print(num2)     # would print 8, the current value of num2 plus 6 (from num1)
```

You can use -=  to subtract from variable.
example:
```
num1 = 6
num2 = 2
num2 -= num1       # same as num2 = num2 - num1
print(num2)     # would print -4, the current value of num2 minus 6 (from num1)
```

You can use *=  to multiply a variable.
example:
```
num1 = 6
num2 = 2
num2 *= num1       # same as num2 = num2 * num1
print(num2)     # would print 12, the current value of num2 times 6 (from num1)
```

Here are some other common compound operators that work the same way:

/=    regular divison
//=   integer or floor division
%=    Mod or Modulus operation
 


Convert string to float or floating point or real number
=
Use float function to convert to a real number.
example:
```
print("Enter Real Number: ")
string_variable = input()
my_float_variable = float(string_variable)
```

Another way:
You can do all of this on one line if you like:
```
my_float_variable = float(input("Enter Real Number: "))
```

Addition
=
Use + operator to add numbers together. example:
```
num1 = 5
num2 = 3
num3 = num1 + num2
```
Subtraction
=
Use - operator to add numbers together. example:
```
num1 = 5
num2 = 3
num3 = num1 - num2
```
Multiplication
=
Use * operator to multiply numbers together. example:
```
num1 = 5
num2 = 3
num3 = num1 * num2
```
Output literal string and number (int or float) variable
=
Use the str function to convert a number to a string.  Use concatination to put strings together.
output for all options below will be: 

My Cat hase 6 lives remaining.

example:
```
lives = 6
print("My cat has " + str(lives) + " remaining.")
```
Another way:
Use , (comma) with print function to put results together, it adds a space.

example:
```
lives = 6
print("My cat has", lives, "remaining.")
```

Another way:
Use f string feature, put f in front of string then use variables inside string enclosed in curly braces {}.

example:
```
lives = 6
print(f"My cat has {lives} remaining.")
```
# python
Notes 
Vocab:
Strings in python are surrounded by either single quotation marks, or double quotation marks.
Example String With Variable:
a = "Hello"
print(a)

Integer: x = 1
y = 35656222554887711
z = -3255522

print(type(x))
print(type(y))
print(type(z))

The float() method returns a floating point number from a number or a string.
Example:
# for integers
print(float(10))

# for floats
print(float(11.22))

# for string floats
print(float("-13.33"))

# for string floats with whitespaces
print(float("     -24.45\n"))

Example:
x = 1.10
y = 1.0
z = -35.59

print(type(x))
print(type(y))
print(type(z))

-------------------------------------------------------------------------------------------------------------


Functions:

How to comment Function:
Arguments:
Return:
Assumptions: 

def my_function(fname):
  print(fname + " Refsnes")

my_function("Emil")
my_function("Tobias")
my_function("Linus")****

A fucntion is a block of code that runs when it is called. You can pass data that is knows as paramters, into a function.
Functions return data as a result.

Basic Example:
def my_function():
  print("Hello from a function")
  
  caliing a function example: 

def my_function():
  print("Hello from a function")

my_function()

Example Argument function:

def my_function(fname):
  print(fname + " Refsnes")

my_function("Emil")
my_function("Tobias")
my_function("Linus")

Practice Problem Example:

# Read an integer:
number = int(input('Enter a 3 digit number: '))

# Print the sum of the digits:
# print(a)



a = number // 100

b = number // 10 % 10

c = number % 10

print(a + b + c)

-----------------------------------------------------------------------------------------------

Lists: Value That Contains Multiple Values in ordered sequence. Used to sotre multiple items in a single variable. square brakets []


Example: 

Basic Example:
thislist = ["apple", "banana", "cherry"]
print(thislist)





Reading Example: >>> spam = ['cat', 'bat', 'rat', 'elephant']
>>> spam[0]
'cat'
>>> spam[1]
'bat'
>>> spam[2]
'rat'
>>> spam[3]
'elephant'
>>> ['cat', 'bat', 'rat', 'elephant'][3]
'elephant'
>>> 'Hello ' + spam[0]
'Hello cat'
>>> 'The ' + spam[1] + ' ate the ' + spam[0] + '.'
'The bat ate the cat.'


Loops: Loops in python are used for iterating over a sequence. "for" loop we can execite set of statments, once for each item ina list. 

for loop: 
# Prints out the numbers 0,1,2,3,4
for x in range(5):
    print(x)

# Prints out 3,4,5
for x in range(3, 6):
    print(x)

# Prints out 3,5,7
for x in range(3, 8, 2):
    print(x)
    
while loop: 
# Prints out 0,1,2,3,4

count = 0
while count < 5:
    print(count)
    count += 1  # This is the same as count = count + 1
    
    





















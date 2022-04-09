# Welcome to Coding Starter Pack Lab Number 1

![Homer Learning Python](https://media3.giphy.com/media/3o6MbhdrQxaTJxhOiQ/giphy.gif)

> Emphasize the start - Jason Selk
***

## If you can copy and paste, you can learn how to code.
### That said, to be a coder, you're going to have to first believe that you're life isn't over yet. That your brain isn't over yet.
#### That you can do something that you haven't done before. And if you believe that you can do something that you haven't done before, you're tall enough to step on this rollercoaster. And it will be  a rollercoaster.

***

## STEPS:
### copy and paste the code below into https://www.programiz.com/python-programming/online-compiler/ to get started
### when you're done copying and pasting, click on Run to complete Lab Number 1. You'll have gotten farther than 99% of people who start.
### when you're done copying and pasting the code, start changing stuff.

> Changing stuff and seeing what happens is the core principle of software engineering. 

![Changing stuff and seeing what happens](https://pbs.twimg.com/media/EPz8GQTXsAIBfsy.jpg)

***

![image](https://user-images.githubusercontent.com/45397093/162582764-b3797b4a-aadc-417d-960f-38b8ffb040ad.png)

***

```
# Start copying from here

# ever heard of invisible ink?
# if you start a line of with a #, it's like you're writing with invisible ink
# wow
# code
# isn't it cool
# when you start a line with a #, whatever you write after it is invisible to the user

# what if you wanted to go from invisible to visible
# that's easy

# let's start by showing the user a line of dashes
print ("------------------")
# congrats! you're a python developer.
# print ("") is how you print stuff on the screen

##################

# STEP 0: HELLO WORLD


print(" ")

# print Hello World
print("Hello World")

##################
print ("------------------")
# STEP 1: HELLO x
print ("STEP 1: HELLO x")
print(" ")
# create a variable called x to hold the value 5
x = 5

# print the value stored in x
print (x)

# change the value stored in x
x = 19
print (x)

##################
print ("------------------")
#STEP 2: HELLO NURSE
print("STEP 2: HELLO NURSE")
# create a variable called y to hold the value Nurse
y = "Hello Nurse"

# print the value stored in y
print(y)

##################
print ("------------------")
#STEP 3: HELLO LISTS
# create a list of values
listofvalues = [7, 4, 6, 1, 2, 4]

# print the list of values
print(listofvalues)

print("---------------")

# print the 0 position in the list
print(listofvalues[0])

# print the 3 position in the list
print(listofvalues[3])

# print the last position in the list
print(listofvalues[-1])

# print the length of the list of values
print(len(listofvalues))

##################
print ("------------------")

# HELLO LOOPS
print("Hello Loops")
#print all of the elements in listofvalues
for i in listofvalues:
    print(i)

##################

print ("------------------")
# HELLO DICTIONARIES

thisdict = {
  "brand": "Ford",
  "model": "Mustang",
  "year": 1964
}

for i in thisdict:
    print(i, ": ", thisdict[i])
    
print(len(thisdict))

##################
print ("------------------")
# HELLO LEETCODE 1

print("Dictionary filling positions 0-4 with values 1-5")
thisdict = {
    0: 1,
    1: 2,
    2: 3,
    3: 4,
    4: 5
    }

for i in thisdict:
    print(i, thisdict[i])

##################
print ("------------------")
# HELLO LEETCODE 2

print ("count represents position in array; value represents position's stored value")

values = ["a", "b", "c", "d"]

# print position and corresponding value in array
for count, value in enumerate(values):
     print(count, value)

# end copying here

```

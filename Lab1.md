# Welcome to Coding Starter Pack Lab Number 1

![Homer Learning Python](https://media3.giphy.com/media/3o6MbhdrQxaTJxhOiQ/giphy.gif)

> Emphasize the start - Jason Selk
***

## If you can copy and paste, you can learn how to code.
### That said, to be a coder, you're going to have to first believe that you're life isn't over yet. That your brain isn't over yet.
#### That you can do something that you haven't done before. And if you believe that you can do something that you haven't done before, you're tall enough to step on this rollercoaster. And it will be  a rollercoaster.

***
## STEPS:

![Changing stuff and seeing what happens](https://pbs.twimg.com/media/EPz8GQTXsAIBfsy.jpg)
> Changing stuff and seeing what happens is the core principle of software engineering. 

### copy and paste the code below into https://www.programiz.com/python-programming/online-compiler/ to get started
### when you're done copying and pasting, click on Run to complete Lab Number 1. You'll have gotten farther than 99% of people who start.
### when you're done copying and pasting the code, start changing stuff and clicking Run again to see what happens.
### Stop. Go for a walk. You learn when you're away from the desk because that's when you fire theta-nested gamma oscillations. The understanding will come when you walk away from the desk, trust me.

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
# create a list of grocery_list
listofgrocery_list = [7, 4, 6, 1, 2, 4]

# print the list of grocery_list
print(listofgrocery_list)

print("---------------")

# print the 0 position in the list
print(listofgrocery_list[0])

# print the 3 position in the list
print(listofgrocery_list[3])

# print the last position in the list
print(listofgrocery_list[-1])

# print the length of the list of grocery_list
print(len(listofgrocery_list))

##################
print ("------------------")

# HELLO LOOPS
print("Hello Loops")
#print all of the elements in listofgrocery_list
for i in listofgrocery_list:
    print(i)


##################
print ("------------------")
# HELLO LEETCODE 1

print("Dictionary filling positions 0-4 with grocery_list 1-5")
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
print("HELLO LEETCODE")
print("")
print("The reason you're here is because you are thinking about getting a job in code. Job in code are guarded by Leetcode, which is kind of like the SATs of code. If you pass your SATs, you get into whatever college you want. If you pass your Leetcode coding exams, you'll get into whatever company you want")
print("")
print("The most fundamental tool used in all coding tests is called an array. And array is simply a list of grocery_list, like your favourites on Spotify, or your friends on discord, or your followers on Twitter and Facebook. A list might be one of the most powerful inventions ever made.")

print("---------------------------")

# imagine making a grocery list. this is how we'd create a grocery list
grocery_list = ["apples", "bears", "coranges", "dblueberries"]

# creating a list isn't the same thing as showing it to the user, feel me? This is how you print the contents of value position zero
print(grocery_list[0])

# and this is how we print the other grocery_list
print(grocery_list[1])
print(grocery_list[2])
print(grocery_list[3])


# I'm telling you, if you've gotten this far, YOU'RE SOOOOO CLOOOOOOOOOOOSE!!

print("-------------------")

print ("So now you know how an array or a list works.")
print("")

# make sure to take breaks, feeel ms

print("The reason that we use lists is because we don't just have one user, or one song, or one picture; we have TONS OF THEM. Connecting lists - songs featuring Jay-Z and Pusha T at the same time - are things that users love. ")

# sometimes code is easier to understand when you read right to left. What this 
print ("------------------")
for count, value in enumerate(grocery_list):
     print(count, value)

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

# end copying here

```

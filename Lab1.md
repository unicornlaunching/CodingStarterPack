# Welcome to Coding Starter Pack Lab Number 1
## copy and paste the code below into https://www.programiz.com/python-programming/online-compiler/ to get started

<blockquote class="twitter-tweet"><p lang="en" dir="ltr">Creating the <a href="https://twitter.com/hashtag/Python?src=hash&amp;ref_src=twsrc%5Etfw">#Python</a> Tutorial for idiots like me. <a href="https://twitter.com/hashtag/100DaysOfWeb3?src=hash&amp;ref_src=twsrc%5Etfw">#100DaysOfWeb3</a><br><br>If you&#39;re just starting out, you can start code learning immediately with <a href="https://t.co/1zv6PR0x8z">https://t.co/1zv6PR0x8z</a> <a href="https://t.co/ATqjUshDwo">pic.twitter.com/ATqjUshDwo</a></p>&mdash; So you want to... (@attractfunding) <a href="https://twitter.com/attractfunding/status/1512825132066263041?ref_src=twsrc%5Etfw">April 9, 2022</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

```python
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
```

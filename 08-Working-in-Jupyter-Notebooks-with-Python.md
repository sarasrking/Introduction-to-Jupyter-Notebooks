---
Title: "Working in Jupyter Notebooks with Python"
Teaching: 45
Exercises: 4
Question:
- How do I get started in Python?
Objectives:
- Use some basic commands in P
Activity:
 - Create a sequence, assign a value, use the sum and print commands
 - Create a list and a dictionary
Keypoints:
 - Coding is all about little steps. Let's start at the beginning!
---

# Working in Jupyter Notebooks with Python

Now let's try using Python for some of the things we did in R. The first thing we need to do is create a new Notebook. Select 'Python 3' after you click on new. Give your new Notebook a name. 

Watch the top right hand corner of the screen to see when the the kernel is ready. When it changes to 'Trusted' we're ready to go.

In this part of the workshop we'll be having a go at using Python, doing some of the same things we did in R, though I'll also be introducing a couple of new concepts as we go, because the two programming languages work differently. 

## Sequence

Let's start with creating a sequence of numbers again.

In a new cell, select 'code'. Remember that the code cell looks different to the markdown cell. How can you tell?

- Type the following inside the cell:

`list(range(1, 20))`

- Click on 'Run' or use the shortcut **Shift+Enter** to execute the cell.

You have just created a list of the range of numbers from 1 to 20. Woohoo!

## Value

 - In the next cell type the following:

`a = list(range(1, 20))`

This command tells the computer that the list of numbers you created can now be called 'a'. This is called a 'value'.

## Sum

- In the SAME cell type the following underneath:

`x = sum(a)`

This second instruction tells the computer to add each of those numbers in the list ('a') together and give that total a value of 'x'.

## Print

- In the SAME cell type the following underneath:
    
`print(x)`

-  Click on 'Run' or use the shortcut **Shift+Enter** to execute the cell.

This last instruction tells the computer to print the total of the list of numbers on the screen.

You just did some computing! Hooray! 

Mindbender: With these three instructions you have performed a 'sequence'. In computing, this is a list of instructions to be carried out in order and forms one of the backbones of programming. It is different to the sequence of numbers we created above. 

### Activity

Take a few minutes to change the range of numbers, and/or change the values and see what happens. Have a bit of fun with it - see if you can beat the computer with your lightning speed mental arithmetic skills. Or just be amazed at how fast it can be.

## Creating a list
 
Lists are ordered sequences of elements, and values can be repeated. 

- In your 'code' cell, write the following series of commands:
    
```
arr = ["Jack", "Queen", "King"]
print(arr[0])
print(arr[1])
print(arr[2])
```

- Click on 'Run' or use the shortcut **Shift+Enter** to execute the cell.

Using the command 'arr=' gives the content of the square brackets the value of an 'array'. Each thing in the list has then an automatically appointed number, from its order in the list. The first thing, the word "Jack" is position 0, the second, "Queen" is position 1, and so on. 
Those numbers are then what you use to perform your computation or visualisation, as you see when you use the command 'print' to show each one as a printed output on the screen. What you can see is that you have assigned each word a number (also known as a key, or array index.

### Activity

What would you do to print the items in the list in a different order? (HINT: There are more ways than one!)

## Creating a dictionary or set

Now let's create a dictionary or set, using data of different types. In this table we'll use text, number and date data types. 

Sets are collections of unique elements and you cannot order them. Lists are ordered sequences of elements, and values can be repeated. 

Curly braces are used in Python to define a dictionary. A dictionary is a data structure that maps one value to another - kind of like how an English dictionary maps a word to its definition.

- In your 'code' cell, write the following series of commands:

```
d = {'employee': 'Juanita Lopez','salary':81000, 'startdate': '2010-11-1'}
e = {'employee': 'Peter Gynn','salary':83400, 'startdate': '2008-3-25'}
f = {'employee': 'Jolie Talofa','salary':96800, 'startdate': '2007-3-14'}
print (d)
print (e)
print (f)
```

- Click on 'Run' or use the shortcut **Shift+Enter** to execute the cell.

Here we have assigned these three different rows (or dictionaries) a value of either 'd', 'e', or 'f'. Using the print command you can print them on the screen.

Dictionaries map keys to values, and the keys must be unique. This and other restrictions help Python keep track of them efficiently and know they are and that they remain unique.

In Python, the key is the term used before the colon and the value is the term used after it. The quote mark encapsulates the whole term, the comma separates them. The curly braces hold the whole 'dictionary'.

- In your 'code' cell, write the following series of commands:
    
```
d.keys()
d.values()
d.items()
```

- Click on 'Run' or use the shortcut **Shift+Enter** to execute the cell.

This set of commands has now created a list of dictionary items as values. The 'd.' prefix refers to the dictionary we called 'd' above.

- In your 'code' cell, write the following series of commands:
    
```
for k,v in d.items():
    print (k, v)
```

- Click on 'Run' or use the shortcut **Shift+Enter** to execute the cell.

The tab key is important here. In this case we are showing the keys and values in the dictionary called 'd'.

- In your 'code' cell, write the following series of commands:

```
for k,v in e.items():
    print(k, v)
```

- Click on 'Run' or use the shortcut **Shift+Enter** to execute the cell.

In this case we are showing the keys and values in the dictionary called 'd'.

**Remember**: Curly braces create dictionaries or sets. Square brackets create lists.

### Activity

Print the dictionary called 'f' using the 'for' command. 
Create a new dictionary to add to the employee dataset.

## A new dictionary

Dictionaries can be contained in lists and vice versa. A list is an ordered sequence of objects, whereas dictionaries are unordered sets. But the main difference is that items in dictionaries are accessed via keys and not via their position.

More theoretically, we can say that dictionaries are the Python implementation of an abstract data type, known in computer science as an associative array.

Associative arrays consist - like dictionaries of (key, value) pairs, such that each possible key appears at most once in the collection. Any key of the dictionary is associated (or mapped) to a value. The values of a dictionary can be any Python data type.

Let's make an English-German dictionary:

- In your 'code' cell, write the following series of commands:
    
```
en_de = {"red" : "rot", "blue" : "blau", "yellow" : "gelb"}
print (en_de)
```

- Click on 'Run' or use the shortcut **Shift+Enter** to execute the cell.

You now have the beginnings of a list of colours in both languages. Let's see if we can make it work:

- In your 'code' cell, write the following series of commands:
    
`print (en_de["red"])`

- Click on 'Run' or use the shortcut **Shift+Enter** to execute the cell.

Hooray! You just translated 'red' into German.

Now let's add some French.

- In your 'code' cell, write the following series of commands:
    
```
de_fr = {"rot" : "rouge", "blau" : "bleu", "gelb" : "jaune"}
print ("The French word for red is: " + de_fr[en_de["red"]])
```

- Click on 'Run' or use the shortcut **Shift+Enter** to execute the cell.

By creating a dictionary structure you can now go to French via German.

## Activity

See if you can translate from French to English, and German to French.

Expand on this dictionary.

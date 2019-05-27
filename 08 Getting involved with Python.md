---
Title: "Getting involved with Python"
Teaching: 30
Exercises: 1
Question:
- How do you assign values to variables in Python?
Objectives:
- Understand the concepts of values and variables. 
Activity:
 - Create a mini database in Python - also known as a dictionary.
Keypoints:
 - Remember that programming is about language as much as maths - you _can_ talk to a computer and it will understand if you know the language!
---

## Ready to splash a little with Python?

  - In a new cell, select 'code'. Remember that the code cell looks different to the markdown cell. _How can you tell?_ 
  
    Type the following inside the cell:
    
      **d = {'employee': 'Juanita Lopez','salary':81000, 'startdate': '2010-11-1'}**
      
      **e = {'employee': 'Peter Gynn','salary':83400, 'startdate': '2008-3-25'}**
      
      **f = {'employee': 'Jolie Talofa','salary':96800, 'startdate': '2007-3-14'}**
      
      **print (d)**
      
      **print (e)**
      
      **print (f)**
      
  - Click on 'run' or Shift+Enter.

[SCREEN SHOT]

So what is going on here?

The equal sign (=) is used to assign values to groups of variables. This creates a kind of shorthand for working on these variables later.

[NEED MORE EXPLANATION ABOUT WHAT THIS IS USEFUL FOR]

[MIGHT NEED AN ACTIVITY HERE TO PRACTICE WHAT WE JUST DID ABOVE?]

  - In a new code cell, type the following:

      **d.keys()**

      **d.values()**

      **d.items()**

  - Click on 'run' or Shift+Enter.

  - In the next cell, type:

      **for k,v in d.items():**
      
      **print(k, v)**

  - Click on 'run' or Shift+Enter.

  - In the next cell, type:

      **for k,v in e.items():**
      
      **print(k, v)**

 - Click on 'run' or Shift+Enter.

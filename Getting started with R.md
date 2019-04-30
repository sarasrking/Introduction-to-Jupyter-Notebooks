---
Title: "Getting started with R"
Teaching: 15
Exercises: 1
Question:
- How do you open a notebook and what do you do when you get there?
Objectives:
- Open a notebook then use markdown and R to perform basic tasks
Activity:
 - With a group, work on a calculation and have a go at changing some of the code to produce different results.
Keypoints:
 - Get started, be fearless!
---
## Getting started

Follow these step-by-step instructions to get started with Jupyter Notebooks using Python:

1. Open MyBinder: https://mybinder.org/
2. Paste the link to this GitHub repository https://github.com/ingridbmason/Intro-to-Jupyter/ and click on LAUNCH.
3. Open workshop list of commands in separate window: https://github.com/ingridbmason/Intro-to-Jupyter/blob/master/Worksheet_R.txt
4. Open a new notebook from the top righthand dropdown menu: Click on 'New' and then select R. 

![New](https://user-images.githubusercontent.com/48195568/56337762-02459e00-61e6-11e9-8293-c19ba8d30c4c.jpg)

5. Select 'File' at the top left hand side of the screen and select 'Save As'. Name your notebook 'Intro to Jupyter Notebooks'.

## Let's go for dip with R

Using the workshop list of commands - saved in the repository as **Worksheet_R.txt** we can now start with some basic markdown. Remember that [markdown](https://en.wikipedia.org/wiki/Markdown) is how you can make rich (or formatted) text in a plain text editor.

- First let's splash around in markdown!
  - Markdown is for writing down comments outside of the code cells, so you can describe what you are doing as you go.
  - In computer programming a 'string' is sequence of alphanumerical characters
  - Type **<# this is a string>** into the cell, making sure you select 'Markdown' from the dropdown menu above where it shows 'Code' as the default. Already here you can see how notebooks are flexible, as you can choose what kind of cell you are writing in (and toggle it at any time!)
  
  ![markdown](https://user-images.githubusercontent.com/48195568/56338527-89484580-61e9-11e9-965c-3726d8fd7fbb.png)

  - Click on 'Run' or use the shortcut **Shift+Enter** to execute the cell. 
  - You have just created a heading in your notebook! Hooray!
 
  ![STRING](https://user-images.githubusercontent.com/48195568/56339085-dcbb9300-61eb-11e9-88c9-60034e797b68.JPG)
 
  - Now let's try italics. In a new cell type **< _this is a string_ >**, and select 'Markdown' from the dropdown menu again.
  - Click on 'Run' or use the  shortcut **Shift+Enter** to execute the cell.
  - Voila! _Italics!_
   
  ![italics](https://user-images.githubusercontent.com/48195568/56340380-ea274c00-61f0-11e9-8580-f471417719d9.JPG)
    
What happens? What is going on here? Speak in small groups about these instructions, markdown and what you've just learned. It can feel a little strange, as you already know how to do this in programs like Word, but what we are doing here is shorthand, and 'speaking' directly to the computer, with a different kind of interface.


### Mini-activity

Following the same steps as above but selecting 'Code' from the dropdown menu for the next fields, try typing this: 

  -**print ("this is a string")**
    
Now let's try to print out a calculation using 'x':

-**x<- "this is a string"**
-**print (x)**

Let's see what happens when we add this:

-**print(x, quote = false)**

If you want to know more, take a look at these pages: 

- https://guides.github.com/features/mastering-markdown/
- http://www.gastonsanchez.com/r4strings/formatting.html

![Alt Text](https://media.giphy.com/media/vFKqnCdLPNOKc/giphy.gif)

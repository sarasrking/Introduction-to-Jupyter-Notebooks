---
Title: "Swimming with Python"
Teaching: 15
Exercises: 1
Question:
- How do you create a dataset[dictionaries?] in Jupyter Notebooks?
Objectives:
- Create a basic dataset and understand basic concepts of [dictionaries]***
Activity:
 - Translate English into French via German
Keypoints:
 - Building a flexible dataset can save you time in the long run!
---

## Dictionaries

In Python dictionaries are written with curly brackets, and they have keys and values. Dictionaries are essentially datasets - they are simply a collection of objects.

Key - value pairs eg key is the word you look up, value is the definition

Type the following into the code cell:

  *# -*- coding: iso-8859-1 -*-* 

This first line of code (also known as 'script') is necessary to use the (iso-8859-1)<https://en.wikipedia.org/wiki/ISO/IEC_8859-1> code with German Umlaute.The file has to be saved in this coding as well. 

In the next cell, type the following:

  *en_de = {"red" : "rot", "blue" : "blau", "yellow" : "gelb"}*
  *print (en_de)*
  *print (en_de["red"])*
  
In the previous cell we just created an English-German dictionary, and could then return the request for the German word for the Englihs word 'red'.

Now type in the following:

  *de_fr = {"rot" : "rouge", "blau" : "bleu", "gelb" : "jaune"}*
  *print ("The French word for red is: " + de_fr[en_de["red"]])*
 
In the first line we created a German-French dictionary. Because the previous code included English, we could then easily create a French-English dictionary, without having to do it manually. This is the kind of automation that makes Jupyter Notebooks so handy and efficient as a data wrangling tool. 

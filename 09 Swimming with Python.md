---
Title: "Creating dictionaries with Python"
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

Dictionaries are essentially datasets - they are simply a collection of objects.

Dictionaries work with key-value pairs, eg the key is the word you look up, and the value is the definition. 

In Python dictionaries are written with curly brackets, and the keys and values are separated by a colon ( : ).

## Activity

Now we are going to create a little dictionary. 

Type the following into the code cell:

  **en_de = {"red" : "rot", "blue" : "blau", "yellow" : "gelb"}**
  
  **print (en_de)**
 
Click on Shift+Enter. Remember if you get something wrong, you can either edit the code cell, or you can delete it by clicking on the scissor icon.

You can see that you have printed out the dataset you have started to create. The computer has created an associated with those German words and their English equivalents. Now type the following and click on Run or Shift+Enter:
  
   **print (en_de["red"])**
  
We just created an English-German dictionary! See how you could then return the request for the German word for the English word 'red'?

Now type in the following click on Run or Shift+Enter:

   **de_fr = {"rot" : "rouge", "blau" : "bleu", "gelb" : "jaune"}**
   
This time we are creating a German to French dictionary. 

Now type in the following click on Run or Shift+Enter:

   **print (de_fr["rot"])**
   
Now what happens if we want to translate directly from English to French? Try this:
   
   **print ("The French word for red is: " + de_fr[en_de["red"]])**
 
In the first line we created a German-French dictionary. Because the previous code included English, we could then easily create a French-English dictionary, without having to do it manually. 

This is the kind of automation that makes Jupyter Notebooks so handy and efficient as a data wrangling tool. 

Can you think of any other applications for this kind of process? Have a chat with your partner about any other ways you think this sort of categorising of data might be interesting to you. 

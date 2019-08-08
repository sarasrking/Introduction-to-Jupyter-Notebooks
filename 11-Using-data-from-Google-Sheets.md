---
Title: "Using data from Google Sheets"
Teaching: 5
Exercises: 1
Question:
- How do you work in Jupyter Notebooks with data from Google Sheets?
Objectives:
- Access a Google Sheets dataset using Jupyter Notebooks
Activity:
 - Use 'pandas' to read data
Keypoints:
 - This is where the fun begins!
---

# Using data from Google Sheets

Thi is another way you can quickly import a dataset into your Jupyter Notebook. Make sure you are working in Jupyter Notebooks with the Python kernel running. We are going to use a software library called 'pandas', written for data manipulation and analysis in Python.

First, take a look at the GIF attached to this Tweet: https://twitter.com/choldgraf/status/1141436794359046144?s=12 

You can create a basic dataset using Google Sheets and use the 'pandas' command to import the data into Jupyter Notebooks. 

REMEMBER: The data used in this way will be made public via the public link. Not for sensitive data!

Here's the code to copy, with a link to a Fortune 500 dataset prepared earlier :)
    
- In a code cell, type:

`import pandas`

- Click on 'Run' or use the shortcut Shift+Enter to execute the cell.

- In the next code cell, type: 
    
 `pandas.read_csv ("")`
 
- And then, in between the quote marks, paste this link: 
    
    https://docs.google.com/spreadsheets/d/e/2PACX-1vQctQqQu1baZQJfhV333sEcjnkmvnRFtCGF0HVfoV3WnSmeDhhFneZ7bYtaxe3xFeMS9-pmzk83AuR4/pub?output=csv 
    
    (this is what is known as a 'token')

### Activity

You can continue to work with this data set, following along with the tutorial here: 

https://www.dataquest.io/blog/jupyter-notebook-tutorial/

# Recommendations with IBM

This exercise is the final project of the Udacity Data Science Nanodegree Program.

Introduction

For this project you will analyze the interactions that users have with articles on the IBM Watson Studio platform, 
and make recommendations to them about new articles you think they will like. Below you can see an example of what the dashboard 
could look like displaying articles on the IBM Watson Platform.

## Your Tasks

Your project will be divided into the following tasks:

### I. Exploratory Data Analysis

Before making recommendations of any kind, you will need to explore the data you are working with for the project. 
Dive in to see what you can find. There are some basic, required questions to be answered about the data you are working with 
throughout the rest of the notebook. Use this space to explore, before you dive into the details of your recommendation system 
in the later sections.

### II. Rank Based Recommendations

To get started in building recommendations, you will first find the most popular articles simply based on the most interactions.
Since there are no ratings for any of the articles, it is easy to assume the articles with the most interactions are the most popular.
These are then the articles we might recommend to new users (or anyone depending on what we know about them).

### III. User-User Based Collaborative Filtering

In order to build better recommendations for the users of IBM's platform, we could look at users that are similar in terms of the 
items they have interacted with. These items could then be recommended to the similar users. This would be a step in the right direction
towards more personal recommendations for the users. You will implement this next.

### IV. Content Based Recommendations (EXTRA - NOT REQUIRED)

Given the amount of content available for each article, there are a number of different ways in which someone might choose to 
implement a content based recommendations system. Using your NLP skills, you might come up with some extremely creative ways to 
develop a content based recommendation system. You are encouraged to complete a content based recommendation system, but not required 
to do so to complete this project.

### V. Matrix Factorization

Finally, you will complete a machine learning approach to building recommendations. Using the user-item interactions, you will build
out a matrix decomposition. Using your decomposition, you will get an idea of how well you can predict new articles an individual might 
interact with (spoiler alert - it isn't great). You will finally discuss which methods you might use moving forward, and how you might
test how well your recommendations are working for engaging users.

Before you submit your work, check the RUBRIC to make sure you meet all of the rubric items.

## Files Structure

The file structure is as follows:
1. data files -> articles community and user item interactions csv files. 
2. assets files -> top_5.p, top_10.p, top_20.p files
3. Recommendations_with_IBM.html -> comple version notebook in html file 
4. Recommendations_with_IBM.ipynb -> complete version notebook 
5. project_test.py -> test file  
6. user_item_matrix.p -> user matrix file

## Submission Instructions

### What to Submit

### Required

Once you are satisfied with the status of your Notebook, you should save it in a format that will make it easy for others to read.
You can use the File -> Download as -> HTML (.html) menu to save your notebook as an .html file. If you get an error about "No module 
name", then open a terminal and try installing the missing module using pip install <module_name> (don't include the "<" or ">" or any
words following a period in the module name).

You will submit both your original Notebook and an HTML or PDF copy of the Notebook for review. There is no need for you to include any 
data files with your submission. If you made reference to other websites, books, and other resources to help you in solving tasks in the 
project, make sure that you document them. It is recommended that you either add a "Resources" section in a Markdown cell at the end of 
the Notebook report, or you can include a readme.txt file documenting your sources.

## License
[MIT](https://choosealicense.com/licenses/mit/)

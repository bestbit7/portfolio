---
title: "Data Analysis Using Pandas"
date: 2019-06-15
tags: [Data Science]
header:
    image: "/images/projects.jpg"
excerpt: "Read the data from the file into pandas DataFrame. Analyze, clean and transform the data to answer the following question:
What categories of passengers were most likely to survive the Titanic disaster?"
mathjax: "true"
---

## Data Science Certificate Assignment 2
### Goal
Read the data from the file into pandas DataFrame. Analyze, clean and transform the data from Kaggle website to answer the following question:

What categories of passengers were most likely to survive the Titanic disaster?

**Question 1.**

The answer to the main question - What categories of passengers were most likely to survive the Titanic disaster?
The detailed explanation of the logic of the analysis

**Answer:**

People who are female from the first class and 1~9 years old were most likely to have survived.

    63% of the people from the first class survived.
    74% of females survived.
    The age groups between 20~29 and 30~39 had highest number of survivors which is 43% of the TOTAL number of the people but ratio wise, 61% of people between ages 1~9 had highest possibility of survivng.
    SibSp and Parch were analyzed but the percentages between data are not significant so these attributes were not included in the result.

**Question 2.**

    What other attributes did you use for the analysis? Explain how you used them and why you decided to use them.
    Provide a complete list of all attributes used.

**Question 3.**

    Did you engineer any attributes (created new attributes)? If yes, explain the rationale and how the new attributes were used in the analysis?
    If you have excluded any attributes from the analysis, provide an explanation why you believe they can be excluded.

**Question 4.**

    How did you treat missing values for those attributes that you included in the analysis (for example, age attribute)? Provide a detailed explanation in the comments.


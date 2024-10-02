# Assignment 2 - Write UP

## Description
This assignment is about learning and applying the while loop and iterating through multiple lists at a time.  We also will discuss how we match things in chatbots in order to extract what a user is trying to find.  Next assignment we will work with data bases and how we can extract information from them.

## What to complete
1. Go through the notes.py file w/ Mr. Berg
2. Complete `a2.py`, Mr. Berg will walk everyone through the process
3. Make sure you pass all asserts in `a2.py`
4. Complete the reflection problems below
5. Push your code to github for grading

## Reflection Questions
1. What was difficult for you while completing the match function?
    There were a couple stumbling points that were tricky to navigate when writing the match function. My original design for the % keyword added each element to the result list independently (like a series of underscores). When I realized I had to combine them into one element I had some trouble making spaces between them but not before the first one or after the last one (I did this before you showed us the join() function). I had to rewrite almost all of my percent code, but I got it eventually.


2. Explain how you could use the match function for extracting information from a movie database.
You could match queries to patterns to determine what keywords they want to know (directed, acted, star wars, etc)
 and search a database for those keywords.

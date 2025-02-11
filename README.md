#              Manipulation of CSV

When tasked with manipulating a 30k + entries CSV based off a input or partial input in another column, the creation of this script was a must.
Saved me hundreds of hours in my internship at Dublin City Council ICT department 


#  How it works

The Script takes in 3 variables;
target1 - this is the field you want to change, where you expect to make a change.
target - is the paremeter you'll look for in order to make changes
newTarge - this is your outcome, it is what you want to change target1 to this value

# Tools utilized

Pandas library - Pandas is a powerful tool, mostly used throughout my machine learning/AI module at college
when I read the documentation on Pandas, it was clear that the library provides a solid way to manipulate data.

# Outcomes

There are 2 scripts attached to this repo, they do follow mostly the same approach and have similar outcomes
differentiation between them is that one maintains the same CSV structure, altering only necessary fields as requested
while the other alters the whole structure of the document, leaving one fields that you target as the outcome.

# Analysis

This file is will give you a CSV file with the same structure as the one it is given as a dataframe.
this is a nice way of bulk-editing your CSV, making this a powerful script for that sense.

# Analysis2

This file will change the structure of your CSV, making sure to leave only the columns you require,
this can be useful if you need to work on anything that you require a clear and less problematic view of your CSV.

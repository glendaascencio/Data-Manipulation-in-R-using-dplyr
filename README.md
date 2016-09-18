---
title: "Data Manipulation in R using dplyr"
author: "Glenda Ascencio"
date: "August 28, 2016"
output: html_document
---
## Five main functions in dplyr are:

### * selects = removes columns for a database (which returns a subset of the columns)
### * filter = which removes rows (that is able to return a subset of the rows)
### * arrange = which reorders the rows according to single or multiple variables
### * mutate = used to add columns from existing data
### * summarise = which reduces each group to a single row by calculating aggregate measures

## Real structure of data
### * select and mutate = manipulates the variables in your data
### * filter and arrange = manipulates the observations
### * summarize = manipulates groups of observations

## tydyr = helps us organize the data into a tidyr layout 

### Logical Operators with the **filter()** function
* x < y, TRUE if x is less than y
* x <= y, TRUE if x is less than or equal to y
* x == y, TRUE if x equals y
* x != y, TRUE if x does not equal y
* x >= y, TRUE if x is greater than or equal to y
* x > y, TRUE if x is greater than y
* x %in% c(a, b, c), TRUE if x is in the vector c(a, b, c)

#### Aggrate functions
* min(x) - minimum value of vector x.
* max(x) - maximum value of vector x.
* mean(x) - mean value of vector x.
* median(x) - median value of vector x.
* quantile(x, p) - pth quantile of vector x.
* sd(x) - standard deviation of vector x.
* var(x) - variance of vector x.
* IQR(x) - Inter Quartile Range (IQR) of vector x.
* diff(range(x)) - total range of vector x.
* first(x) - The first element of vector x.
* last(x) - The last element of vector x.
* nth(x, n) - The nth element of vector x.
* n() - The number of rows in the data.frame or group of observations that summarise() describes.
* n_distinct(x) - The number of unique values in vector x



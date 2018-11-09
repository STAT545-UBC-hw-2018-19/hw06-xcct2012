# STAT 547 Homework 06
## Zachary Sherker

# Introduction

In this worksheet, I will be completing the tasks outlined in Parts 1 and 2 in the homework exercises as follows:

## Part 1: Read and work the exercises in the Strings chapter

(1) In code that doesn’t use stringr, you’ll often see paste() and paste0(). What’s the difference between the two functions? What stringr function are they equivalent to? How do the functions differ in their handling of NA?

(2) In your own words, describe the difference between the sep and collapse arguments to str_c().

(3) What does str_trim() do? What’s the opposite of str_trim()?

(4) Write a function that turns (e.g.) a vector c("a", "b", "c") into the string a, b, and c. Think carefully about what it should do if given a vector of length 0, 1, or 2.

## Part 2: Writing functions

  Write one (or more) functions that do something useful to pieces of the Gapminder or Singer data. It is logical to think about computing on the mini-data frames corresponding to the data for each specific country, location, year, band, album, … This would pair well with the prompt below about working with a nested data frame, as you could apply your function there.

  Make it something you can’t easily do with built-in functions. Make it something that’s not trivial to do with the simple dplyr verbs. The linear regression function presented here is a good starting point. You could generalize that to do quadratic regression (include a squared term) or use robust regression, using MASS::rlm() or robustbase::lmrob().

* Links to the files in my repository can be found below:

hw06.Rmd file -- https://github.com/STAT545-UBC-students/hw06-xcct2012/blob/master/STAT547_hw06.Rmd

hw06.html file -- https://github.com/STAT545-UBC-students/hw06-xcct2012/blob/master/STAT547_hw06.html

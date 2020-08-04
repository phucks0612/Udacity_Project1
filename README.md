# Udacity_Project1

Data visualization to understand of coding during youth in order to success in tech field

## Motivation

A typical confusion about developers is that they’ve all been programming since youth. I want to see if it is true using data.

## Technology used

* [Stack Overflow Annual Developer Survey](https://insights.stackoverflow.com/survey) - The data set used
* [Python Pandas library](https://pandas.pydata.org)
* [Python Numpy library](https://numpy.org)

## Summary

- There is little to no gap between developers who program since your with those who break into the field
- The average time spent to learn before getting a professional job is increasing

## What's included

```
* source.ipynb - the main file in which all the calculation is done
```

## CRISP-DM

```
  * Business Understanding: Find out the relationship between salary and years of coding prior to developers' first jobs.
  * Data Understanding: Stack Overflow Annual survey: the annual survey for developers with over 150 questions about every thing: their preferred language, salary, age, etc...
  * Data Preparation: In this project, I drop all the rows with NaN values in these columns: "Salary", "YearsProgram", "YearsCodedJob"
  * Modeling: plot chart to understand the trend and relationship between developers and their experience
  * Evaluation: You can read about it in my blog post
  
```

## Question answered

```
  1) What is the distribution of the years of learning to code before first professional(YearsProgramPrior) jobs among developers
  2) What is the avarage salary and career satisfaction among these developers group by YearsProgramPrior 
  3) What is the trend of YearsProgramPrior
```
## Blog post

* [link to my Medium blog post](https://medium.com/@phanchithanh091/this-is-why-you-can-start-your-career-as-a-programmer-right-now-4eb2076cdd79)

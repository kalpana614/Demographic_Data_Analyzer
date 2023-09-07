# Demographic_Data_Analyzer
## Overview

This project involves analyzing demographic data using Pandas. You are provided with a dataset of demographic information extracted from the 1994 Census database. Your task is to answer several questions based on this dataset.

## Getting Started

To start working on this project, follow these steps:

1. Import the project on Replit.
2. In the .replit window, select "Use run command" and click the "Done" button.

## Dataset

Here is a sample of the dataset you will be working with:

|    |   age | workclass        |   fnlwgt | education   |   education-num | marital-status     | occupation        | relationship   | race   | sex    |   capital-gain |   capital-loss |   hours-per-week
|---:|------:|:-----------------|---------:|:------------|----------------:|:-------------------|:------------------|:---------------|:-------|:-------|---------------:|---------------:|-----------------:|
|  0 |    39 | State-gov        |    77516 | Bachelors   |              13 | Never-married      | Adm-clerical      | Not-in-family  | White  | Male   |           2174 |              0 |               40 | 
|  1 |    50 | Self-emp-not-inc |    83311 | Bachelors   |              13 | Married-civ-spouse | Exec-managerial   | Husband        | White  | Male   |              0 |              0 |               13 | 
|  2 |    38 | Private          |   215646 | HS-grad     |               9 | Divorced           | Handlers-cleaners | Not-in-family  | White  | Male   |              0 |              0 |               40 | 
|  3 |    53 | Private          |   234721 | 11th        |               7 | Married-civ-spouse | Handlers-cleaners | Husband        | Black  | Male   |              0 |              0 |               40 | 
|  4 |    28 | Private          |   338409 | Bachelors   |              13 | Married-civ-spouse | Prof-specialty    | Wife           | Black  | Female |              0 |              0 |               40 |           

## Questions to Answer

You are required to answer the following questions using Pandas:

1. How many people of each race are represented in this dataset? This should be a Pandas series with race names as the index labels. (race column)

2. What is the average age of men?

3. What is the percentage of people who have a Bachelor's degree?

4. What percentage of people with advanced education (Bachelors, Masters, or Doctorate) make more than 50K?

5. What percentage of people without advanced education make more than 50K?

6. What is the minimum number of hours a person works per week?

7. What percentage of the people who work the minimum number of hours per week have a salary of more than 50K?

8. What country has the highest percentage of people that earn >50K and what is that percentage?

9. Identify the most popular occupation for those who earn >50K in India.

## Development and Testing

- For development, you can use `main.py` to test your functions. Click the "run" button in Replit, and `main.py` will run.

- Unit tests are written for you under `test_module.py`. The tests will run automatically whenever you hit the "run" button.

## Submitting

Copy your project's URL from Replit and submit it to freeCodeCamp.

## Dataset Source

Dua, D. and Graff, C. (2019). UCI Machine Learning Repository. Irvine, CA: University of California, School of Information and Computer Science.

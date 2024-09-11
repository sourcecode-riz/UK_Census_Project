# Census Report - Fundamentals of Data Science

**Author:** Muhammad Rizwan Arshad  
**Student ID:** 202255401

---

## Table of Contents

1. [Introduction](#introduction)
2. [Data Cleaning](#data-cleaning)
   - 2.1 [Removing Whitespaces](#removing-whitespaces)
   - 2.2 [Converting Data Types](#converting-data-types)
   - 2.3 [Removing Blanks & Fixing Typos](#removing-blanks--fixing-typos)
3. [Analysis](#analysis)
   - 3.1 [Age Distribution](#age-distribution)
   - 3.2 [Unemployment Trends](#unemployment-trends)
   - 3.3 [Religious Affiliation](#religious-affiliation)
   - 3.4 [Divorce & Marriage Rate](#divorce--marriage-rate)
   - 3.5 [Occupancy Level](#occupancy-level)
   - 3.6 [Students & Commuters](#students--commuters)
4. [Recommendations and Conclusion](#recommendations-and-conclusion)
5. [References](#references)

---

## Introduction

The census is conducted by the Office of National Statistics (ONS) every ten years in the UK. The latest census was completed in 2021. This report provides an analysis of a mock census for the imaginary town "Gotham City," inspired by the Batman movies. This analysis is part of a local government decision-making process for the town, focusing on:
- What to do with an unoccupied plot of land
- What to invest in

---

## Data Cleaning

Data cleaning is the process of fixing or removing incorrect, corrupted, incorrectly formatted, duplicate, or incomplete data within a dataset.

### Removing Whitespaces

Whitespaces before and after the data values were removed using Python's `strip()` method. 

### Converting Data Types

The 'House Number' column was converted to integers, and 'Age' was converted from float to integer.

### Removing Blanks & Fixing Typos

All empty cells were filled or corrected based on analysis, such as replacing blanks in the 'Age' column with 0 and correcting typos in columns like 'Relationship to Head of House'.

---

## Analysis

Data analysis was performed after cleaning the data. Below are some key analyses:

### Age Distribution

- Total population: 9,405 (47.28% male, 52.72% female)
- Age groups show that people between 36-54 years form the majority, with females slightly outnumbering males.

### Unemployment Trends

- Unemployment rate in Gotham City: 11.49%
- The top 10 occupations are listed, with the health sector dominating.

### Religious Affiliation

- More than 57% of the population reported no religious affiliation, with Christianity being the largest religion at 22.34%.

### Divorce & Marriage Rate

- The marriage rate in Gotham City is higher than the divorce rate, with single individuals making up 34.12% of the population.

### Occupancy Level

- There are 3,329 houses with an average of 2.83 occupants per house. The data shows no need for more housing despite some outliers.

### Students & Commuters

- 43.4% of the population are students, with a significant number of them commuting daily.

---

## Recommendations and Conclusion

1. **Train Station:** A large number of commuters justify the construction of a train station to ease road congestion.
2. **Old Age Care:** The growing middle-aged population indicates the future need for old-age care facilities.

---

## References

- BBC 2022. BBC- Census. [Available here](https://www.bbc.co.uk/news/uk-63485073)
- ONS 2023. Old Age Profile. [Available here](https://www.ons.gov.uk)
- Tableau 2023. Guide To Data Cleaning. [Available here](https://www.tableau.com/learn/articles/what-is-data-cleaning#definition)
- ONS 2022. About the Census. [Available here](https://www.ons.gov.uk/census/aboutcensus/aboutthecensus)

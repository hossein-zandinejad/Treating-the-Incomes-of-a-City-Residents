# Treating the Incomes of City Residents

![City](city.gif)

## Table of Contents
- [Introduction](#introduction)
- [Data](#data)
- [Methodology](#methodology)
  - [Handling Missing Data](#handling-missing-data)
  - [Parametric Tests](#parametric-tests)
- [Analysis](#analysis)
- [Test Summary](#test-summary)
- [References](#references)

## Introduction

The Treating the Incomes of City Residents project aims to assist government decision-making by analyzing a dataset that includes information about residents' sex, age, education, and salary. To achieve this, we have employed statistical methods such as central tendencies, index of dispersion, and parametric tests. This README provides an overview of the project and its key findings.

## Data

The dataset used in this analysis contains demographic statistics, including sex, age, education level, and salary of city residents.

## Methodology

### Handling Missing Data

We started by addressing missing data in the dataset. Missing values in salary columns were replaced with the mean value of their respective columns.

### Parametric Tests

We conducted parametric tests to compare the means of Salary 1 and Salary 2. Assumptions checked included:

- Residuals (experimental error) are normally distributed.
- Homogeneity of variances (variances are equal between treatment groups).
- Observations are sampled independently from each other.

## Analysis

We collected several key insights from the dataset, including population composition by sex, age groups, and education levels. Some notable findings include the mean salaries of men and women, age distribution, and salary variances between Salary 1 and Salary 2.

## Test Summary

We performed several statistical tests to compare Salary 1 and Salary 2, including independent t-tests, paired t-tests, and ANOVA. Each test had specific assumptions and yielded valuable information about the data.

## References

- [R in Action: Data Analysis and Graphics with R by Robert Kabacoff](#)
- [Basic Concepts of Probability and Statistics for Science and Engineering Students (Third Edition) by Dr. A. Parsian](#)
- [Statistical Methods by Nader Nematollahi](#)
- [Homogeneity of variances in R - DataNovia](#)
- [Basic Inferential Data Analysis Instructions](#)
- [One-Way ANOVA Test in R - STHDA](#)

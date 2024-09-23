# Preface & Chapter 1

## Preface

* Elements of Statistical Learning (ESL) - 2001, 2nd edition 2009
* An Introduction to Statistical Learning, With Applications in R (ISLR) - 2013, 2nd edition 2021
* An Introduction to Statistical Learning, With Applications in Python (ISLP) - 2023
* ISLR/ISLP - Advanced undergraduates + Master's students in statistics/quantitative fields

## Chapter 1 - Introduction

* Statistical Learning - Vast set of tools for *understanding* data.
   * Tools are either: Supervised or Unsupervised

* 3 Datasets:
   * Wage Data
   * Stock Market Data
   * Gene Expression Data

Wage Data
* Wages for a group of men from the Atlantic region of the United States
* Association between an employee's `age` and `education` as well as the calendar `year` and his `wage`
* Goal: Predict a *continuous* or *quantitative* output value - "Regression"

Stock Market Data
* Daily movements in the Standards & Poors 500 (S&P) stock index over 5 years from 2001-2005
* Goal: Predict a *non-numerical* or *categorical* or *qualitative* output value - "will index increase or decrease on a given day" - "Classification"

Gene Expression Data
* Previous 2 datasets have both input and output variables
* Class of problems for situations in which we only observe input variables, with no corresponding output
   * e.g., Marketing - Have demographic information for a number of current or potential customers. Goal: To understand what types of customers are *similar* to each other by grouping individuals according to their observed characteristics
* NCI60 dataset - 6,830 gene expression measurements for each of 64 cancer cell lines
* "Clustering"
* *principal components* - 6,830 expression measuremnets summarized down to two numbers (i.e., *dimensions*)


---

## A brief history of statistical learning
* Term is fairly new - concepts that underlie were developed long ago

1. Beginning of 19th century - *Least Squares* - Implementing the earliest form of what is now known as *linear regression*
   * First succesfully applied to problems in *astronomy*
   * Linear Regression - Used for predicting __quantitiative__ values (e.g., individual's salary)

1. Qualitative (e.g., whether a patient survives or dies) - *Linear Discriminant anlaysis* - 1936
1. 1940s - Alternative approch to Linear Discriminant Analysis - Logistic Regression
1. Early 1970s - *Generalized Linear Model* - Class of statisical learning methods that include both *linear* and *logistic* regression as special cases
1. Late 1970s - Many more techniques for learning from data were available
   * Almost exclusively linear methods, because fitting *non-linear* relationships was computationally difficult at the time
1. 1980s - Computing technology had improved sufficiently that non-linear methods were no longer computationally prohibitive
1. Mid 1980s - *Classifcation* and *Regression Trees* were developed. Followed shortly by *Generalied Additive Models*. Neural Networks gained popularity in the 1980s
1. 1990s - Support Vector Machines (SVMs)

__Statistical Learning has emerged as a new subfield in statistics -  Focused on supervised and unsupervised modeling & prediction__

1. 1990s - Field of statistical learning has expanded its audience. Increases in computational power generated a surge of interest in the field from non-statisticians who were eager to use cutting-edge statistical tools to analyze their data.

---
Purpose of ISL is to facilitate the transition statisical learning from academic to a mainstream field.
* ISL is not meant to replace ESL. Less technical & more accessible

ISL based on 4 premises:

1. __Many statistical learning methods are relevant and useful in a wide range of academic and non-academic disciplines, beyond just the statistical sciences__
1. __Statisical Learning should not be viewed as a series of black boxes__
   * No single approach will perform well in all possible applications
   * Need to understand internals to be able to select the best box (model, intutition, assumptions, and trade-offs behind each of the methods that we consider)
1. __While it is important to know what job is performed by each cog, it is not necessary to have the skills to construct the machine inside the box__
1. __We presume that the reader is interested in applying statistical learning methods to real-world problems__

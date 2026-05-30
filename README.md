# Data Science Statistics Projects

## Overview

This repository contains several data science projects focused on the implementation of statistics, probability distributions, hypothesis testing, A/B testing, and basic machine learning algorithms.

The projects in this repository were developed to strengthen fundamental concepts in mathematics for data science and apply them using Python. Each project demonstrates a different statistical or machine learning approach, starting from probability distribution simulation, Naive Bayes classification, and A/B testing analysis.

## Projects Included

### 1. Probability Distribution and Naive Bayes Classification

This project focuses on generating synthetic data using several probability distributions, including uniform distribution, Gaussian distribution, and binomial distribution.

The generated data is then used to build a simple Naive Bayes classification model. The classification task is designed to predict bird types based on several features such as wingspan, weight, singing frequency, and beak-to-head ratio.

Main topics covered:

* Uniform distribution
* Gaussian distribution
* Binomial distribution
* Synthetic data generation
* Naive Bayes classification
* Probability-based machine learning

### 2. A/B Testing for Article Recommendation System

This project implements A/B testing to evaluate whether adding an article recommendation feature can increase the number of articles read by users.

Users are divided into two groups:

* Origin group: users who do not see the recommendation feature
* Variant group: users who see the recommendation feature

The main metric used in this project is the number of articles read by each user. A hypothesis test is performed to determine whether the difference between the two groups is statistically significant.

Main topics covered:

* A/B testing
* Hypothesis testing
* Two-sample t-test
* User-level experiment analysis
* Statistical significance
* Experiment evaluation

### 3. A/B Testing for Software Feature Conversion Rate

This project focuses on A/B testing in a software development case study. The goal is to evaluate whether a new feature can improve user conversion rate.

The project includes sample size estimation, simulated experiment data generation, and two-proportion z-test analysis. The conversion rate between the origin group and the variant group is compared to determine whether the new feature has a statistically significant impact.

Main topics covered:

* A/B testing
* Sample size estimation
* Conversion rate analysis
* Two-proportion z-test
* Hypothesis testing
* Statistical decision making

## Dataset

The datasets used in these projects are generated synthetically through Python code. The data simulation process is designed based on probability distributions and statistical assumptions that match each case study.

## Tools and Libraries

* Python
* NumPy
* Pandas
* Matplotlib
* Seaborn
* SciPy
* Dataclasses

## Methodology

The workflow in this repository generally follows several main steps:

1. Define the case study and statistical problem.
2. Generate or prepare the dataset.
3. Apply statistical methods or machine learning algorithms.
4. Evaluate the result using appropriate metrics.
5. Interpret the output to support data-driven decision making.

Each project applies different methods depending on the problem. The first project focuses on probability distribution and classification, while the second and third projects focus on hypothesis testing through A/B testing.

## Results

The projects demonstrate how statistical concepts can be applied practically in data science problems. Probability distributions are used to generate synthetic data, Naive Bayes is applied for classification, and hypothesis testing is used to evaluate experiment results in A/B testing scenarios.

## Conclusion

This repository shows the implementation of fundamental statistical and mathematical concepts in data science using Python. The projects provide practical examples of how probability, classification, and hypothesis testing can be used to solve real-world analytical problems.

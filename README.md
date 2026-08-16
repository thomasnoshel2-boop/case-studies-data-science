# Case Studies in Data Science – Individual Task 1

## Student
Noshel Thomas  
RMIT University

## Project Overview
This repository contains the code and datasets used for my Individual Task 1 for Case Studies in Data Science.

The project examines the application of machine learning for the analysis of student performance and determination of students likely to be at risk of academic failure or dropout.

Machine learning analysis of two educational datasets is performed.

## Datasets

### 1. Student Performance Dataset
The Student Performance dataset includes details of 395 students enrolled in a course of mathematics. It covers academic, demographic, family, social and school-related attributes.

For the analysis purposes, student performance was divided into two classes: Pass and Fail, where Fail represents students who got failing grade (G3).

Source: UCI Machine Learning Repository – Student Performance Dataset.

### 2. Predict Students' Dropout and Academic Success Dataset
The dataset contains details of 4,424 students of higher education institutions. It covers academic, demographic and socioeconomic attributes and classifies students as Graduate, Dropout or Enrolled.

For the analysis, students were classified according to their dropout status.

Source: UCI Machine Learning Repository – Predict Students' Dropout and Academic Success.

## Machine Learning Methods

Following methods were used for analysis:

- majority class baseline model
- Decision Tree
- Support Vector Machine (SVM)

The training and testing sets consisted of 80% and 20% of data respectively.

Evaluation metrics used include:

- accuracy
- precision
- recall
- f1 score

Variables contributing to decision tree splits were investigated for feature importance of student performance and dropout.

## Repository Files

- `ACER_student_performance_analysis.ipynb` – Machine learning analysis of the Student Performance dataset.
- `student-mat.csv` – Mathematics Student Performance dataset.
- `ACER_student_dropout_analysis.ipynb` – Machine learning analysis of the Dropout and Academic Success dataset.
- `data.csv` – Dropout and Academic Success dataset.
- `README.md` – Description of the project and repository contents.

## How to run the analysis

Notebooks in this repository are written in Python language and can be accessed using Jupyter Notebook or Google Colab.

Open each notebook and execute cells one by one from top to bottom.

## Purpose

Repository supports the analysis performed for my Case Studies in Data Science Individual Task 1 submission.

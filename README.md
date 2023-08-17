# Credit_risk_resampling

# Table of Contents
* [Introduction](#Introduction)
* [Objective](#Objective)
* [Project Overview](#ProjectOverview)
* [Conclusion](#Conclusion)
* [Getting Started](#GettingStarted)
* [Dependencies](#Dependencies)

 ## Introduction
Welcome to the Credit Risk Analysis Repository! This platform serves as a crucial tool for financial institutions, particularly banks, engaged in lending activities. Here, we present a machine learning-based solution that effectively predicts credit risk, harnessing historical lending data from a peer-to-peer lending services provider.

## Objective
Our primary mission in this project is to construct a model with the capacity to accurately gauge the creditworthiness of borrowers. This endeavor involves tackling a classification challenge characterized by inherent data imbalance, where instances of healthy loans far outnumber risky ones. Our focus is on ensuring the model's adeptness in recognizing both loan categories.

## Project Overview
The project entails the development and comparison of two distinct machine learning models:

Logistic Regression Model trained on the original data.
Logistic Regression Model trained on resampled data utilizing the RandomOverSampler module from the imbalanced-learn library.
The workflow encompasses data division into training and testing sets, creation of a Logistic Regression model using the original dataset, prediction using this model, and replication of the process with a resampled training dataset.

## Outcome
A comprehensive Credit Risk Analysis Report encapsulates the findings of our investigation. This report features balanced accuracy scores, precision, and recall scores for both machine learning models. This compilation offers insights into model performance encompassing accuracy, false-positive rate, and the model's efficacy in identifying high-risk loans.

## Conclusion
The project culminates in a head-to-head comparison of the two models, accompanied by a well-founded recommendation. Our analysis discerns that the model trained on oversampled data outperforms in identifying high-risk loans. As a result, it emerges as the favored choice for implementation.

## Getting Started
To engage with this analysis, access the Jupyter Notebook containing the code. You can initiate the process by cloning this repository, installing the requisite Python libraries, and subsequently running the Jupyter Notebook.

## Dependencies
The successful execution of this project relies on the following dependencies:

Python
Pandas
NumPy
Scikit-learn
Imbalanced-learn

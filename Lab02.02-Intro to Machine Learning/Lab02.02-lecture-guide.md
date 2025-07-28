# Lab 2.02: Introduction to Machine Learning - Student Guide

## 📋 What You'll Learn Today
- [Overview](#overview)
- [Before We Start](#before-we-start)
- [Session Schedule](#session-schedule)
- [What to Expect](#what-to-expect)
- [Resources](#resources)

## Overview
Welcome to your first machine learning lab! Today you'll learn to build predictive models using real datasets. No prior ML experience required - we'll start from the basics and build up to practical applications.

**Duration:** 2 hours  
**What you need:** Basic Python and data skills from Lab 01 and Lab 2.01 respectively

## Before We Start

### 📚 What You Should Know
- Basic Python programming (variables, functions, loops)
- Working with pandas DataFrames
- Creating simple visualizations with matplotlib


### 🎯 Learning Goals
By the end of today, you'll be able to:
- **Predict continuous values** using linear regression (like predicting car emissions)
- **Classify categories** using logistic regression and decision trees (like predicting customer behavior)
- **Evaluate model performance** using metrics like accuracy and error rates
- **Apply ML to real problems** in automotive, telecommunications, and healthcare

## Session Schedule

### 🚀 Getting Started (10 minutes)
- Quick review of supervised learning concepts
- Library setup and verification
- Overview of today's datasets and problems

### 📈 Session 1: Simple Linear Regression (25 minutes)
**What we'll do:** Predict car CO2 emissions from engine size
- Learn the basics of linear relationships in data
- Build your first machine learning model
- Visualize predictions with scatter plots
- Measure how good your model is

**Dataset:** Canadian vehicle fuel consumption data  
**Real-world application:** Environmental impact assessment

### 📊 Session 2: Multiple Linear Regression (25 minutes)  
**What we'll do:** Improve predictions using multiple car features
- Use multiple factors to make better predictions
- Handle different types of data (numbers and categories)
- Compare feature importance
- Understand when models make mistakes

**Dataset:** Extended automotive data with make, model, vehicle class  
**Real-world application:** Automotive industry analytics

### 🎯 Session 3: Logistic Regression (25 minutes)
**What we'll do:** Predict if customers will leave their phone company
- Switch from predicting numbers to predicting categories
- Understand probability and decision-making
- Evaluate classification performance
- Interpret results for business decisions

**Dataset:** Telecommunications customer churn data  
**Real-world application:** Customer retention strategy

### 🌳 Session 4: Decision Trees (25 minutes)
**What we'll do:** Recommend drugs based on patient health
- Learn how computers make human-like decisions
- Handle multiple categories (5 different drugs)
- Visualize decision-making process
- Apply ML to healthcare decisions

**Dataset:** Drug prescription based on patient parameters  
**Real-world application:** Medical decision support

### 🎉 Wrap-up (5 minutes)
- Compare different approaches you learned
- Discuss when to use each method
- Q&A and next steps


### 📊 Real Datasets You'll Work With

| Dataset | Problem Type | What You'll Predict | Why It Matters |
|---------|--------------|-------------------|----------------|
| **Car Emissions** | Regression | CO2 emissions from car features | Environmental policy |
| **Customer Churn** | Classification | Will customer leave? (Yes/No) | Business strategy |
| **Drug Prescription** | Multi-class | Which of 5 drugs to prescribe | Healthcare decisions |

### 🔍 Skills You'll Gain

**Technical Skills:**
- Using scikit-learn for machine learning
- Model training with `.fit()` and prediction with `.predict()`
- Performance evaluation (MSE, accuracy, confusion matrix)
- Data preprocessing for ML

**Practical Skills:**
- Choosing the right algorithm for your problem
- Interpreting model results
- Applying ML to real-world scenarios

## Resources

### 📓 Today's Notebooks
| Notebook | Focus | Dataset |
|----------|--------|---------|
| [Simple Linear Regression](Scripts/Lab02-03.Simple-Linear-Regression.ipynb) | **Your first ML model** | Car fuel data |
| [Multiple Linear Regression](Scripts/Lab02-04.Mulitple-Linear-Regression.ipynb) | **Complex predictions** | Extended car data |
| [Logistic Regression](Scripts/Lab02-05.Logistic-Regression.ipynb) | **Classification basics** | Customer churn |
| [Decision Trees](Scripts/Lab02-06.Decision-tree-classifier-drug-pred.ipynb) | **Interpretable decisions** | Medical prescriptions |

### 📚 Additional Help
- [Scikit-learn Beginner Guide](https://scikit-learn.org/stable/getting_started.html)
- [Machine Learning Glossary](https://developers.google.com/machine-learning/glossary)

## 🗂️ Navigation
- [← Previous: Lab 2.01 - Data Fundamentals](../Lab02.01-Data%20Fundemantals/Lab02.01-lecture-guide.md)
- [← Back to Main Course](../README.md)
- [→ Next: Lab 3 - Fairness with COMPAS](../Lab03-Fairness%20with%20COMPAS/Lab03-lecture-guide.md)

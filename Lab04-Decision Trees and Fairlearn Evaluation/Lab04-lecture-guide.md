# Lab 4: Advanced Decision Trees and ML Fairness - Lecture Guide

## 📋 Table of Contents
- [Overview](#overview)
- [Lab Schedule](#lab-schedule)
- [Learning Objectives](#learning-objectives)
- [Quick Links](#quick-links)

## Overview
Comprehensive ML fairness analysis using the COMPAS recidivism dataset, covering decision trees, fairness metrics, and multiple algorithm comparison.

## Lab Schedule

### Session 1: COMPAS Dataset & Ethics (25 minutes)
- Load and clean COMPAS recidivism dataset 
- Understand criminal justice ML implications

### Session 2: Decision Tree Modeling (30 minutes)
- Train decision trees for recidivism prediction
- Evaluate performance vs. original COMPAS algorithm

### Session 3: Fairness Analysis (35 minutes)
- Implement FairLearn library
- Calculate fairness metrics: Demographic Parity, False Positive Rate, Equalized Odds
- Visualize disparities and trade-offs

### Session 4: Multi-Algorithm Comparison (25 minutes)
- Compare Random Forest, SVM, and KNN
- Evaluate accuracy vs. fairness across models

## Learning Objectives
Students will learn to:
- **Analyze** COMPAS criminal justice dataset with ethical context
- **Build** decision tree labifiers and compare with benchmarks  
- **Assess** ML fairness using FairLearn metrics and visualizations
- **Compare** multiple algorithms (Random Forest, SVM, KNN) for performance and fairness
- **Understand** real-world impact of algorithmic bias in criminal justice

## Key Concepts 

| Concept | Description |
|---------|-------------|
| **COMPAS Dataset** | Criminal risk assessment data for recidivism prediction |
| **FairLearn** | Microsoft's toolkit for fairness assessment in ML |
| **Demographic Parity** | Equal positive prediction rates across protected groups |
| **False Positive Rate** | Rate of incorrect positive predictions by group |
| **Equalized Odds** | Equal true/false positive rates across groups |
| **Feature Scaling** | Normalizing features for algorithms like SVM |
| **Ensemble Methods** | Random Forest using multiple decision trees |
| **Model Comparison** | Systematic evaluation across multiple algorithms |

## 🔗 Quick Links

| Resource | Description | Local File | Google Colab |
|----------|-------------|------------|--------------|
| Student Exercises | Guided exercises with TODO sections | [📁 COMPAS_exercises.ipynb](./Exercises/COMPAS_exercises.ipynb) | [☁️ Open in Colab](https://colab.research.google.com/drive/1dmQ9pB5rwUuoWN8Wu_Fi6qf2I67fb6Us?usp=sharing) |
| Complete Solutions | Full implementations with explanations | [📁 COMPAS_solutions.ipynb](./Exercises/COMPAS_solutions.ipynb) | [☁️ Open in Colab](https://colab.research.google.com/drive/1HCdkIKqo3KI1FBLyDAoHZPA2s84swrQu?usp=sharing) |

### 📖 Key Libraries Used
- **pandas**: Data manipulation and analysis
- **scikit-learn**: Machine learning algorithms and metrics
- **fairlearn**: Fairness assessment and mitigation
- **matplotlib/seaborn**: Data visualization

### 🗂️ Navigation
- [← Back to Main Course](../README.md)
- [← Previous: Lab 3 - ML Fairness](../lab3-ml-fairness/lab3-lecture-guide.md)
- [→ Next: Lab 5 - Differential Privacy](../lab5-differential-privacy/lab5-lecture-guide.md)




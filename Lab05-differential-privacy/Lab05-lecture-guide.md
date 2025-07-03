# Lab 5: Differential Privacy - Lecture Guide

## 📋 Table of Contents
- [Lab Schedule](#lab-schedule)
- [Learning Objectives & Key Concepts](#learning-objectives--key-concepts)
- [Quick Links](#quick-links)

## Overview
Introduction to differential privacy concepts, de-identification attacks, and privacy-preserving machine learning techniques.

## Lab Schedule

### Session 1: Differential Privacy Fundamentals (30 minutes)
**Core Concepts and Theory**
- **Tutorial:** `Census/census_tutorial.ipynb` | [📁 Local File](./Exercises/Census/census_tutorial.ipynb) | [☁️ Google Colab](https://colab.research.google.com/drive/1h0ZOYBOzeEAWhKg2nvDtgRFO9CZr4ddy?usp=sharing)
- Based on [Programming DP Chapter 1](https://programming-dp.com/ch1.html)
- De-identification
- Re-identification
- Identifying information / personally identifying information
- Linkage attacks
- Aggregation and aggregate statistics
- Differencing attacks

### Session 2: Census Dataset Exercise (30 minutes)
**De-identification Attacks and Basic DP**
- **Exercise:** `Census/census_exercises.ipynb` | [📁 Local File](./Exercises/Census/census_exercises.ipynb) | [☁️ Google Colab](https://colab.research.google.com/drive/15e682dGaOVC_uwSvSJaqfMR9kOFQFBys?usp=sharing)
- Demonstrate re-identification attacks on census data
- Implement basic differential privacy mechanisms
- Compare results with and without privacy protection

### Session 3: Sleep Dataset Exercise (30 minutes)
**Practical Differential Privacy Implementation**
- **Exercise:** `Sleep/differentialPrivacy_exercises.ipynb` | [📁 Local File](./Exercises/Sleep/differentialPrivacy_exercises.ipynb) | [☁️ Google Colab](https://colab.research.google.com/drive/1xQI3AvuB6UopswqcC0HKiFfHrV7GavzB?usp=sharing)
- Based on [Differential Privacy for Beginners](https://towardsdatascience.com/a-differential-privacy-example-for-beginners-ef3c23f69401)
- Hands-on noise addition mechanisms
- Understand the impact of different privacy parameters
- Privacy-preserving data analysis


## Learning Objectives & Key Concepts
By the end of this lab, students should be able to:

### 🔍 Privacy Attack Techniques
- Perform **linkage attacks** using auxiliary information to re-identify individuals
- Execute **differencing attacks** on aggregate statistics
- Demonstrate how **aggregation** can still leak individual information
- Understand why traditional **de-identification** methods fail

### 🛡️ Differential Privacy Fundamentals  
- Define **differential privacy** and its mathematical framework
- Explain the **privacy-utility trade-off** in data analysis
- Work with **epsilon (ε)** and **delta (δ)** privacy parameters
- Implement **noise addition mechanisms** (Laplacian noise)

### 🔧 Practical Implementation
- Use **PyDP** library for differential privacy algorithms
- Apply **BoundedSum**, **BoundedMean**, **Count**, and **Max** functions
- Implement the **randomized response** technique for sensitive surveys
- Compare privacy-preserving vs. non-private analysis results

### 📊 Real-world Applications
- Understand **personally identifiable information (PII)** vulnerabilities  
- Recognize the limitations of **anonymization** and **pseudonymization**
- Apply differential privacy to **survey data** and **statistical queries**
- Connect privacy techniques to **regulatory compliance** (GDPR, CCPA)

## 🔗 Quick Links

### 📚 Exercise Files
| Exercise | Local File | Google Colab |
|----------|------------|--------------|
| Census Tutorial | [📁 census_tutorial.ipynb](./Exercises/Census/census_tutorial.ipynb) | [☁️ Open in Colab](https://colab.research.google.com/drive/1h0ZOYBOzeEAWhKg2nvDtgRFO9CZr4ddy?usp=sharing) |
| Census Exercises | [📁 census_exercises.ipynb](./Exercises/Census/census_exercises.ipynb) | [☁️ Open in Colab](https://colab.research.google.com/drive/15e682dGaOVC_uwSvSJaqfMR9kOFQFBys?usp=sharing) |
| Sleep Exercises | [📁 differentialPrivacy_exercises.ipynb](./Exercises/Sleep/differentialPrivacy_exercises.ipynb) | [☁️ Open in Colab](https://colab.research.google.com/drive/1xQI3AvuB6UopswqcC0HKiFfHrV7GavzB?usp=sharing) |

### 📖 Reference Materials
- [Programming Differential Privacy - Chapter 1](https://programming-dp.com/ch1.html)
- [Differential Privacy for Beginners](https://towardsdatascience.com/a-differential-privacy-example-for-beginners-ef3c23f69401)

### 🗂️ Navigation
- [← Back to Main Course](../README.md)
- [← Previous: Lab 4 - Advanced Trees](../lab4-advanced-trees/lab4-lecture-guide.md)
- [→ Next: Lab 6 - Regression & LLM](../lab6-regression-llm/lab6-lecture-guide.md)








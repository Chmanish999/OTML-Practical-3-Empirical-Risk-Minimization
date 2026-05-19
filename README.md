# OTML Practical 3: Empirical Risk Minimization (ERM)

## 1. Aim

The aim of this practical is to understand the concept of Empirical Risk Minimization (ERM) and implement it using a simple Music Genre Recommendation System.

In this practical, students train a supervised machine learning model and calculate how prediction performance is related to empirical risk. The practical helps students understand that machine learning models try to minimize prediction error on training or testing data.

---

## 2. Course and Module Mapping

**Course:** A8751 – Optimization Techniques in Machine Learning  
**Module:** Module 1 – Model Fitting and Error Measurement  
**Practical Topic:** Empirical Risk Minimization using a Music Genre Recommendation System

This practical is mapped with Module 1 of OTML, where students study model fitting, error measurement, empirical risk, prediction accuracy, and optimization-based learning.

---

## 3. Theory Background

Empirical Risk Minimization, commonly called ERM, is one of the most important principles in machine learning.

In machine learning, **risk** means prediction error or loss. The true risk is the expected error of a model on the complete real-world data distribution. However, in practice, we do not have access to the complete data distribution. We only have a finite training dataset.

Therefore, we calculate error on the available dataset. This is called **empirical risk**.

Empirical risk means the average loss calculated over the available training examples.

In simple terms:

```text
Empirical Risk = Average prediction error on available data

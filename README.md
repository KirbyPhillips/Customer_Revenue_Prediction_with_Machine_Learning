# Predicting_Customer_Revenue_with_Machine_Learning
A machine learning analysis of ~2,000 customer records, using customer behaviour and engagement data to predict revenue with 65.9% explanatory power and support targeted marketing and retention decisions.

### Note: 

This repository outlines the full analytical and technical process used to predict customer revenue, from Python-based exploratory data analysis and data preparation through to feature engineering and regression-based machine learning modelling. Key findings, model performance, and potential business value and financial impact are provided throughout the project.

## Table of Contents

This repository presents the end-to-end process used to explore customer revenue and develop predictive machine learning models, from understanding the business problem and data through to model evaluation and potential business impact.

1. [Project Overview](#project-overview)
2. [Business Question](#business-question)
3. [The Dataset](#the-dataset)
4. [Exploratory Data Analysis](#exploratory-data-analysis)
5. [Data Preparation & Feature Engineering](#data-preparation--feature-engineering)
6. [Predictive Modelling](#predictive-modelling)
7. [Model Evaluation](#model-evaluation)
8. [Key Findings](#key-findings)
9. [Business Value & Financial Impact](#business-value--financial-impact)
10. [Technical Skills Demonstrated](#technical-skills-demonstrated)
11. [Tools](#tools)
12. [Project Context](#project-context)
---

## 1. Project Overview

Top Chef is a gourmet meal-delivery business with approximately 2,000 customer records containing purchasing behaviour, engagement, and account-level information. While this data captured how customers interacted with the business, it did not clearly show which behaviours were associated with higher revenue or how customer data could be used to predict revenue potential.

As a result, the business needed to understand:

- Which customer behaviours and engagement patterns are associated with revenue?
- How effectively can customer-level data be used to predict customer revenue?
- How could these predictions support more targeted marketing and retention decisions?

This project addresses that gap through exploratory data analysis, feature engineering, and machine learning regression modelling to predict customer revenue and demonstrate how these insights could support more informed customer and commercial decisions.

---

## 2. The Dataset

The analysis uses a dataset of approximately **2,000 Top Chef customers**, with each record representing an individual customer. The data includes information on customer purchasing behaviour, engagement with Top Chef's services, customer interactions and account characteristics.

| Data Area | Examples |
|---|---|
| Purchasing Behaviour | Meal orders, order size and cancellations |
| Customer Engagement | Videos, feedback, photos and cooking classes |
| Customer Interactions | Customer service and survey engagement |
| Account Characteristics | Customer and email-domain information |
| **Target Variable** | **REVENUE** |

The objective was to explore how these customer characteristics relate to revenue and use them to develop predictive models.

---

## 3. Exploratory Data Analysis

The analysis began by examining the dataset structure, variable types, descriptive statistics, missing values and the distribution of the target variable, `REVENUE`. Customer behaviour and engagement variables were then explored to identify patterns and relationships that could inform the predictive modelling stage.

### Revenue Distribution

The distribution of `REVENUE` was examined to understand how customer revenue was distributed across the dataset.

`REVENUE` was **right-skewed**, indicating that most customers generated relatively lower levels of revenue, while a smaller group generated substantially higher revenue.

> **Key Insight:** Customer revenue was unevenly distributed, with a relatively small group of higher-value customers generating substantially more revenue than the majority.

---



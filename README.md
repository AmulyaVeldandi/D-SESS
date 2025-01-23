# Quantitative Analysis of Side Effect Severity using the D-SESS Scale

This repository contains the code, data, and documentation for the research study titled **"Quantitative Analysis of Side Effect Severity using the D-SESS Scale: An Observational Study with Analytical Techniques"**, authored by Vijay Kumar Gaddam, Amulya Veldandi, Akhila Siri Godana, Surya Rao Sripathi, and Timothy Gudisa.

The study introduces the **Drug Side Effect Severity Scale (D-SESS)**, a novel quantitative metric designed to assess and categorize the severity of drug side effects using natural language processing (NLP) and machine learning techniques.

---

## Table of Contents

1. [Overview](#overview)
2. [Features](#features)
3. [Dataset](#dataset)
4. [Methods](#methods)
5. [Results](#results)
6. [Setup](#setup)
7. [Authors and Acknowledgment](#authors-and-acknowledgment)
8. [License](#license)

---

## Overview

The D-SESS scale provides a systematic and quantitative method to classify drug side effects into mild, moderate, and severe categories. It employs clustering and predictive modeling to facilitate a deeper understanding of drug safety.

This repository includes:

- Code for preprocessing the dataset.
- Algorithms for clustering and predictive modeling.
- Analytical results and visualizations.

---

## Features

- **Data Preprocessing**:
  - Tokenization of drug side effects.
  - Categorization of side effects into severity levels.
  
- **D-SESS Development**:
  - Quantitative scale calculation based on severity levels.
  - Inter-Rater Reliability (IRR) assessment.

- **Clustering Models**:
  - Algorithms: K-Means, DBSCAN, Agglomerative, Mean Shifting, BIRCH, and Affinity Propagation.

- **Prediction Models**:
  - Algorithms: Random Forest, Logistic Regression, and Support Vector Machine.

---

## Dataset

- The dataset was scraped from [Drugs.com](https://www.drugs.com) and includes columns such as:
  - `drug name`, `medical condition`, `side effects`, `rx_otc`, `alcohol`, `rating`.
- Features such as prescription status and alcohol interactions were encoded numerically for analysis.
- The scraped dataset  is obtained from Kaggle. https://www.kaggle.com/datasets/jithinanievarghese/drugs-side-effects-and-medicalcondition 


---

## Methods

### 1. Data Preprocessing
- NLP techniques for tokenization and normalization.
- Grouping of synonyms for consistent analysis.

### 2. Clustering Models
- Evaluation metrics: Homogeneity, Completeness, V-Measure, and Silhouette Scores.
- Clustering approaches to categorize drugs based on D-SESS scores.

### 3. Prediction Models
- Use of supervised learning models to predict drug cluster assignments.

---

## Results

- The Agglomerative clustering model demonstrated the best performance.
- Predictive models (Random Forest and Logistic Regression) achieved high accuracy (0.99 and 0.98, respectively).
- Results were visualized through scatter plots and tables for better interpretability.

---

## Setup

### Requirements

- Python 3.8+
- Libraries:
  - `numpy`
  - `pandas`
  - `scikit-learn`
  - `matplotlib`
  - `seaborn`
  - Additional NLP libraries as needed.

# Authors and Acknowledgment
Authors:

Amulya Veldandi
Vijay Kumar Gaddam
Akhila Siri Godana
Surya Rao Sripathi
Timothy Gudisa

Acknowledgment:
Special thanks to Dr. Saptarshi Purkayastha for his guidance and support throughout this research.





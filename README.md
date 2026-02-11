# Asteroid Hazard Analysis and Classification

## Overview
This project explores asteroid datasets to better understand orbital characteristics, identify potentially hazardous asteroids (PHAs), and analyze trajectory-based risk factors. The work combines data preprocessing, exploratory analysis, and machine learning modeling to study patterns that differentiate hazardous and non-hazardous asteroids.

---

## Project Goals
- Analyze asteroid orbital and physical characteristics
- Study Near-Earth Objects (NEOs) and Potentially Hazardous Asteroids (PHAs)
- Explore relationships between asteroid size, velocity, and proximity to Earth
- Develop machine learning models to classify asteroid hazard status
- Compare model performance across multiple classification techniques

---

## Data Sources
This project uses two publicly available datasets from Kaggle:

1. **NASA JPL Asteroid Dataset**  
   Source: https://www.kaggle.com/datasets/sakhawat18/asteroid-dataset  

2. **NASA Nearest Earth Objects Dataset**  
   Source: https://www.kaggle.com/datasets/sameepvani/nasa-nearest-earth-objects  

---

## Dataset Construction
The final working dataset was created by merging both datasets using the asteroid `id` field.

Processing steps included:
- Removing redundant or non-informative columns
- Handling missing values using statistical imputation
- Encoding categorical variables
- Creating filtered subsets for:
  - Near-Earth Objects (NEO)
  - Potentially Hazardous Asteroids (PHA)

---

## Methods and Analysis

### Exploratory Data Analysis
The exploratory analysis focused on:

- Orbital distribution and asteroid belt patterns
- Inclination and eccentricity comparisons across asteroid classes
- Hazard threshold analysis using MOID and absolute magnitude
- Velocity and miss distance relationship analysis
- Clustering analysis based on asteroid physical characteristics

---

### Machine Learning Models
Several classification models were trained and evaluated:

- Decision Tree
- AdaBoost
- K-Nearest Neighbors
- Logistic Regression
- Voting Classifier (Ensemble Model)

The ensemble Voting Classifier achieved the strongest overall performance.

---

## Key Findings
- Hazard classification strongly correlates with Minimum Orbit Intersection Distance (MOID) and absolute magnitude.
- Larger asteroids tend to exhibit higher velocities in close-approach data.
- Ensemble models improved classification accuracy by combining multiple model strengths.
- Distinct orbital distribution patterns were observed across asteroid belt classifications.

---

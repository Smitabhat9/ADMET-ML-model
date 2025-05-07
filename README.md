**ADMET-Based Machine Learning Models for Pancreatic Cancer Drug Discovery**

**Overview**
This repository houses two complementary machine learning approaches aimed at predicting drug-likeness and key ADMET properties for pancreatic cancer drug screening:

ADMET Model: Utilizes molecular docking results along with SWISSADME predictions to evaluate drug candidates based on classical ADMET (Absorption, Distribution, Metabolism, Excretion, and Toxicity) properties.

ADMET + PaDDLE Model: Extends the baseline ADMET model by incorporating PaDDLE descriptors, offering enhanced feature representation and improved predictive insight.

Both models leverage state-of-the-art techniques and are designed to facilitate a comprehensive analysis, from data preprocessing and exploratory analysis to model training and evaluation.
**Key Components**

Data Processing: Extraction of molecular docking outputs and biomarker data.
Integration of SWISSADME predictions as additional drug-likeness indicators.

**Feature Engineering:**

ADMET Model: Focuses on traditional ADMET properties.

ADMET + PaDDLE Model: Augments the feature space with PaDDLE descriptors for improved accuracy.

**Exploratory Data Analysis (EDA)**: Visualizes property distributions, correlational patterns, and overall molecular characteristics.

Model Training & Evaluation: Compares multiple machine learning algorithms using metrics such as accuracy, R², and MSE to determine the best-performing strategy for each model.


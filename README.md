# Titanic-EDA
🚢 Titanic Survival Analysis – Expert EDA & Feature Engineering
📌 Project Overview

This project presents a deep exploratory data analysis (EDA) and feature engineering–driven approach to understand survival patterns in the Titanic dataset.
Instead of directly jumping into modeling, the focus is on statistical reasoning, visualization, and information theory, following industry best practices.

This repository is suitable for:

📊 Data Analysis Internships

🤖 Machine Learning Fundamentals

📈 Visualization-centric ML projects

🎯 Objectives

Perform expert-level exploratory data analysis

Extract high-signal features using domain intuition

Apply information-theoretic feature selection

Build interpretable foundations before modeling

🧠 Key Concepts Used

Exploratory Data Analysis (EDA)

Statistical Visualization

Information Theory (Mutual Information)

Feature Engineering

Handling Missing Data

Multicollinearity & Correlation Analysis

📂 Dataset

Source: Titanic Dataset (Kaggle)

Target Variable: Survived (Binary Classification)

🔍 Exploratory Data Analysis (EDA)
✔️ Univariate Analysis

Survival distribution

Passenger class imbalance

Gender-wise survival trends

✔️ Bivariate & Multivariate Analysis

Survival vs Gender / Class / Fare

KDE plots for continuous variables

Correlation heatmaps

Survival probability by Deck

✔️ Advanced Visualizations

KDE plots for density estimation

Boxplots & violin plots for distribution comparison

Countplots with percentage annotations

🧱 Feature Engineering (Core Strength of Project)
🚪 Cabin Analysis (Handled Professionally)

Cabin_Known: Binary indicator (missingness as signal)

Deck: Extracted from Cabin (A–G, Unknown)

Missing values treated as explicit uncertainty, not noise

🧮 Mathematical Feature Engineering

Binning (AgeGroup, FareBins)

Interaction Features

Ordinal Encoding where mathematically valid

🧪 Feature Selection (High-Math Focus)
🔹 Mutual Information (Information Theory)

Used to quantify non-linear dependency between features and survival outcome.

Why MI?

Model-agnostic

Captures non-linear relationships

Strong theoretical foundation

⚠️ Interval and categorical features handled carefully to meet sklearn assumptions.

🤖 Modeling (Minimal but Meaningful)

Models are used only after EDA clarity, not blindly.

Implemented:

Logistic Regression (Interpretability first)

Tree-based models (optional extension)

Focus:

Understanding why a model predicts

Feature contribution over raw accuracy

🛠️ Tech Stack

Python

Pandas, NumPy

Matplotlib, Seaborn

Scikit-learn

Jupyter Notebook

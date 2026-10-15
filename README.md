# EDA
```markdown
# Exploratory Data Analysis (EDA) & Data Cleaning

This repository contains Python-based data analysis notebooks demonstrating Exploratory Data Analysis (EDA), missing value treatment, data type casting, and feature cleaning using popular data science libraries (`pandas`, `numpy`, `matplotlib`, `seaborn`).

## Overview
The provided workflow covers two primary datasets to showcase standard preprocessing pipelines:
1. **Titanic Dataset**: Initial structural inspection (`info`, `describe`), shape verification, and missing value checks.
2. **Google Play Store Apps Dataset**: Data cleaning tasks including handling non-numeric review entries, converting app sizes from string annotations (Megabytes/Kilobytes) to numeric formats, stripping currency symbols and special characters from price/installs data, dropping duplicates, and separating numerical vs. categorical features.

## Requirements
To run this notebook locally or on Google Colab, ensure you have the following libraries installed:
```bash
pip install pandas numpy matplotlib seaborn

```

## Notebook Structure

* **Import Libraries**: Loads `pandas`, `numpy`, `matplotlib.pyplot`, `seaborn`, and suppresses warnings.
* **Data Loading & Inspection**: Reads CSV sources directly and executes initial data checks (`head`, `info`, `shape`, `describe`).
* **Data Cleaning & Manipulation**:
* Handling missing values (`isnull().sum()`).
* Cleaning mixed-type columns (e.g., parsing sizes, removing commas/dollar signs from `Installs` and `Price`).
* Type casting columns from `object` to `int` or `float`.
* Removing duplicates and categorizing numerical vs. categorical features.



```

```

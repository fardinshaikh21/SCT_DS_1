
# 📊 Task 1 - Exploratory Data Analysis (EDA) on Population Data

This project focuses on performing exploratory data analysis (EDA) using Python on a population dataset, possibly similar to the Titanic dataset structure. It includes insightful visualizations like bar charts and histograms to understand the **distribution of age groups** and **gender** in the dataset.

---

## 🎯 Objective

The objective of this project is to:
- Understand the distribution of demographic features
- Identify patterns in age and gender
- Prepare the dataset for future predictive modeling or statistical analysis

---

## 📂 Files

- `Task1 (1).ipynb` — Jupyter notebook that performs the analysis
- `standard_populations_19_age_groups.csv` — Dataset used for the visualizations

---

## 🧾 Dataset Description

The dataset includes standardized population figures grouped by age. It typically contains the following columns:

- `Age_Group`: Age range of individuals (e.g., 0–4, 5–9, ..., 85+)
- `Gender`: Male or Female (if available)
- `Population`: Count of individuals in each group

---

## 📊 Visualizations & EDA Tasks

The following analyses are performed in the notebook:

- ✅ **Bar Chart** showing the distribution of population across gender  
- ✅ **Histogram** for understanding the distribution of age groups  
- ✅ Checking for missing data and data types  
- ✅ Shape and sample preview of the dataset using `head()`, `shape`, and `info()`  
- ✅ Additional categorical analysis using Seaborn's `countplot` or `barplot`  

---

## 📦 Libraries Used

- `pandas` – for data manipulation
- `matplotlib.pyplot` – for visual plotting
- `seaborn` – for aesthetic statistical plots

### Installation:

```bash
pip install pandas
pip install matplotlib
pip install seaborn

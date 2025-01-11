# FIFA Players Data Analysis Project

---

## Table of Contents
- [Overview](#overview)
- [Dataset](#dataset)
- [Project Goals](#project-goals)
- [Methodology](#methodology)
- [Results](#results)
- [How to Run](#how-to-run)
- [File Structure](#file-structure)
- [Author](#author)

---

## Overview
This project demonstrates the process of exploratory data analysis (EDA) using Python and Pandas on a dataset of FIFA players. It focuses on uncovering patterns, relationships, and trends in the data through statistical summaries and visualizations.  

The project is divided into two main parts: data cleaning and preprocessing, followed by exploratory data analysis with tables and visualizations.

---

## Dataset
The dataset used is `FIFA_Players_Data.csv`, which contains detailed information about FIFA players, including attributes such as nation position, ball control, stamina, pace, and more.

---

## Project Goals
1. **Data Cleaning and Preprocessing**:  
   - Handle missing values through imputation or logical deletion.
   - Process columns with inconsistent or complex data formats to make them analysis-ready.  
   - Standardize data types for numeric analysis.

2. **Exploratory Data Analysis (EDA)**:  
   - Perform univariate, bivariate, and multivariate analyses.  
   - Generate statistical summaries and meaningful visualizations to identify insights and trends.  

---

## Methodology
### Step 1: Data Cleaning
- Handled missing values in columns like `joined`, `nation_position`, and `nation_jersey_number` using appropriate strategies.  
- Addressed inconsistencies in `skill_ball_control` and `power_stamina` columns by parsing and converting them into integers after performing the necessary arithmetic operations.  
- Dropped or imputed values for rows where the `nation_position` is `GK` and irrelevant for specific attributes like pace or shooting.

### Step 2: Exploratory Data Analysis
#### Univariate Analysis
- Generated bar charts and histograms to analyze individual variables and distributions.  

#### Bivariate Analysis
- Created scatter plots to explore relationships between continuous variables.  
- Used visualizations to analyze interactions between discrete and continuous variables.  
- Computed and visualized correlation matrices for numerical variables.

#### Multivariate Analysis
- Produced visualizations involving three or more variables to capture complex relationships and patterns.

---

## Results
### Key Outcomes
1. **Data Cleaning**: The dataset was cleaned and processed to ensure consistency and readiness for analysis. Missing values were handled logically, and complex data formats were simplified for ease of use.  
2. **EDA Insights**:  
   - Identified trends in player attributes like stamina, ball control, and performance across positions.  
   - Explored relationships between physical attributes and player performance.  
   - Generated engaging visualizations that highlight significant findings in the dataset.

---

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/fifa-players-eda.git

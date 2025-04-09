# 🏘️ Affordable Housing in Connecticut (2011–2022)

This project presents a comprehensive data analysis of affordable housing units across Connecticut towns from 2011 to 2022. The analysis leverages a publicly available dataset to explore trends, distributions, and correlations in housing assistance programs, providing insights for policy makers, urban planners, and researchers.

---

## 📊 Project Overview

The dataset contains yearly information about:

- Total housing units per town
- Government-assisted housing
- Tenant rental assistance
- CHFA/USDA single-family mortgages
- Deed-restricted units
- Total number of assisted units
- Percentage of affordable housing per town

### 🧠 Objectives:
- Understand affordable housing trends across years and towns.
- Identify towns with the highest and lowest affordable housing percentages.
- Explore the distribution and proportions of different housing assistance types.
- Perform correlation and clustering analysis to uncover hidden patterns.
- Model affordable housing percentage predictions using regression.

---

## 📁 Data

**Source:** [CT.gov – Affordable Housing by Town (2011–2022)]  
**File:** `Affordable_Housing_by_Town_2011-2022.csv`  
**Columns Include:**
- `Year`
- `Town`
- `2010 Census Units`
- `Government Assisted`
- `Tenant Rental Assistance`
- `Single Family CHFA/USDA Mortgages`
- `Deed Restricted Units`
- `Total Assisted Units`
- `Percent Affordable`

---

## 🔍 Analysis Performed

### ✅ Data Cleaning
- Handled missing values
- Verified and corrected data types

### 📈 Trend Analysis
- Year-over-year changes in total assisted units and percent affordable
- Time series plots per town

### 📊 Comparative Analysis
- Top and bottom 10 towns by affordable housing percentage
- Bar charts for visual comparison

### 📉 Correlation Analysis
- Heatmap showing relationships between variables

### 📦 Distribution & Proportional Analysis
- Histograms and boxplots for all housing types
- Proportional breakdowns of assistance programs over time

### 🔬 Clustering
- KMeans clustering to identify groups of towns with similar housing profiles

### 📈 Predictive Modeling
- Linear regression to predict percent affordable based on other variables

---

## 🛠️ Technologies Used

- Python (Pandas, NumPy)
- Matplotlib & Seaborn (Visualization)
- Scikit-learn (Clustering, Regression)
- Jupyter Notebook (Analysis environment)

---

## 📌 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/affordable-housing-ct.git
   cd affordable-housing-ct

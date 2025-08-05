# TASK_2_Elevate_Labs

# Titanic Dataset - Exploratory Data Analysis (EDA)

This project performs a comprehensive exploratory data analysis (EDA) on the Titanic dataset to understand key characteristics and relationships between features. The goal is to extract meaningful insights that could help in building predictive models or understanding survival trends.

## Dataset

The dataset contains information about passengers on the Titanic, including:
- Demographics (Age, Sex, etc.)
- Travel class and fare
- Family relationships aboard
- Survival outcome

## EDA Steps Performed

### 1. Summary Statistics
- Basic descriptive statistics like mean, median, standard deviation, and quartiles for numeric columns.

### 2. Histograms and Boxplots
- Distribution plots (histograms) and boxplots were created for:
  - Age
  - Fare
  - SibSp (Number of siblings/spouses aboard)
  - Parch (Number of parents/children aboard)
- These plots help detect skewness and outliers.

### 3. Correlation Matrix
- A heatmap of correlations between numeric features.
- Helps understand which features have linear relationships (e.g., Fare has some correlation with Survived).

### 4. Pairplot
- A multi-variable plot showing relationships and class separation across key features.
- Plots are color-coded by survival status for visual inference.

### 5. Inference Guide
- Added markdown guidance for interpreting visuals.
- Encourages spotting trends, anomalies, and patterns.

## Output

- 📓 `Titanic_EDA_Guide_Cleaned.ipynb` - The complete notebook with plots and commentary.

## Usage

To view and run the notebook:
```bash
jupyter notebook Titanic_EDA_Guide_Cleaned.ipynb

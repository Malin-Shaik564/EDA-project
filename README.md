# Exploratory Data Analysis (EDA)

## Project Overview

This project performs **Exploratory Data Analysis (EDA)** on a restaurant dataset to identify patterns, trends, and relationships among various features. Using Python visualization and data analysis libraries, the project explores restaurant ratings, cuisines, pricing, online delivery, table booking, city-wise distribution, and other key attributes.

The analysis provides meaningful insights that help understand customer preferences and restaurant characteristics before applying machine learning techniques.

---

## Objectives

* Load and inspect the dataset.
* Analyze data quality by checking missing and duplicate values.
* Generate statistical summaries.
* Visualize important features using graphs.
* Identify relationships between variables.
* Detect outliers in numerical data.
* Present key business insights from the dataset.

---

## Technologies Used

* Python 3.x
* Pandas
* NumPy
* Matplotlib
* Seaborn

---

## Libraries Required

Install the required libraries before running the project:

```bash
pip install pandas numpy matplotlib seaborn
```

---

## Dataset

The dataset is loaded from the following CSV file:

```text
dataset1.csv
```

Update the dataset path in the code according to your system if necessary.

---

## Workflow

### 1. Data Loading

* Reads the dataset using Pandas.
* Displays dataset shape, columns, data types, and sample records.

### 2. Data Quality Analysis

* Checks for missing values.
* Visualizes missing data using a heatmap.
* Detects duplicate records.

### 3. Statistical Summary

* Generates descriptive statistics for numerical features.
* Summarizes categorical features.

### 4. Data Visualization

The project creates several visualizations, including:

* Top 10 Cities by Number of Restaurants
* Distribution of Restaurant Ratings
* Online Delivery Availability
* Table Booking Availability
* Price Range Distribution
* Top 10 Most Popular Cuisines
* Correlation Heatmap
* Votes vs Aggregate Rating
* Average Cost for Two vs Rating
* Outlier Detection using Boxplots
* Online Delivery vs Rating
* Table Booking vs Rating
* Restaurants by Country Code

### 5. Insights Report

At the end of the analysis, the program displays:

* Total number of restaurants
* Total number of cities
* Highest-rated restaurant
* Most common city
* Most common cuisine
* Average restaurant rating
* Average cost for two people
* Maximum number of votes received

---

## Output

The program generates:

* Dataset overview
* Missing value analysis
* Statistical summaries
* Multiple charts and visualizations
* Correlation matrix
* Outlier detection plots
* Final EDA insights report

---

## Expected Outcome

After completing this project, users will be able to:

* Understand the structure and quality of the dataset.
* Identify important trends and patterns.
* Interpret relationships between variables.
* Detect missing values and outliers.
* Build a strong foundation for predictive modeling and machine learning.

---

## Project Structure

```text
Project Folder/
│
├── dataset1.csv
├── eda_analysis.py
├── README.md
```

---

## Future Enhancements

* Interactive dashboards using Plotly or Power BI.
* Geographic analysis using restaurant locations.
* Time-series analysis (if date information is available).
* Customer segmentation and clustering.
* Automated EDA report generation using profiling libraries.

---

## Conclusion

This project demonstrates a complete Exploratory Data Analysis (EDA) workflow using Python. It helps uncover hidden patterns, understand data distributions, identify relationships among variables, and generate valuable business insights. The analysis also prepares the dataset for future machine learning applications by ensuring data quality and providing a clear understanding of the underlying data.

---

**Author:** Shaik Malin

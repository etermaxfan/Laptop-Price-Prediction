# Laptop-Price-Prediction
An end-to-end Python project to analyse market specifications and predict laptop prices using Linear Regression
## PROJECT OVERVIEW
This project processes a dataset of laptop hardware specifications (RAM, CPU, Operating system...) to celan, transform and build a predictive regression model. The primary goal is to evaluate key feature relationships and forecast pricing trends accurately.

## Tech Stack and Libraries
* **Language:** Python
* **Environment:** Jupyter Notebook (`.ipynb`)
* **Data Manipulation:** Pandas, NumPy
* **Data Visualization:** Matplotlib, Seaborn
* **Machine Learning:** Scikit-Learn

## Key Features and Workflow
1. **Exploratory Data Analysis (EDA) & Multi-variable Visualization:** Analyzed relationships between CPU frequency, RAM, weight, operating system, and screen resolution against laptop prices in Euros using Seaborn and Matplotlib.
2. **Feature Engineering & Trend Analysis:** Identified price stepping behavior based on display resolution (`ScreenW`) and system categories.
3. **Model Training & Split:** Performed an 80/20 train-test split using Scikit-Learn to evaluate model generalization.
4. **Linear Regression & Evaluation:** Built and fitted a Linear Regression model to forecast laptop prices, measuring accuracy with the $R^2$ score metric and comparing predicted vs. actual values.

# Predicting Hazardous NEOs (Nearest Earth Objects)

This project analyzes a dataset of car listings to predict whether a vehicle is in hazardous condition based on various features. The dataset contains over 426,000 records. The project involves data preprocessing, exploratory data analysis (EDA), and model building using machine learning to predict a specified target variable.

## Overview

This project demonstrates skills in data cleaning, feature engineering, visualization, and predictive modeling. The objective is to build a reliable machine learning model capable of predicting the target label effectively.

---

## 🏗️ Project Structure

1. ### 📥 Import Libraries and Dataset

   Essential libraries for data manipulation, visualization, and machine learning are imported:
   - **numpy** for numerical operations.
   - **pandas** for data manipulation.
   - **matplotlib** and **seaborn** for data visualization.
   - **sklearn** for machine learning.

   **Dataset Details**:
   - Total Records: 426,880 entries
   - Columns: 26, including features like `price`, `year`, `manufacturer`, `model`, `condition`, `cylinders`, `fuel`, `odometer`, and `transmission`.
   - **Note**: Extract the dataset file from any provided compressed format before running the notebook.
   - **Dataset Link**: https://www.kaggle.com/datasets/austinreese/craigslist-carstrucks-data/data?authuser=0.

2. ### 🛠️ Data Preprocessing

   Data preprocessing steps include:
   - **Handling Missing Values**: Using `SimpleImputer` to fill missing data for crucial columns.
   - **Feature Scaling**: Normalizing numerical features.

3. ### 🔍 Exploratory Data Analysis (EDA)

   EDA is performed using `matplotlib` and `seaborn`:
   - **Histograms**: Displaying distributions of numerical variables (e.g., `price`, `year`).
   - **Correlation Heatmaps**: Revealing potential interactions between variables and identifying relevant features for the prediction.

   **Questions Answered in EDA**:
   - What is the distribution of cars by region?
   - What is the average price of cars by region?
   - What is the distribution of cars by manufacturer?
   - What is the average price of cars by manufacturer?
   - What are the top 20 most frequent car models?
   - What is the average price of the top 20 most frequent car models?
   - What is the distribution of cars by condition?
   - What is the average price of cars by condition?
   - What is the distribution of cars by number of cylinders?
   - What is the average price of cars by number of cylinders?
   - What is the distribution of cars by fuel type?
   - What is the average price of cars by fuel type?
   - What is the distribution of cars by title status?
   - What is the average price of cars by title status?
   - What is the distribution of cars by transmission type?
   - What is the average price of cars by transmission type?
   - What is the distribution of cars by type?
   - What is the average price of cars by type?
   - What is the distribution of cars by paint color?
   - Which paint color is most common for each car type?

## 📜 Instructions for Running the Project

### Clone this repository

```bash
git clone https://github.com/your-username/Car-Listing-Hazard-Prediction.git
```

### Extract the Dataset

Ensure you have extracted the dataset from any provided compressed format before running the notebook.

### Run the Jupyter Notebook

```bash
jupyter notebook "Mid-Course project ((Mohamed Mahmoud Elsayed)).ipynb"
```

---

## 📝 Requirements

- **Python 3.x**
- **pandas**
- **numpy**
- **matplotlib**
- **seaborn**
- **scikit-learn**

Install these with:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

---

## 🏁 Conclusion

This project provides a framework for predicting hazardous conditions based on vehicle listings. Initial models show promise, though future work could involve handling class imbalance more effectively to improve predictions for the hazardous class.

---

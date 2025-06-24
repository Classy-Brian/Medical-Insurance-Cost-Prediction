# Medical Cost Prediction using Linear Regression

## Overview

This project aims to predict individual medical insurance costs based on a number of personal factors. By analyzing a dataset of insurance beneficiaries, I built and evaluated a linear regression model to forecast healthcare charges.

*This project serves as a practical application of the skills learned in the "Supervised Machine Learning: Regression and Classification" course from Coursera and Stanford University.*

## Dataset

The dataset used for this analysis is the "Medical Cost Personal Datasets" from Kaggle. It contains information on 1,338 beneficiaries with the following features: age, sex, BMI, number of children, smoking status, and region.

- **Source:** [Medical Cost Personal Datasets on Kaggle](https://www.kaggle.com/datasets/mirichoi0218/insurance)

## Methodology

1.  **Exploratory Data Analysis (EDA):** Loaded, cleaned, and investigated the dataset to understand feature distributions and correlations using visualizations (e.g., histograms, scatter plots).
2.  **Data Preprocessing:** Converted categorical features (like `sex`, `smoker`, `region`) into a numerical format using one-hot encoding so they could be used by the model.
3.  **Model Training:** Split the data into training and testing sets. Trained a Linear Regression model using the Scikit-learn library on the training data.
4.  **Model Evaluation:** Assessed the model's performance on the unseen test set using key regression metrics, including R-squared (R²) and Root Mean Squared Error (RMSE).

## Technologies Used

- **Language:** Python
- **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
- **Environment:** Google Colab / Jupyter Notebook

## Results & Key Findings



## How to Run This Project

1.  Clone this GitHub repository to your local machine.
2.  Ensure you have the required libraries installed (Pandas, Scikit-learn, etc.).
3.  Open the `Medical_Cost_Prediction.ipynb` notebook in a Jupyter environment like Jupyter Lab or Google Colab.
4.  Run the cells sequentially to reproduce the analysis and results.

---

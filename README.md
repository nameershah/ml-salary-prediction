# Salary Prediction using Simple Linear Regression

A beginner-friendly machine learning project that predicts salary based on years of experience using Simple Linear Regression.

---

## Dataset

**Source:** [Salary Dataset - Simple Linear Regression](https://www.kaggle.com/datasets/abhishek14398/salary-dataset-simple-linear-regression) (Kaggle)

| Column | Type | Description |
|---|---|---|
| YearsExperience | float | Years of work experience |
| Salary | float | Annual salary in USD |

- 30 rows, 2 features
- No missing values

---

## Project Structure

```
ml-salary-prediction/
├── Simple_Linear_Regression_Salary_Dataset.ipynb
├── Salary_dataset.csv
└── README.md
```

---

## Notebook Walkthrough

| Cell | Description |
|---|---|
| Cell 1 | Install libraries |
| Cell 2 | Import dependencies |
| Cell 3 | Load and clean dataset |
| Cell 4 | Exploratory Data Analysis (EDA) |
| Cell 5 | Scatter plot visualization |
| Cell 6 | Correlation heatmap |
| Cell 7 | Prepare features and target |
| Cell 8 | Train model on full dataset |
| Cell 9 | Print regression equation |
| Cell 10 | Predictions |
| Cell 11 | Evaluate (MAE, MSE, RMSE, R²) |
| Cell 12 | Visualize training set |
| Cell 13 | Visualize test set |
| Cell 14 | Predict for a custom input |

---

## Model

**Algorithm:** Simple Linear Regression (`sklearn.linear_model.LinearRegression`)

```
Salary = 9449.96 × YearsExperience + 25792.20
```

**Sample Prediction:**
```python
model.predict([[6.8]])
# → $89,107.95
```

---

## Results

| Metric | Value |
|---|---|
| R² Score | ~0.96 |
| RMSE | ~5,592 |
| MAE | ~3,426 |

---

## Libraries Used

```
pandas
numpy
matplotlib
seaborn
scikit-learn
```

---

## How to Run

1. Open the notebook in Google Colab using the badge below
2. Upload `Salary_dataset.csv` when prompted
3. Run all cells: **Runtime → Run All**

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/nameershah/ml-salary-prediction/blob/main/Simple_Linear_Regression_Salary_Dataset.ipynb)

---

## Author

**Muhammad Nameer Shah** 
[GitHub](https://github.com/nameershah) · [LinkedIn](https://linkedin.com/in/muhammad-nameer-shah)

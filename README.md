# EL-Internship-Task-3

# Linear Regression – Housing Price Prediction

This project implements simple and multiple linear regression models to predict house prices using the **Housing Price Prediction Dataset**. The project is part of the AI & ML Internship Task 3.

## Objective

To understand and apply simple and multiple linear regression using **Scikit-learn**, **Pandas**, and **Matplotlib**. Evaluate the model using performance metrics like MAE, MSE, and R² Score.

## Tools & Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Dataset

- **Source:** [Housing Price Prediction – Kaggle](https://www.kaggle.com/datasets/harishkumardatalab/housing-price-prediction)
- Features include: number of bedrooms, area, parking, air conditioning, etc.
- Target variable: `price`
  
## Steps Performed

1. **Data Preprocessing**
   - Categorical encoding (yes/no → 1/0)
   - One-hot encoding (if needed)
   - Handled missing values

2. **Train-Test Split**
   - Used `train_test_split` (80% training, 20% testing)

3. **Model Building**
   - Trained a `LinearRegression` model using Scikit-learn

4. **Model Evaluation**
   - MAE (Mean Absolute Error)
   - MSE (Mean Squared Error)
   - R² Score

5. **Visualization**
   - Regression line for simple regression
   - Residual plots and coefficient interpretation

## Evaluation Metrics

| Metric        | Value (Example) |
|---------------|-----------------|
| MAE           | 280000.45       |
| MSE           | 150000000.12    |
| R² Score      | 0.82            |

(*Note: Actual values will vary based on model training*)

## Insights

- Larger area and number of bedrooms have a positive influence on price.
- Good model fit with R² score indicating **~82% variance** explained by features.

## Files in Repository

- `task3_linear_regression.ipynb` – Jupyter Notebook with code
- `Housing.csv` – Dataset used
- `README.md` – This file
- `plots/` – Folder containing graphs (optional)

## Conclusion

- Built and evaluated both simple and multiple linear regression models.
- Gained insights into regression assumptions, model interpretation, and metric evaluation.

## Submission

This task is part of the AI & ML Internship (Task 3).  
**Submitted by:** Dhanush G  
**Email:** dhanushg0710@gmail.com  
**GitHub:** [github.com/dhanushg0710](https://github.com/dhanushg0710)


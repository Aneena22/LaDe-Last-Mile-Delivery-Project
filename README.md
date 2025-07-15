 LaDe - Last Mile Delivery Prediction
 Author:Aneena Jomy

This is a Data Science project using the **LaDe (Last Mile Delivery)** dataset to analyze, visualize, and predict delivery time based on courier and location features.

---

##  Project Overview

The goal of this project is to:
- Understand key delivery patterns
- Clean and preprocess the dataset
- Perform feature engineering and visualization
- Train a regression model to predict actual delivery time
- Evaluate model performance using metrics like MAE, RMSE, and R²

---

## Dataset

- Source: [Cainiao LaDe Dataset (HuggingFace)](https://huggingface.co/datasets/Cainiao-AI/LaDe)
- Format: CSV
- Rows: 11,000+
- Columns: 15

---

##  Preprocessing Steps

- Missing value handling
- Date & time transformation (hour, weekday)
- Label Encoding & One-hot Encoding
- Feature Scaling using StandardScaler

---

## Exploratory Data Analysis

Visualizations include:
- Delivery time distribution
- Hourly delivery patterns
- Courier-wise performance
- Heatmaps & boxplots

---

## Model Training

- Model Type: **Regression**
- Algorithms Tried: Linear Regression, RandomForestRegressor
- Evaluation Metrics:
  - R² Score
  - Mean Absolute Error (MAE)
  - Root Mean Squared Error (RMSE)

---

## Final Result

- Best Model: Random Forest
- MAE:0.89
- RMSE:1.12
- R² Score:0.91

---

## Conclusion

This project shows how machine learning can be used in logistics to optimize last-mile delivery by predicting delivery times accurately and helping dispatchers make better decisions.

---

## Tools Used

- Python
- Google Colab
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn

- ## Author
- 
- Aneena Jomy
- datascience student
- Email :aneenajomy22@gmail.com


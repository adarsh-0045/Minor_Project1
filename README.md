# 🛒 Store Sales Prediction Using Supervised Machine Learning

## 📌 Project Overview

Accurate sales prediction plays a vital role in the retail industry by helping businesses optimize inventory, improve promotional strategies, and make informed business decisions.

This project develops and compares two supervised machine learning models—**Linear Regression** and **Decision Tree Regressor**—to predict daily store sales using historical sales records along with store information, promotional activities, holidays, and oil prices.

---

# 🎯 Problem Statement

Retail companies generate large amounts of transactional data every day. Predicting future sales helps businesses:

- Optimize inventory management
- Reduce product shortages
- Improve promotional planning
- Increase profitability
- Support data-driven business decisions

The objective of this project is to build a supervised machine learning model capable of predicting store sales using historical retail data.

---

# 🎯 Objectives

- Perform data preprocessing and cleaning
- Merge multiple retail datasets
- Conduct Exploratory Data Analysis (EDA)
- Engineer meaningful features
- Train supervised learning models
- Compare model performance
- Select the best-performing model

---

# 📂 Dataset

The datasets used in this project are from the Kaggle **Store Sales - Time Series Forecasting** competition.

Datasets:

- train.csv
- stores.csv
- oil.csv
- holidays_events.csv

Dataset Link:

https://www.kaggle.com/competitions/store-sales-time-series-forecasting

---

# 📁 Project Structure

```
MINORPROJECT-1/
│
├── data/
│   ├── train.csv
│   ├── stores.csv
│   ├── oil.csv
│   └── holidays_events.csv
│
├── model/
│   └── DecisionTreeModel.pkl
│
├── notebook/
│   └── Store_Sales_Prediction.ipynb
│
├── results/
│   ├── sales_distribution.png
│   ├── monthly_sales.png
│   ├── promotion_vs_sales.png
│   ├── correlation_heatmap.png
│   ├── actual_vs_predicted.png
│   ├── residual_plot.png
│   └── evaluation_metrics.csv
│
├── README.md
└── .gitignore
```

---

# ⚙️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Joblib
- Colab Notebook

---

# 🔍 Data Preprocessing

The following preprocessing techniques were applied:

- Handling missing values
- Merging multiple datasets
- Date conversion
- Feature engineering
- Label Encoding
- Duplicate checking

---

# 📊 Exploratory Data Analysis

Several visualizations were created to understand the dataset:

- Sales Distribution
- Monthly Sales Trend
- Store-wise Sales
- Product Family Analysis
- Promotion vs Sales
- Correlation Heatmap
- Boxplots
- Outlier Detection
- Sales by Day of Week

---

# 🤖 Machine Learning Models

The following supervised learning algorithms were implemented:

## 1. Linear Regression

Used as the baseline regression model.

## 2. Decision Tree Regressor

Captures nonlinear relationships between features and target values.

---

# 📈 Evaluation Metrics

The models were evaluated using:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

---

# 🏆 Results

The performance of both models was compared.

| Model | MAE | MSE | RMSE | R² Score |
|-------|-----|-----|------|-----------|
| Linear Regression | 279.169784  | 408348.064457 | 639.021177 | 0.043339 |
| Decision Tree | 38.469661 | 64967.874213 | 254.887964 | 0.847796 |

The Decision Tree Regressor achieved better prediction performance and was selected as the final model.

---

# 📷 Sample Outputs

The **results/** folder contains:

- Sales Distribution Plot
- Monthly Sales Trend
- Correlation Heatmap
- Actual vs Predicted Plot
- Residual Distribution
- Evaluation Metrics

---

# 🚀 Installation

Clone the repository:

```bash
git clone Repository link
```

Move to the project directory:

```bash
cd MinorProject1
```


Launch Colab Notebook:

```bash
colab notebook
```

---

# ▶️ How to Run

1. Download the datasets from Kaggle.
2. Place them inside the **data/** folder.
3. Open the notebook.
4. Run all cells sequentially.
5. View evaluation metrics and generated graphs.

---

# 📌 Conclusion

This project demonstrates the application of supervised machine learning techniques to retail sales forecasting.

Among the implemented models, the Decision Tree Regressor provided better predictive performance and was selected as the final model.

The project also highlights the importance of preprocessing, feature engineering, and exploratory data analysis in improving model performance.

---

# 🔮 Future Scope

Possible improvements include:

- Hyperparameter tuning
- Random Forest Regression
- XGBoost
- LightGBM
- Time-series forecasting using LSTM
- Deployment using Streamlit or Flask

---

# 📚 References

- Kaggle Store Sales Forecasting Dataset
- Scikit-Learn Documentation
- Pandas Documentation
- NumPy Documentation
- Matplotlib Documentation
- Seaborn Documentation

---

# 👨‍💻 Author

**Adarsh Yadav**

Minor Project


## ⭐ If you found this project useful, consider giving it a star!
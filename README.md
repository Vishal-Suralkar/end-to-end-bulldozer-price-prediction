🚜 End-to-End Bulldozer Price Prediction (Time-Series Regression)
📌 Project Overview

This project builds an end-to-end Machine Learning pipeline to predict the resale price of bulldozers using historical auction data.

The objective is to accurately estimate machine prices based on features such as manufacturing year, product size, usage patterns, and sale date.

This project demonstrates:

Real-world ML workflow

Advanced feature engineering

Time-aware validation

Hyperparameter tuning

Business-driven evaluation

🧠 Business Problem

Construction companies and equipment dealers require accurate resale price predictions to:

Optimize pricing strategy

Minimize financial risk

Improve bidding decisions

Maximize return on assets

This project solves that problem using supervised regression modeling.

📊 Dataset Description

The dataset contains historical auction data of bulldozers including:

Sale date

Machine specifications

Model ID

Product size

Usage information

Sale price (target variable)

Since price distribution is skewed, log transformation was applied.

⚙️ Tech Stack

Python

Pandas

NumPy

Scikit-learn

Matplotlib

Random Forest Regressor

RandomizedSearchCV

🔍 Project Workflow
1️⃣ Data Cleaning & Preprocessing

Converted saledate to datetime format

Extracted year, month, day, and day of week

Handled missing values

Converted categorical variables

Applied log transformation to target variable

2️⃣ Feature Engineering

Created time-based features

Processed high-cardinality categorical variables

Ensured time-based data splitting (no data leakage)

3️⃣ Model Development

Built baseline regression model

Trained Random Forest Regressor

Performed hyperparameter tuning using RandomizedSearchCV

Used time-aware validation strategy

📈 Evaluation Metric
RMSLE (Root Mean Squared Log Error)

RMSLE was used instead of RMSE because:

Target variable is highly skewed

Penalizes underestimation and overestimation proportionally

More suitable for price prediction problems

📊 Model Performance
Model	RMSLE
Baseline Model	X.XXX
Random Forest	X.XXX
Tuned Random Forest	X.XXX

✅ Final Model: Tuned Random Forest
✅ Achieved improved prediction accuracy after hyperparameter tuning

📌 Key Insights

Machine age strongly impacts resale price

Larger product sizes retain higher value

Time-based features significantly improved performance

Feature engineering had greater impact than model complexity

🚀 What This Project Demonstrates

End-to-end ML pipeline design

Business-oriented model evaluation

Time-series data handling

Advanced feature engineering

Hyperparameter optimization

Clean and reproducible workflow

🔮 Future Improvements

Implement XGBoost / Gradient Boosting

Perform advanced categorical encoding

Build interactive dashboard

Deploy model using Streamlit

👨‍💻 Author

Vishal Suralkar
Aspiring Data Scientist | Machine Learning | Python | Analytics

⭐ If You Found This Project Interesting

Give it a ⭐ and feel free to connect with me!

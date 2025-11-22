# Customer Churn Prediction (Machine Learning Project)

This project predicts whether a customer is likely to churn based on behavioral patterns such as order history, app usage, tenure, and support interactions.

The project includes:
- Data preprocessing
- Exploratory Data Analysis (EDA)
- Machine Learning models (Random Forest & XGBoost)
- Model comparison using Accuracy & ROC-AUC
- Feature importance analysis

## 🛠️ Technologies Used

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- XGBoost
- Jupyter Notebook


## 📊 Dataset Description

Synthetic dataset with 5000 customers containing:

- `age`
- `gender`
- `country`
- `tenure_months`
- `total_orders`
- `avg_order_value`
- `app_opens_per_month`
- `support_tickets_raised`
- `is_premium_member`
- `used_coupon_last_month`
- `churned` (Target variable)


## 🚀 Project Workflow

1. Data Generation (Synthetic data)
2. Data Cleaning
3. Exploratory Data Analysis
4. Encoding categorical variables
5. Train-Test Split
6. Model Training:
   - Random Forest
   - XGBoost
7. Model Evaluation:
   - Accuracy
   - Classification Report
   - ROC-AUC
   - Confusion Matrix
8. Feature Importance analysis


## 📈 Model Performance Summary

| Model | Accuracy | ROC-AUC |
|-------|----------|----------|
| Random Forest | ~85% | ~0.88 |
| XGBoost | ~88% | ~0.91 |

*XGBoost performed better overall.*


## ▶️ How to Run This Project

1. Clone the repository:
   ```bash
   git clone https://github.com/mansikapse04/customer_churn_ml.git



pip install -r requirements.txt


jupyter notebook



---

# ⭐ Step 8 (Optional but powerful): Future Improvements

```md
## 🔮 Future Improvements

- Hyperparameter tuning (GridSearchCV)
- Adding SHAP explainability
- Deploying model with Streamlit
- Adding Power BI dashboard

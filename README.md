# Machine_learning-cse422_project-

# 🛍️ Sales Prediction Model

This project aims to build a machine learning model that predicts product sales in a retail environment. It involves detailed preprocessing, model training, and evaluation of various regression algorithms.

## 📁 Project Overview

The primary goal is to forecast sales based on features like product attributes and outlet characteristics. This helps retailers optimize inventory, pricing, and marketing strategies by making data-driven decisions.

---

## 👥 Group Members

- **Samin Sayonton Aungshuk** - 21201721  
- **Anindita Dash** - 21201116  
- CSE422, Section 11

---

## 📊 Dataset

- **Source**: [Kaggle - Dataset for Null Value Treatment](https://www.kaggle.com/datasets/akalyasubramanian/dataset-for-null-value-treatment)
- **Size**: 8523 rows × 12 columns
- **Target Variable**: `Item_Outlet_Sales`
- **Feature Types**:
  - *Categorical*: Item_Identifier, Item_Fat_Content, Item_Type, etc.
  - *Numerical*: Item_Weight, Item_Visibility, etc.

---

## ⚙️ Data Preprocessing

- Removed rows with **NULL values** in `Item_Weight` and `Outlet_Size`
- Applied **Label Encoding** to categorical features
- Removed columns with high uniqueness or low relevance
- Scaled numerical features using **StandardScaler**

---

## 🧪 Train-Test Split

- Final dataset: **4648 rows**
- **70%** for training, **30%** for testing

---

## 🤖 Models Used

- **Linear Regression**
- **Decision Tree Regressor**
- **Random Forest Regressor**
- **Multi-Layer Perceptron (MLP)**

---

## 📈 Evaluation Metrics

- **R² Score**
- **Mean Squared Error (MSE)**

### 📊 Results Summary

Each model was evaluated based on R² score and MSE to compare performance and accuracy of sales prediction.

---

## ✅ Conclusion

The project demonstrates how sales forecasting can be improved using regression-based machine learning techniques. While the selected models performed well, other advanced methods like XGBoost or ensemble stacking could further improve accuracy.

---

## 📂 Files

- `project_report.pdf`: Full documentation of the project and results
- `notebooks/`: Jupyter notebooks for data processing and modeling
- `README.md`: Project description and summary

---

## 📬 Contact

For queries or feedback, reach out via GitHub or email.


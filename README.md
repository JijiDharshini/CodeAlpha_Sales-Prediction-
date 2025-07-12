# CodeAlpha_Sales-Prediction-with-Python

This project uses regression techniques to predict product sales based on various advertising channels and market segments.

---

## 🎯 Objective

- Predict future sales based on advertising spend and platform
- Identify the most impactful marketing channels
- Generate actionable insights for business strategy

---

## 📁 Dataset

- **File:** `Sales_data.csv`
- **Columns Example:**
  - `TV`, `Radio`, `Social Media` — Ad spend in each channel
  - `Platform`, `Target_Audience`, `Region` — Categorical segments
  - `Sales` — Actual sales (Target variable)

---

## 🧠 Technologies Used

- Python
- Pandas, NumPy
- Scikit-learn (Regression, Preprocessing)
- Matplotlib, Seaborn
- Google Colab

---

## 📈 Visualizations

| Chart | Description |
|-------|-------------|
| `correlation_matrix.png` | Shows correlation among numerical features |
| `actual_vs_predicted.png` | Scatter plot of real vs predicted sales |
| `feature_importance.png` | Which features influence sales most |
| `pairplot.png` | Pairwise relationships in data |

---

## 📊 Model Evaluation

- **R² Score:** High accuracy achieved using Linear Regression
- **RMSE:** Acceptable error margin
- **Insights:**
  - TV & Social Media have high impact
  - Some platforms yield better ROI

---

## 🗂 Project Structure
Sales-Prediction/ ├── Sales_Prediction.ipynb ├── Sales_data.csv ├── README.md ├── sales_prediction_output.csv ├── sales_prediction_summary.pdf └── images/ ├── actual_vs_predicted.png ├── correlation_matrix.png ├── feature_importance.png └── pairplot.png


# 🏡 House Prices - Advanced Regression Techniques

This repository contains a full machine learning pipeline built to tackle the House Prices - Advanced Regression Techniques competition on Kaggle. It includes data preprocessing, feature engineering, model training, evaluation, and generation of a submission file. The project has been structured to reflect academic standards and pipeline best practices.

---

## 📁 Project Structure

```
.
├── dataset/
│   ├── train_unprocessed.csv
│   └── test.csv
├── notebook/
│   └── pipeline.ipynb
    └── deploy_pipeline.ipynb
├── pipeline/
│   ├── pipe.pkl
├── submission/
│   └── submission.csv
├── README.md
└── House_Price_Report.pdf
```

---

## 📌 Objective

To predict the final selling price of homes using advanced regression techniques, while handling missing values, categorical encodings, skewed data, and outliers through a clean and robust preprocessing pipeline.

---

## 🚧 Features

- ✅ Outlier capping using IQR logic  
- ✅ Handling of rare categorical values  
- ✅ ColumnTransformer for modular preprocessing  
- ✅ Yeo-Johnson transformation  
- ✅ Feature standardization  
- ✅ Integration of multiple regression models  
- ✅ Model persistence via `pickle`  

---

## 📈 Performance Summary

| Model               | R² Score | MAE     | RMSE    |
|--------------------|----------|---------|---------|
| Linear Regression   | 0.84     | 17890   | 23029   |
| Ridge Regression    | 0.85     | 17430   | 22600   |
| Random Forest       | 0.87     | 16500   | 21682   |
| Gradient Boosting   | 0.87     | 16200   | 21445   |

> 🔹 Final pipeline achieves **R² score of 0.87** on validation data.

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
https://github.com/YugBargaway2006/House-Prices---Advanced-Regression-Techniques.git
cd house-prices-regression
```

### 2. Install Dependencies

### 3. Launch the Notebook

```bash
jupyter notebook notebook/pipeline.ipynb

```

---

## 📜 License

This project is licensed under the [MIT License](LICENSE).

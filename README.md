# 🚗 Ford Car Price Prediction using Machine Learning

## 📌 Project Overview

This project predicts the price of used Ford cars using Machine Learning. The model was trained on a dataset containing over **17,000 car records** and uses various vehicle features to estimate the selling price.

The project includes data preprocessing, exploratory data analysis (EDA), feature engineering, model training, and model evaluation.

---

## 📊 Dataset

The dataset contains information about used Ford cars with features such as:

- Year
- Mileage
- Tax
- MPG (Miles Per Gallon)
- Engine Size
- Transmission
- Fuel Type
- Car Model
- Price (Target Variable)

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 🔍 Data Preprocessing

The following preprocessing steps were performed:

- Removed missing values
- One-Hot Encoding for categorical variables
- Feature selection
- Log transformation of the target variable (`price`)
- Train-Test Split
- Model evaluation

---

## 🤖 Machine Learning Model

Model Used:

- Linear Regression

---

## 📈 Model Performance

After applying a log transformation to the target variable, the model achieved:

- **R² Score:** 0.85
- **MAE:** 0.097
- **RMSE:** 0.153

The log transformation significantly improved the model performance compared to training directly on the original price values.

---

## 📂 Project Structure

```
Car-Price-Prediction/
│
├── dataset.csv
├── Car_Price_Prediction.ipynb
├── README.md
├── requirements.txt
└── model.pkl
```

---

## 🚀 How to Run

1. Clone the repository

```bash
git clone https://github.com/your-username/Car-Price-Prediction.git
```

2. Install dependencies

```bash
pip install -r requirements.txt
```

3. Open the Jupyter Notebook

```bash
jupyter notebook
```

4. Run all cells.

---

## 📚 Future Improvements

- Random Forest Regressor
- XGBoost Regressor
- Hyperparameter Tuning
- Cross Validation
- Deploy using Streamlit

---

## 👨‍💻 Author

**Shani**

Machine Learning Enthusiast

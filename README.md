# House Price Prediction using Linear Regression

## 📌 Overview

This project is part of the **SkillCraft Technology Machine Learning Internship - Task 01**.

The objective is to build a **Linear Regression** model to predict house prices based on:
- Square Footage
- Number of Bedrooms
- Number of Bathrooms

The model is trained using the Kaggle **House Prices - Advanced Regression Techniques** dataset.

---

## 📂 Dataset

Dataset Source:
https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/data

For this project, the following features were used:

| Feature | Description |
|---------|-------------|
| GrLivArea | Above ground living area (Square Footage) |
| BedroomAbvGr | Number of Bedrooms |
| FullBath | Number of Full Bathrooms |
| SalePrice | House Price (Target Variable) |

---

## 🛠 Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Scikit-learn
- Matplotlib

---

## 📊 Machine Learning Model

Algorithm Used:

- Linear Regression

Workflow:

1. Load Dataset
2. Select Features
3. Split Dataset into Training and Testing Sets
4. Train Linear Regression Model
5. Predict House Prices
6. Evaluate Model using:
   - Mean Absolute Error (MAE)
   - Mean Squared Error (MSE)
   - R² Score

---

## 📈 Model Evaluation

The model performance is evaluated using:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- R² Score

---

## 📷 Output

The notebook contains:

- Dataset Preview
- Model Training
- Predicted House Prices
- Model Evaluation Metrics
- Scatter Plot (Actual vs Predicted Prices)

---

## 📁 Project Structure

```
skillcraft-task-1/
│
├── House_Price_Prediction.ipynb
├── README.md
├── requirements.txt
└── images/
```

---

## ▶️ How to Run

1. Clone the repository.

```
git clone https://github.com/YOUR_USERNAME/skillcraft-task-1.git
```

2. Install dependencies.

```
pip install -r requirements.txt
```

3. Open the notebook in Google Colab or Jupyter Notebook.

4. Upload the dataset (`train.csv`).

5. Run all cells.

---

## 📌 Results

The Linear Regression model successfully predicts house prices using:

- Living Area
- Bedrooms
- Bathrooms

Model performance is measured using MAE, MSE, and R² Score.

---

## 👨‍💻 Author

**Sreeman**

SkillCraft Technology Machine Learning Internship

Task 01 - House Price Prediction using Linear Regression

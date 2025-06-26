# SCT_ML_1
Regression model to predict house prices based on square footage, bedrooms, and bathrooms | Internship @ SkillCraft Technologies

# 🏠 House Price Prediction Using Linear Regression

This project predicts house prices using a **Linear Regression** model based on:

## 📌 Objective

🔍 Predict the price of a house using:
- Area (in sq. ft.)
- Number of Bedrooms
- Number of Bathrooms

The model is trained using **scikit-learn’s LinearRegression** and evaluated using **R² score** and **Mean Squared Error**.

## DataSet Details

| File Name                 | Description                                  |
|--------------------------|----------------------------------------------|
| `House_Price_Prediction.py` | Main Python script with complete model logic |
| `Housing.csv`            | Dataset containing house features and prices  |
| `requirements.txt`       | Required Python libraries list                |
| `README.md`              | You're reading it 😄                          |

---


## 🧠 Techniques Used

- Linear Regression (Supervised ML)
- Data Preprocessing (handling missing values)
- Train-test splitting
- Evaluation using R² and MSE
- Scatter plot visualization of predictions

---

## ✅ Output Example

### 📊 Model Evaluation Metrics:
R² Score: 0.45592991188724474
Mean Squared Error: 2750040479309.0513

---

## 🚀 How to Run the Project

You can run this project either in VS Code, Jupyter Notebook, or Google Colab:

---

### 🔹 Option 1: Run on Google Colab (Recommended)

1. Go to [Google Colab](https://colab.research.google.com/)
2. Copy and paste the code from `housing_price_prediction.py` into a new notebook
3. Upload the dataset file:
   ```python
   from google.colab import files
   uploaded = files.upload()  # Upload Housing.csv

---   
   
### 🔹 Option 2: Run Locally (VS Code / Terminal)

1. Make sure Python is installed  
2. Install required libraries:
   ```bash
   pip install pandas matplotlib scikit-learn



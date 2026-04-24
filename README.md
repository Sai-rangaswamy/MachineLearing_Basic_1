# Linear Regression Project

## 📌 Problem Statement
This project aims to predict a continuous value using a Linear Regression model.

## 📂 Dataset
- Description: https://lms.snuchennai.edu.in/pluginfile.php/19519/mod_assign/introattachment/0/CarPrice_Assignment%20%282%29.csv?forcedownload=1
- Features: horse power
- Target: price

## ⚙️ Workflow
1. Data Cleaning
   - Removed null values
   - Handled duplicates

2. Data Preprocessing
   - Feature selection
   - Normalization (if applied)

3. Train-Test Split
   - Split ratio: 80% training, 20% testing

4. Model
   - Applied Linear Regression

## 🧠 Model Explanation
Linear Regression finds a relationship between input features and a continuous output using a best-fit line.

## 📊 Results
- Evaluation Metric: r2 score = 0.6326129716904236 ,MSE: 3601.91529863185
- 

## 🛠 Tech Stack
- Python
- Pandas
- NumPy
- Scikit-learn

## ▶️ How to Run
```bash
pip install -r requirements.txt
python main.py

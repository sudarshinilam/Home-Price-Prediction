# 🏠 Home Price Prediction using Linear Regression

This project uses **Linear Regression** to predict housing prices based on the area (in square feet). The dataset is a simple real-estate dataset, and the model is built using Python's `scikit-learn` library.

---

## 📌 Project Overview

- **Goal:** Predict home prices based on area using supervised machine learning (Linear Regression).
- **Tools Used:** Python, Pandas, Matplotlib, scikit-learn
- **Output:** Predicted prices for new home areas, saved to CSV and visualized with a regression line.

---
## 📂 Files in This Project

| File Name              | Description                                      |
|------------------------|--------------------------------------------------|
| `df1.csv`              | Initial dataset (area vs price) used to train the model |
| `df3.csv`              | New areas for which predictions are to be made  |
| `predictedprice.csv`   | Output CSV file with predicted prices           |
| `home_price_prediction.py` | Python script containing the full code        |
| `home_price_prediction.ipynb` | (Optional) Jupyter notebook version       |   
| `README.md`            | Project documentation (this file)               |

---
📈 Sample Plot Output
Red dots: Actual data (training)
Pink line: Predicted regression line
Pink circles: Predicted values for new areas
This visualization helps you understand how well the model fits the training data and the predictions for new inputs.

📊 Model Details
Model Used: LinearRegression() from sklearn.linear_model
Features: area
Target: price
Output: Predicted price using the formula:
price = m * area + b
Where:
m is the slope (model coefficient)
b is the intercept

📄 Sample Prediction
For example, if you predict for an area of 3300 sq ft, you may get an output like:

Predicted Price: ₹628,408

🧰 Libraries Used
Pandas
NumPy
Matplotlib
scikit-learn

🧑‍💻 Author
Nilam Sudarshi
GitHub: @yourusername
Project Repository: home-price-prediction

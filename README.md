# 💻 Laptop Price Prediction

A machine learning project to predict laptop prices based on various hardware specifications.
[GitHub Repository: github.com/mshahzaib4/Laptop-Price-Prediction](https://github.com/mshahzaib4/Laptop-Price-Prediction)
![Image](https://github.com/user-attachments/assets/a28987f0-86df-4fd3-bb01-1998ad887f94)

---

## 📦 Dependencies

Install all required Python packages with:

```bash
pip install -r requirements.txt
```

---

## 📊 Dataset Overview

The dataset consists of information on **1302 laptops** scraped from Amazon (2017–18). It includes 12 features such as:

* Company Name
* Type Name
* Screen Size (inches)
* Screen Resolution
* CPU
* RAM
* Memory
* GPU
* Operating System
* Price (INR)

---

## 🤖 Model Selection

A range of regression models were tested for price prediction:

* Multiple Linear Regression
* Ridge & Lasso Regression
* k-Nearest Neighbors (k-NN)
* Decision Tree
* Support Vector Machine (SVM)
* Random Forest
* ExtraTrees
* AdaBoost
* Gradient Boosting
* XGBoost
* Voting Regressor
* Stacking Regressor
* **Customized Random Forest Regressor**
* **Customized Voting Regressor (Random Forest + Gradient Boosting)**

---

## ✅ Selected Models & Results

**Random Forest Regressor (Customized)**

```
R² Score: 88.78%  
Mean Absolute Error: 15.94%
```

**Voting Regressor (Random Forest + Gradient Boosting)**

```
R² Score: 89.27%  
Mean Absolute Error: 15.37%
```

---

## 💱 Optional: Price Currency Conversion

You can convert the predicted price from INR to USD (or any other currency).
Example using INR → USD (1 INR = 0.012 USD):

```python
st.title(f"\nPrice: {round(predicted_price * 0.012, 2)} USD")
```

Customize the exchange rate as needed.

---

## 🚀 Run the App

To launch the Streamlit app:

```bash
streamlit run app.py
```

---

## 🛠 Need Help?

If you encounter any issues or bugs, feel free to open an issue in the repository.
And if you find this project helpful, don't forget to ⭐️ the repo!

---

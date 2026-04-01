# 💡 BMI Driven Insurance Cost Prediction

## 📌 Project Overview

This project focuses on analyzing and predicting **medical insurance costs** based on various personal and lifestyle factors, with a special focus on **BMI (Body Mass Index)**.

Using Machine Learning techniques, this project identifies how different features like age, BMI, smoking habits, and number of children affect insurance charges.

---

## 🎯 Objective

* Analyze the impact of **BMI on insurance costs**
* Perform **Exploratory Data Analysis (EDA)**
* Build a **Machine Learning model** to predict insurance charges
* Understand key factors influencing medical expenses

---

## 📊 Dataset Description

The dataset contains information about individuals and their insurance charges.

### 🔑 Features:

* **Age** → Age of the person
* **Sex** → Gender
* **BMI** → Body Mass Index
* **Children** → Number of dependents
* **Smoker** → Smoking status
* **Region** → Residential area
* **Charges** → Medical insurance cost (Target Variable)

👉 These features are commonly used in insurance prediction models to estimate costs based on health and lifestyle factors ([GitHub][1])

---

## 🔍 Exploratory Data Analysis (EDA)

* Visualized relationships between BMI and insurance charges
* Identified patterns for smokers vs non-smokers
* Analyzed how age and BMI together impact cost
* Checked distribution of features

### 📌 Key Insights:

* Smokers have significantly higher insurance charges
* Higher BMI often leads to increased medical costs
* Age is a major factor in determining insurance cost
* Combination of smoking + high BMI leads to highest charges

---

## ⚙️ Data Preprocessing

* Handled missing values
* Encoded categorical variables
* Feature selection
* Prepared data for model training

---

## 🤖 Model Building

* Applied Machine Learning algorithms (e.g., Linear Regression)
* Trained model on dataset
* Predicted insurance charges

---

## 📈 Model Evaluation

* Evaluated using metrics like:

  * R² Score
  * MAE (Mean Absolute Error)
  * RMSE (Root Mean Squared Error)

👉 These metrics help measure how accurately the model predicts insurance costs ([GitHub][2])

---

## 🚀 Technologies Used

* Python 🐍
* Pandas & NumPy
* Matplotlib & Seaborn
* Scikit-learn
* Jupyter Notebook

---

## 📂 Project Structure

```
📁 Insurance-Cost-Prediction
│── BMI_Driven_Insurance_Costs.ipynb
│── README.md
│── requirements.txt
```

---

## ▶️ How to Run

1. Clone the repository

```
git clone https://github.com/your-username/insurance-project.git
```

2. Install dependencies

```
pip install -r requirements.txt
```

3. Run the notebook

```
jupyter notebook
```

---

## 📌 Future Improvements

* Add more advanced models (Random Forest, XGBoost)
* Deploy using Streamlit 🌐
* Improve feature engineering
* Build interactive dashboard

---

## 👨‍💻 Author

**Vedant Nachankar**

🔗 LinkedIn:
[www.linkedin.com/in/vedant-nachankar-6396783b1](http://www.linkedin.com/in/vedant-nachankar-6396783b1)

---

## ⭐ If you like this project

Give it a ⭐ on GitHub and share it!

---

[1]: https://github.com/adiag321/Medical-Insurance-Cost-Prediction?utm_source=chatgpt.com "GitHub - adiag321/Medical-Insurance-Cost-Prediction: A Project to analyze and predict the cost of Medical costs of patients and evaluate the model using various Performance Metrics."
[2]: https://github.com/mhdee740/insurance-charges-prediction-linear-regression?utm_source=chatgpt.com "GitHub - mhdee740/insurance-charges-prediction-linear-regression: Predict insurance charges with linear regression; Python project offers a concise EDA-to-model workflow with feature engineering, training, and evaluation 🐙."

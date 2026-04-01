# 💡 BMI Driven Insurance Cost Prediction 🚀

🔗 **Live App:** https://medical-insurance-vedant.streamlit.app/
🔗 **GitHub Repository:** https://github.com/vedantnachankar856-sketch/insurance-
🔗 **LinkedIn:** https://www.linkedin.com/in/vedant-nachankar-6396783b1

---

## 📌 Project Overview

This project focuses on predicting **medical insurance charges** using Machine Learning by analyzing various personal and health-related factors, especially **BMI (Body Mass Index)**.

BMI plays a crucial role in determining insurance costs because it reflects a person’s health risk — higher BMI is often linked to higher medical expenses and insurance premiums ([IndiaFirst Life Insurance][1]).

---

## 🎯 Objective

* Analyze the relationship between **BMI and insurance charges**
* Perform **Exploratory Data Analysis (EDA)**
* Build a **Machine Learning model** for prediction
* Deploy the model using **Streamlit Web App**

---

## 📊 Dataset Description

The dataset contains information about individuals and their insurance costs.

### 🔑 Features:

* **Age** → Age of the individual
* **Sex** → Gender
* **BMI** → Body Mass Index
* **Children** → Number of dependents
* **Smoker** → Smoking status
* **Region** → Residential area
* **Charges** → Medical insurance cost (Target Variable)

👉 Factors like BMI, age, and smoking significantly influence insurance premiums due to associated health risks ([LinkedIn][2]).

---

## 🔍 Exploratory Data Analysis (EDA)

* Visualized BMI vs insurance charges 📈
* Compared smokers vs non-smokers 🚬
* Analyzed age impact on costs
* Checked feature distributions

### 📌 Key Insights:

* Smokers have significantly higher charges
* Higher BMI → Higher insurance cost
* Age strongly influences medical expenses
* Combination of smoking + high BMI = highest charges

---

## ⚙️ Data Preprocessing

* Handled missing values
* Encoded categorical variables
* Feature selection
* Data transformation for model training

---

## 🤖 Model Building

* Applied Machine Learning algorithms
* Trained model on dataset
* Predicted insurance charges

---

## 📈 Model Evaluation

Model performance evaluated using:

* **R² Score**
* **Mean Absolute Error (MAE)**
* **Root Mean Squared Error (RMSE)**

---

## 🌐 Streamlit Web App

An interactive web application built using **Streamlit** where users can:

✅ Enter personal details
✅ Get predicted insurance cost instantly
✅ Experience real-time ML predictions

👉 Try it here:
🔗 https://medical-insurance-vedant.streamlit.app/

---

## 🚀 Technologies Used

* Python 🐍
* Pandas & NumPy
* Matplotlib & Seaborn
* Scikit-learn
* Streamlit

---

## 📂 Project Structure

```
📁 insurance-project
│── BMI_Driven_Insurance_Costs.ipynb
│── app.py
│── model.pkl
│── requirements.txt
│── README.md
```

---

## ▶️ How to Run Locally

1. Clone the repository

```
git clone https://github.com/vedantnachankar856-sketch/insurance-
```

2. Navigate to project folder

```
cd insurance-
```

3. Install dependencies

```
pip install -r requirements.txt
```

4. Run Streamlit app

```
streamlit run app.py
```

---

## 📌 Future Improvements

* Use advanced models (Random Forest, XGBoost)
* Improve feature engineering
* Add more interactive visualizations
* Deploy on cloud platforms

---

## 👨‍💻 Author

**Vedant Nachankar**

🔗 LinkedIn:
https://www.linkedin.com/in/vedant-nachankar-6396783b1

---

## ⭐ Support

If you like this project:

* ⭐ Star this repo
* 🔗 Share on LinkedIn
* 💬 Give feedback

---

## 💬 Conclusion

This project demonstrates how **Machine Learning + Data Analysis** can be used to predict real-world insurance costs based on health and lifestyle factors like BMI.

---

[1]: https://www.indiafirstlife.com/knowledge-center/life-insurance/impact-of-bmi-on-term-insurance-premium?utm_source=chatgpt.com "Impact of BMI on Term Insurance Premiums"
[2]: https://www.linkedin.com/posts/chisom-edeh-8509512ab_healthcare-insurance-activity-7333661510331752448-RDip?utm_source=chatgpt.com "How smoking, age, and BMI affect health insurance costs | Jennifer Edeh posted on the topic | LinkedIn"

# 🏡 House Price Prediction Using Machine Learning

This is my first machine learning project where I used **Linear Regression** to predict house prices based on real-world data. The project demonstrates data exploration, preprocessing, model building, and evaluation using Python.

---

## 📌 Project Overview
Predicting house prices is a classic machine learning problem. The goal is to create a model that can accurately estimate the price of a house given features such as average income, rooms, population, and housing age.

---

## 🛠 Tools & Technologies Used
- **Python 3.x**  
- **Pandas, NumPy** – Data handling & manipulation  
- **Matplotlib, Seaborn** – Data visualization  
- **Scikit-learn** – Machine Learning models (Linear Regression)  
- **Google Colab / Jupyter Notebook** – Development environment  

---

## 📂 Dataset
- **Source:** California Housing dataset from `sklearn.datasets.fetch_california_housing`  
- **Features:**  
  - `MedInc` – Median income in block group  
  - `HouseAge` – Median house age in block group  
  - `AveRooms` – Average rooms per household  
  - `AveOccup` – Average occupants per household  
  - …and more  
- **Target:** `MedHouseVal` – Median house value in USD

---

## 🔍 Data Exploration & Visualization
- Explored statistical summaries and distributions of all features  
- Visualized correlations and relationships between features and the target variable  
- Detected patterns and potential outliers in the dataset  

Example visualization:  

![scatter plot of actual vs predicted prices](link-to-image-if-uploaded)

---

## ⚙️ Model Building
1. Split the dataset into **train and test sets**  
2. Built a **Linear Regression model** using Scikit-learn  
3. Evaluated model performance using:
   - **Mean Squared Error (MSE)**  
   - **R² Score**  

---

## 📊 Results
- **R² Score:** ~0.7  
- Model predictions closely align with actual prices  
- Scatter plots show predicted vs actual values

---

## 🚀 Future Improvements
- Experiment with advanced models: **Random Forest, XGBoost**  
- Feature engineering for better predictions  
- Deploy the model as a **web app using Streamlit**  
- Apply model to other real-world datasets  

---

## 📁 Project Structure
House_Price_Prediction/
├── notebooks/ ← Jupyter notebooks
│ └── House_Price_Prediction.ipynb
├── data/ ← Raw & processed data (if applicable)
├── src/ ← Python scripts (optional)
├── README.md ← Project overview and instructions
└── requirements.txt ← Python dependencies

## 🔗 Links
- GitHub Repository: [House_Price_Prediction](https://github.com/kunu55/House_Price_Prediction)

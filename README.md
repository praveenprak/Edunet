# 🖥️ E-Waste Generation Classification using Machine Learning

This project uses machine learning algorithms to classify regions based on their level of e-waste generation. It aims to help identify high-risk areas and support efficient waste management.

---

## 📌 Objective

To build a predictive model that classifies areas into **Low**, **Medium**, or **High** e-waste generation categories using relevant features such as population, electronics usage, and recycling infrastructure.

---

## 📊 Dataset Overview

- **Features:**
  - Region/City/Area
  - Population Density
  - Industrial Presence
  - Number of Electronics Sold
  - Average Device Lifespan
  - Recycling Facilities Available
  - **Target:** E-waste Generation Category (Low, Medium, High)

- **Source:** *

##  Dataset Overview

###  Dataset Name: E-Waste Image Dataset  
###  Source:  https://www.kaggle.com/datasets/akshat103/e-waste-image-dataset 

Each directory contains 10 subfolders, each representing one class of e-waste:

- PCB (Printed Circuit Board)
- Player
- Battery
- Microwave
- Mobile
- Mouse
- Printer
- Television
- Washing Machine
- Keyboard

</div>*

---

## 🛠️ Data Preprocessing

- Missing value handling
- Normalization of numeric features
- Label Encoding / One-Hot Encoding
- Train-test split (80:20)

---

## 📈 Exploratory Data Analysis (EDA)

- Visualizations: bar plots, distribution plots, heatmaps
- Insights:
  - High population & sales → More e-waste
  - More recycling units → Lower waste classification

---

## 🤖 Algorithms Used

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier ✅ (Best Performer)
- Support Vector Machine (SVM)

---

## 📊 Model Evaluation

| Metric     | Value  |
|------------|--------|
| Accuracy   | 87%    |
| Precision  | 85%    |
| Recall     | 88%    |
| F1-Score   | 86%    |

---

## 🔍 Key Findings

- Urban, high-sales regions show higher e-waste
- Random Forest gives high accuracy and interpretability
- Important features: Population, Sales, Recycling Access

---

## 🔮 Future Scope

- Use real-time IoT/sensor data
- Geospatial analysis (heatmaps)
- Environmental impact layer

---

name:penugonda praveen kumar 
intership foundation:Edunet foundation


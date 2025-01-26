# Algerian Forest Fires Prediction

## 📌 Project Overview
This project analyzes the **Algerian Forest Fires Dataset** to build a **machine learning model** that predicts the likelihood of forest fires based on environmental and weather conditions. The goal is to develop a robust predictive model that can help in early detection and prevention of forest fires.

## 📊 Dataset Information
The dataset contains **244 instances** collected from **two regions in Algeria**:
- **Bejaia Region (Northeast Algeria) – 122 instances**
- **Sidi Bel-abbes Region (Northwest Algeria) – 122 instances**

The dataset covers the period from **June 2012 to September 2012** and includes **11 features** and **1 output attribute (Fire/No Fire class)**.

## 📌 Features (Attributes)
1. **Date**: Recorded in DD/MM/YYYY format.
2. **Temp**: Temperature at noon (max) in Celsius degrees (22-42°C).
3. **RH**: Relative Humidity in % (21-90%).
4. **Ws**: Wind speed in km/h (6-29 km/h).
5. **Rain**: Total rainfall in mm (0-16.8 mm).
6. **FFMC**: Fine Fuel Moisture Code (28.6-92.5).
7. **DMC**: Duff Moisture Code (1.1-65.9).
8. **DC**: Drought Code (7-220.4).
9. **ISI**: Initial Spread Index (0-18.5).
10. **BUI**: Buildup Index (1.1-68).
11. **FWI**: Fire Weather Index (0-31.1).
12. **Class**: Binary classification (Fire or No Fire).

## 🔥 Objective
- **Data Preprocessing**: Handling missing values, data cleaning, feature scaling.
- **Exploratory Data Analysis (EDA)**: Understanding relationships between weather conditions and fire occurrences.
- **Model Selection**: Implementing and evaluating classification models.
- **Performance Metrics**: Accuracy, precision, recall, F1-score, and confusion matrix.

## 🏗️ Tech Stack & Tools
- **Programming Language**: Python 🐍
- **Libraries**: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
- **Modeling Techniques**: Logistic Regression, Random Forest, SVM, Decision Tree
- **Visualization**: Power BI, Matplotlib, Seaborn

## 🚀 Implementation Steps
1. **Data Loading**: Read dataset, inspect missing values, and clean inconsistencies.
2. **Exploratory Data Analysis (EDA)**: 
   - Statistical summaries
   - Correlation matrix
   - Visualizing fire trends
3. **Feature Engineering**:
   - Normalization & standardization
   - Handling categorical values
4. **Model Training & Evaluation**:
   - Train/test split
   - Model selection & hyperparameter tuning
   - Performance evaluation using classification metrics
5. **Results & Insights**:
   - Model comparison
   - Key influencing factors
   - Future improvements

## 📈 Results & Findings
- **Identified key factors influencing fire occurrences**
- **Developed a predictive model with high accuracy**
- **Gained insights into fire-prone weather conditions**

## 💡 Future Enhancements
- Incorporate **deep learning models** (e.g., Neural Networks)
- Integrate **real-time weather data** for live predictions
- Develop a **dashboard** for visualizing fire risk zones


## 🎯 Conclusion
This project demonstrates how **machine learning** can help in **predicting and preventing forest fires**. By analyzing historical weather conditions, our model provides valuable insights for **disaster management teams** to take proactive measures.


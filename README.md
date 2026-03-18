# Medical Insurance Data Analysis & Preprocessing 🏥

## 📌 Project Overview
This project performs a deep dive into medical insurance data to identify key trends and prepare the dataset for analytical use. The focus is entirely on **Data Cleaning**, **Exploratory Data Analysis (EDA)**, and **Feature Engineering**.

## ⚙️ Key Technical Steps
- **Exploratory Data Analysis:** Utilizing `Seaborn` and `Matplotlib` to visualize correlations, distributions of BMI, and the impact of smoking on insurance charges.
- **Data Cleaning:** Handling null values and ensuring data integrity for demographic features.
- **Feature Engineering:** - Created a custom `bmi_category` feature to bin continuous BMI data into meaningful groups (Underweight, Normal, Overweight, Obese).
    - Implemented One-Hot Encoding for categorical variables (Sex, Region, Smoking Status).
- **Feature Scaling:** Applied `StandardScaler` to ensure all numerical features are on a comparable scale, which is essential for many statistical algorithms.

## 🛠️ Tech Stack
- **Python**
- **Pandas & NumPy:** For data manipulation and matrix operations.
- **Seaborn & Matplotlib:** For statistical data visualization.
- **Scikit-Learn:** Used specifically for the `StandardScaler` preprocessing module.

## 📈 Visualizations Included
The notebook generates several insights:
- Correlation heatmaps showing the relationship between age, BMI, and charges.
- Distribution plots for age and smoking habits.
- Comparative analysis of charges across different BMI categories.

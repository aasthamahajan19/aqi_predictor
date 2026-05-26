# Air Quality Index (AQI) Prediction using Ensemble Learning

This repository contains a Machine Learning project focused on predicting the **Air Quality Index (AQI)** based on environmental pollutants and weather conditions. The model uses ensemble techniques to improve prediction accuracy and provides categorical health advisories based on the results.

## 🚀 Project Overview
Air pollution is a significant global health concern. This project analyzes a dataset of 10,000 air quality records to build a robust regressor. It compares traditional regression models with advanced ensemble methods to determine the most effective way to predict AQI levels.

## 📊 Key Features
- **Exploratory Data Analysis (EDA):** Visualizing pollutant distributions and correlations using Seaborn and Matplotlib.
- **Data Processing:** Automated handling of missing values and feature scaling with `StandardScaler`.
- **Machine Learning Models:**
  - Linear Regression
  - Support Vector Regression (SVR)
  - Random Forest Regressor
  - **Voting Regressor (Ensemble):** Combines multiple models for superior performance.
- **AQI Classification:** A custom function that maps numerical AQI scores to health categories (e.g., Good, Moderate, Unhealthy).
- **Visual Insights:** Includes feature importance charts and actual vs. predicted value plots.

## 🛠️ Tech Stack
- **Language:** Python
- **Libraries:** Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn
- **Environment:** Jupyter Notebook / Google Colab

## 📂 Repository Contents
- `aqi_predictor.ipynb`: The complete Python code and analysis.
- `global_air_quality_data_10000.csv`: The dataset containing pollutant levels and AQI scores.
- `README.md`: Project documentation.

## ⚙️ How to Run
1. **Clone the repository:**
   ```bash
   git clone [https://github.com/your-username/your-repo-name.git](https://github.com/your-username/your-repo-name.git)
   Install required packages:Bashpip install pandas numpy matplotlib seaborn scikit-learn
Execute the notebook:Run aqi_predictor.ipynb in any Jupyter environment to see the training process and visualizations.📈 Performance ResultsThe Random Forest and Voting Regressor models consistently achieve the highest $R^2$ scores, demonstrating the effectiveness of ensemble learning in capturing the complex relationships between pollutants like $PM_{2.5}$, $NO_2$, and the resulting AQI.Created as part of an AI development project focused on environmental data analysis.

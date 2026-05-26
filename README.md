# Air Quality Index (AQI) Prediction using Ensemble Learning

This project implements a Machine Learning pipeline to predict the **Air Quality Index (AQI)** using environmental pollutant data and weather variables. By comparing multiple regression algorithms, the project identifies the most accurate model for monitoring air quality and providing health advisories.

## 🚀 Features
- **Data Analysis:** Comprehensive EDA of pollutants like $PM_{2.5}$, $PM_{10}$, $NO_2$, $SO_2$, and $O_3$.
- **Advanced Modeling:** Implementation of several ML models:
  - Linear Regression
  - Support Vector Regression (SVR)
  - Random Forest Regressor
  - **Voting Regressor (Ensemble):** A combined model for higher prediction stability.
- **Categorical Mapping:** A built-in function to classify numerical AQI into health categories (Good, Moderate, Unhealthy, etc.).
- **Visualizations:** Correlation heatmaps, feature importance plots, and error distribution analysis.

## 📊 Dataset
The model is trained on a dataset containing 10,000 air quality samples. It includes features such as:
- **Pollutant Concentrations:** PM2.5, PM10, SO2, NO2, O3.
- **Meteorological Data:** Temperature and Humidity.
- **Target Variable:** AQI value.

## 🛠️ Tech Stack
- **Language:** Python
- **Libraries:** `Pandas`, `NumPy`, `Scikit-Learn`, `Matplotlib`, `Seaborn`

## 📂 Project Structure
- `aqi_predictor.ipynb`: Main Jupyter Notebook with code and visualizations.
- `global_air_quality_data_10000.csv`: The dataset used for training.
- `README.md`: Project documentation.

## ⚙️ How to Use
1. **Clone the Repo:**
   ```bash
   git clone [https://github.com/your-username/aqi_predictor.git](https://github.com/your-username/aqi_predictor.git)

2. **Install Dependencies:**
pip install pandas numpy scikit-learn matplotlib seaborn

3. **Run the Analysis:**
Open aqi_predictor.ipynb in your preferred IDE (VS Code, Jupyter, or Colab) and run all cells.
📈 Results
The ensemble approach (Voting Regressor) and Random Forest demonstrated the strongest performance, highlighting $PM_{2.5}$ as a primary driver for AQI levels.Developed for environmental data analysis and AI research.

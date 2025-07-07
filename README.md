# 🌧️ Rain Prediction Using Weather Data from Kozhikode, Kerala

> A machine learning project to predict tomorrow’s rainfall in Kozhikode, Kerala using real-world weather data.

---

## 📍 About the Project

This project leverages meteorological data from **Kozhikode (Calicut), Kerala, India** to build a model that predicts whether it will rain the next day.

It includes:
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Data Preprocessing & Balancing (SMOTE)
- Model Training using SVM, XGBoost, Logistic Regression, Decision Tree
- Performance Evaluation & Visualization

---

## 🗂️ Dataset

- **Source**: Historical weather archive (43314.csv.gz)
- **Location**: Kozhikode, Kerala
- **Features used**:
  - `temp`, `tmin`, `tmax`: Temperature stats
  - `rhum`: Relative Humidity
  - `pres`: Atmospheric Pressure
  - `cldc`: Cloud Cover
  - `wspd`: Wind Speed
  - `prcp`: Precipitation
  - `RainTomorrow`: Target variable (0 = No rain, 1 = Rain)

---

## 🧠 Models Used

| Model                | Accuracy | Notes                              |
|---------------------|----------|------------------------------------|
| Logistic Regression | ✅        | Good baseline model                |
| Support Vector Machine (SVM) | ✅        | Performed well with scaling         |
| XGBoost             | ✅✅       | Best performance overall 🎯         |
| Decision Tree       | ✅        | Easy to interpret                  |

SMOTE was used to handle class imbalance during training.

---

## 📊 Visualizations

- Feature Distributions
- Precipitation Correlation Analysis
- Confusion Matrix
- RainTomorrow Distribution Before & After SMOTE

---

## 🧰 Technologies Used

- Python 🐍
- Pandas & NumPy
- Scikit-learn
- XGBoost
- Seaborn & Matplotlib
- Jupyter Notebook

---

## 📝 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/rain-prediction-kozhikode.git
   cd rain-prediction-kozhikode

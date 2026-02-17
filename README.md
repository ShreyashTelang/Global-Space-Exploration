# Global-Space-Exploration
An exploratory data analysis (EDA) and machine learning project investigating global space missions, budget allocations, and mission success rates using Python and Scikit-Learn.

# Space Mission Analysis & Cost Prediction 🌌

This project performs a comprehensive Exploratory Data Analysis (EDA) on a global space exploration dataset. It investigates the relationships between mission budgets, satellite technologies, and environmental impacts, culminating in a Linear Regression model to predict mission costs.

## 📊 Project Overview
The goal of this project is to understand the economic and technical drivers of modern space exploration. By analyzing historical data, we identify trends in mission success and the financial requirements for different satellite classifications.

## 🛠️ Tech Stack
* **Language:** Python 3.11
* **Data Manipulation:** Pandas, NumPy
* **Visualization:** Matplotlib, Seaborn, Plotly (Interactive Maps & Treemaps)
* **Machine Learning:** Scikit-Learn (Linear Regression, One-Hot Encoding)

## 🔍 Key Features & Visualizations
* **Budget Analysis:** Investigated the mean success rate relative to budget allocation.
* **Categorical Mapping:** Converted mission types (Manned/Unmanned) into binary features for model compatibility.
* **Global Launch Tracking:** Geographical visualization of launch sites across collaborating countries.
* **Tech-Impact Heatmaps:** Analyzed the correlation between technology used and its environmental footprint.
* **Predictive Modeling:** Built a Linear Regression model to estimate mission costs based on satellite type.



## 📈 Model Performance
The current Linear Regression model utilizes One-Hot Encoding for categorical features:
* **Target Variable:** `Budget (in Billion $)`
* **Features:** `Satellite Type`, `Technology Used`
* **Evaluation Metrics:** R² Score and Mean Absolute Error (MAE).

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone [https://github.com/your-username/space-mission-analysis.git](https://github.com/your-username/space-mission-analysis.git)

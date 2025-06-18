# Production-Analysis-for-time-reduction-in-testing-of-automobiles
Predictive analytics project to estimate testing time for automotive components using machine learning. Includes data visualizations, feature importance for actionable insights.

This project includes data preprocessing, feature analysis, model training, performance evaluation, and dashboard visualization.

---

## 📌 Problem Statement

Automobile manufacturing involves multiple stages of production and quality testing. Optimizing testing time without compromising quality is critical for increasing plant throughput.

**Objective**:  
To build a predictive model that estimates the testing time (`y`) for parts/components based on their process parameters and categorical identifiers.

---

## 📂 Project Structure
├── PROJECT/
│ ├── train.csv # Training dataset
│ ├── test.csv # Testing dataset
│ ├── final_predictions.csv # Model output for test data
│ ├── importance_df.csv # Feature importance from Random Forest
├── dashboard_app.py # Streamlit dashboard script
├── requirements.txt # Project dependencies
├── README.md # This file

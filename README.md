# Student-Success-Analytics-Predicting-Performance-Burnout-with-Machine-Learning
End-to-end data analytics and machine learning project analyzing student habits to predict exam performance and burnout risk. Includes SQL querying, feature engineering, regression and classification models, visualization, and an interactive dashboard for personalized academic recommendations.
# Overview
This project analyzes student lifestyle and academic behavior data to:
- Predict exam scores
- Detect burnout risk
- Identify the optimal balance between study, sleep, and screen time
- Provide personalized academic recommendations

The project combines data analysis, SQL querying, machine learning, and interactive visualization into a complete end-to-end pipeline.
# Problem Statement
Student performance is influenced by multiple lifestyle factors including:
- Study hours
- Sleep duration
- Social media usage
- Caffeine intake
- Exercise habits

This project explores how these variables interact and builds predictive models to:
1. Forecast exam scores (Regression)
2. Classify high burnout risk students (Classification)
3. Identify an academic “efficiency sweet spot”

# Tech Stack
- Python
- Pandas & NumPy
- Matplotlib & Seaborn
- SQL (SQLite via SQLAlchemy)
- Scikit-learn
- ipywidgets (Interactive Dashboard)
# Exploratory Data Analysis
- Correlation heatmaps between habits and performance
- Study hours vs burnout trend analysis
- Sleep–Caffeine–Focus interaction visualization
- Success Matrix (Sleep vs Study heatmap)
- Efficiency Ratio to detect optimal study time
# Machine Learning Models
## Exam Score Prediction (Regression)
- Model: Random Forest Regressor
- Evaluation Metrics:
- Mean Absolute Error (MAE)
- R² Score
- Feature importance analysis performed
## Burnout Risk Detection (Classification)
- Model: Random Forest Classifier
- Target defined as top 25% burnout level
- Evaluation:
    - Precision, Recall, F1-score
    - Confusion Matrix visualization
# Feature Engineering
- Created composite metrics such as:
- Digital Distraction Score (Social Media Hours + Gaming Hours)
- Efficiency Ratio (Exam Score / Burnout Level)

These engineered features improved interpretability of behavioral patterns.
# AI Student Advisor
- Built a rule-based + ML hybrid advisory function that:
- Predicts exam score
- Detects burnout risk
- Provides personalized recommendations based on lifestyle inputs
# Interactive Dashboard
Developed a Jupyter-based interactive planner allowing users to:
- Adjust study hours
- Modify sleep duration
- Set target exam score
- Compare personal habits with top-performing students
- Receive AI-driven academic optimization insights

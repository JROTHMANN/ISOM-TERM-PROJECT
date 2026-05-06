# Predicting Global Happiness Scores Using Machine Learning

## ISOM 835 – Predictive Analytics and Machine Learning

This project analyzes global happiness trends using machine learning and predictive analytics techniques. Using the World Happiness Report dataset, the analysis explores how economic, social, and health-related variables influence happiness scores across countries over time.

---

# Project Objectives

The primary objectives of this project were to:

- Explore global happiness trends across countries and years
- Identify key variables associated with happiness scores
- Perform exploratory data analysis (EDA) using visualizations
- Build predictive machine learning models
- Compare model performance using evaluation metrics
- Interpret feature importance and business insights
- Discuss ethical considerations and model interpretability

---

# Dataset Information

- **Dataset:** World Happiness Report 2005–2025 Panel Dataset
- **Source:** Kaggle
- **Observations:** Country-level happiness indicators across multiple years
- **Target Variable:** `happiness_score`

## Key Features

- GDP per capita
- Social support
- Healthy life expectancy
- Freedom
- Generosity
- Corruption perceptions
- Year

---

# Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- GitHub

---

# Machine Learning Models

## Linear Regression
Used as a baseline predictive model to analyze linear relationships between socioeconomic variables and happiness scores.

## Random Forest Regressor
Used to capture nonlinear relationships and improve predictive performance through ensemble learning.

---

# Model Performance

| Model | MAE | RMSE | R² Score |
|---|---|---|---|
| Linear Regression | 0.4091 | 0.5373 | 0.7503 |
| Random Forest | 0.4023 | 0.5063 | 0.7783 |

---

# Key Findings

- Social support emerged as the strongest predictor of happiness scores.
- Healthy life expectancy and GDP per capita also demonstrated strong influence.
- Random Forest outperformed Linear Regression across all evaluation metrics.
- Happiness is influenced by both economic and social well-being factors.

---

# Repository Structure

```plaintext
world-happiness-machine-learning/
│
├── data/
├── notebook/
├── visuals/
├── report/
├── README.md
└── .gitignore
```

---

# Visualizations Included

- Correlation Heatmap
- Happiness Trends Over Time
- GDP vs Happiness Scatterplot
- Model Comparison Graph
- Feature Importance Graph

---

# Ethics and Limitations

This analysis uses country-level averages and may not fully capture individual experiences or cultural differences. Happiness is a subjective concept influenced by many measurable and non-measurable factors.

Machine learning models should support decision-making rather than replace human judgment.

---

# Future Improvements

Potential future improvements include:

- Testing additional machine learning models
- Adding more socioeconomic indicators
- Incorporating time-series forecasting methods
- Expanding the analysis with regional clustering techniques

---

# Author

JOSH ROTHMAN

ISOM 835 – Predictive Analytics and Machine Learning

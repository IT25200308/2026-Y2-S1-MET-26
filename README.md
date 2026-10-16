# 🏠 House Price Prediction Using Machine Learning

### A Comparative Study of Machine Learning Models for Real Estate Price Prediction

🌐 **[Try the Live Web Application](https://gr5wddcucocqsk5j8oemjn.streamlit.app/)**

## 📌 Project Overview

This project is a machine learning-based house price prediction system developed as part of a second-year Artificial Intelligence and Machine Learning (AIML) group project.

The system aims to predict residential property prices by analyzing property characteristics and applying supervised machine learning techniques.

Our team developed and compared **six machine learning models**, implemented a combined data preprocessing and feature engineering pipeline, and built an interactive **Streamlit web application** to demonstrate the prediction system.

The project covers the complete machine learning workflow, from data exploration and preparation to model evaluation and web application development.

---

## ✨ Key Highlights

- Developed and compared six supervised regression models.
- Analyzed a housing dataset containing 21,613 records.
- Implemented a combined preprocessing and feature engineering pipeline.
- Evaluated models using MAE, RMSE, and R².
- Identified CatBoost as the best-performing model, achieving an R² score of 0.9023.
- Developed and deployed an interactive web application using Streamlit.
- Collaborated as a six-member team throughout the development process.

---

## 🛠️ Technology Stack

| Category | Technologies |
|---|---|
| Programming Language | Python |
| Data Analysis | Pandas, NumPy |
| Data Visualization | Matplotlib, Seaborn |
| Machine Learning | Scikit-learn, XGBoost, LightGBM, CatBoost |
| Deep Learning | TabNet |
| Web Application | Streamlit |
| Deployment | Streamlit Community Cloud |
| Development Environment | Jupyter Notebook, Google Colab |
| Version Control | Git, GitHub |

---

## 📊 Dataset

The project uses a residential housing dataset containing various property-related attributes, including bedrooms, bathrooms, living area, property condition, and geographical information.

| Dataset Information | Details |
|---|---|
| Original Records | 21,613 |
| Original Columns | 21 |
| Processed Records | 21,613 |
| Processed Features | 92 |
| Target Variable | `price` |
| Final Processed Columns | 93 |

The dataset underwent preprocessing and feature engineering to prepare it for machine learning model development.

---

## 🔍 Exploratory Data Analysis & Preprocessing

Exploratory Data Analysis (EDA) was performed to understand the dataset, identify patterns, analyze relationships between variables, and examine factors influencing house prices.

### Data Preprocessing

The preprocessing workflow included:

- Data quality and missing-value analysis
- Identification and removal of unnecessary attributes
- Feature engineering and transformations
- Categorical variable encoding
- Numerical feature scaling
- Feature preparation for machine learning algorithms

A combined preprocessing pipeline was developed to integrate the selected preprocessing techniques.

The final processed dataset contained **92 predictor features and one target variable**.

---

## 🤖 Machine Learning Models

Six supervised machine learning models were implemented and evaluated.

| Model | Description |
|---|---|
| Linear Regression | Baseline regression model for learning linear relationships |
| XGBoost | Gradient boosting algorithm for complex predictive patterns |
| Extra Trees Regressor | Ensemble learning using randomized decision trees |
| TabNet | Deep learning architecture designed for tabular data |
| LightGBM | Efficient gradient boosting framework |
| CatBoost | Gradient boosting algorithm optimized for tabular datasets |

Each team member was responsible for implementing an individual model, while the final evaluation and comparison were carried out collaboratively.

### Model Development Workflow

`Dataset → EDA → Preprocessing → Feature Engineering → Model Training → Hyperparameter Tuning → Evaluation → Model Comparison → Web Application`

---

## 📈 Model Evaluation & Results

The performance of the six models was evaluated using three regression metrics:

**Mean Absolute Error (MAE)**

Measures the average absolute difference between predicted and actual house prices. Lower values indicate better prediction accuracy.

**Root Mean Squared Error (RMSE)**

Measures prediction errors while placing greater emphasis on larger errors. Lower values indicate better performance.

**Coefficient of Determination (R²)**

Measures the proportion of variation in house prices explained by the model. Higher values indicate better predictive performance.

### 🏆 Best-Performing Model — CatBoost

Based on the final test evaluation, CatBoost achieved the best overall performance among the six models.

| Evaluation Metric | CatBoost Result |
|---|---:|
| MAE | 66,033.26 |
| RMSE | 121,505.85 |
| R² Score | 0.9023 |

With an **R² score of 0.9023 (90.23%)**, CatBoost explained approximately 90.23% of the variation in house prices within the test dataset.

The results demonstrated the effectiveness of gradient boosting algorithms for structured housing data.

---

## 🌐 Streamlit Web Application

In addition to training and evaluating machine learning models, our team developed an interactive web application using **Streamlit**.

The application provides a user-friendly interface for interacting with the house price prediction system, demonstrating how machine learning models can be integrated into practical applications.

### 🚀 Live Demo

**[Launch the House Price Prediction Web App](https://gr5wddcucocqsk5j8oemjn.streamlit.app/)**

### Application Highlights

- Interactive web-based interface
- Integration of machine learning prediction functionality
- User-friendly interaction with the prediction system
- Cloud-hosted application accessible through a web browser
- Practical demonstration of the trained machine learning solution

The Streamlit application extends the project beyond model development by providing an accessible interface for demonstrating the system's predictive capabilities.

---

## 📉 Data Visualization & Analysis

Visualizations were used throughout the project to explore the dataset and evaluate model performance.

These included:

- Distribution of house prices
- Relationships between property characteristics and prices
- Correlation analysis
- Actual vs. predicted house price comparisons
- Regression model performance analysis
- Feature importance analysis where applicable

These visualizations supported data understanding, feature selection, and interpretation of model results.

---

## ⚖️ Ethical Considerations

The project considered several ethical aspects associated with machine learning-based property valuation.

**Location-Based Bias:** Geographic attributes may reflect existing socioeconomic differences between neighborhoods, potentially influencing predictions.

**Data Representation:** Uneven representation of property types, locations, and price ranges may affect the generalizability of the models.

**Prediction Limitations:** Predicted property prices are estimates and may differ from actual market values.

**Responsible Use:** Model predictions should support decision-making rather than replace professional property valuations or market assessments.

---

## 🤝 Team Collaboration

This project was developed collaboratively by a six-member AIML group.

Each team member was responsible for implementing and evaluating an individual machine learning model.

The team collaborated on:

- Exploratory Data Analysis
- Data preprocessing and feature engineering
- Development of the combined preprocessing pipeline
- Model evaluation and comparison
- Integration of the prediction system
- Streamlit application development
- Technical documentation and project presentation

The project provided practical experience in collaborative machine learning development, experimentation, and problem-solving.

---

## 👥 Contributors

| Team Member | Assigned Model |
|---|---|
| Agksheya | Linear Regression |
| Shathurshigah | XGBoost |
| Agksheya | Extra Trees Regressor |
| Lochana | TabNet |
| Moneesha | LightGBM |
| Vipusha | CatBoost |



---

## 🚀 Getting Started

### Prerequisites

- Python 3.x
- Jupyter Notebook or Google Colab
- Required machine learning libraries
- Streamlit for running the web application locally

### Running the Project

1. Clone or download the repository.
2. Install the required Python dependencies.
3. Open the relevant notebooks in Jupyter Notebook or Google Colab.
4. Configure the dataset paths according to the repository structure.
5. Execute the preprocessing and model training notebooks in the appropriate order.
6. Review the evaluation metrics and model comparison results.

### Accessing the Web Application

The deployed application can be accessed directly without installing the project locally.

🌐 **[Open the Live Streamlit Application](https://gr5wddcucocqsk5j8oemjn.streamlit.app/)**

---

## 🎓 Project Background

This project was developed as part of a **second-year, first-semester Artificial Intelligence and Machine Learning module**.

It demonstrates the practical application of supervised machine learning, data preprocessing, feature engineering, regression analysis, model evaluation, and interactive web application development.

Through this project, the team gained experience in developing an end-to-end machine learning solution, comparing different algorithms, and presenting predictive results through a deployed application.

---

**🏠 House Price Prediction Using Machine Learning — Turning Housing Data into Predictive Insights.**

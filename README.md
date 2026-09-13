# IT2011 Artificial Intelligence and Machine Learning Group Project

## Project Title
House Price Prediction using the King County House Sales Dataset

## Module
IT2011 - Artificial Intelligence and Machine Learning

## Dataset
King County House Sales Dataset

The original dataset contains **21,613 records and 21 attributes** related to residential property sales, including house price, living area, lot size, number of bedrooms and bathrooms, location information, construction year, renovation year, and other property characteristics.

The target variable for the prediction task is:

`price`

---

## Project Overview

This project focuses on preparing the King County House Sales dataset for machine learning-based house price prediction.

Each group member implemented an individual preprocessing technique. These preprocessing contributions were then integrated into a single combined preprocessing pipeline.

The combined pipeline performs:

1. Missing value and duplicate inspection
2. Feature engineering
3. Outlier analysis
4. Log transformation and feature scaling
5. Categorical encoding
6. Final validation
7. Generation of a model-ready processed dataset

---

## Group Member Contributions

| IT Number | Member | Preprocessing Contribution |
|---|---|---|
| IT25103558 | Vipusha V. | Missing Value and Duplicate Handling |
| IT25103613 | Monessha S. | Outlier Analysis |
| IT25103615 | Perera G.A.T.L. | Normalization and Scaling |
| IT25103618 | Shathurshigah R. | Categorical Encoding |
| IT25200308 | Agksheya B. | Feature Engineering |

---

## Repository Structure

```text
2026-Y2-S1-MET-26/
│
├── README.md
├── group_pipeline.ipynb
│
├── data/
│   ├── raw/
│   │   └── kc_house_data.csv
│   └── external/
│
├── notebooks/
│   ├── IT25103558_MISSING__AND_DUPLICATION.ipynb
│   ├── IT25103613_Preprocessing_EDA_Outliers.ipynb
│   ├── IT25103615_normalization_and_scaling.ipynb
│   ├── IT25103618_EncodingCategorical.ipynb
│   └── IT25200308_Feature_Engineering.ipynb
│
└── results/
    ├── eda_visualizations/
    ├── logs/
    └── outputs/
        └── final_processed_house_data.csv

**Project Overview**

This project evaluates and compares the performance of multiple regression-based machine learning models to predict honey production levels and identify key economic and environmental drivers influencing production trends. The objective is to demonstrate how data science and machine learning can support data-driven decision-making in an applied economic context.

The project was completed as part of an MSc in Data Management and is framed as a predictive analytics use case, and it is a purely academic exercise.


**Problem Statement**

Honey production has shown declining and volatile trends over time, raising questions around:

1. Which factors most strongly influence production levels?

2. How accurately can historical data be used to forecast production outcomes?

3. Which modeling approaches provide the best balance between performance, interpretability, and robustness?

_This project addresses these questions using machine learning regression techniques applied to historical production data._


**Data Description**

- Historical honey production dataset covering multiple years

- Features include production levels, colony metrics, and related explanatory variables

- Data preprocessing included:
    - Data cleaning and validation
    - Feature selection and transformation
    - Train–test splitting for model evaluation

_(Note: Dataset is used for educational and analytical purposes.)_


**Methodology**

The following machine learning models were implemented and benchmarked:

- Linear Regression

- Decision Tree Regression

- Random Forest Regression

- XGBoost Regression

Key steps:

- Feature analysis and basic feature engineering

- Model training and evaluation using consistent validation logic

- Comparative assessment of model performance to identify the most suitable approach



**Model Evaluation Approach**

Models were evaluated using standard regression performance metrics and cross-comparison logic.
Rather than focusing solely on raw accuracy, the evaluation emphasized:

- Model stability

- Ability to capture non-linear relationships

- Practical interpretability for decision support

_This approach reflects real-world analytics use cases, where model choice must balance performance with explainability._



**Key Insights**

- Tree-based and ensemble models outperformed simpler linear approaches in capturing complex production patterns.

- Feature analysis highlighted key drivers influencing honey production variability.

- Machine learning models can meaningfully support forecasting and scenario analysis in agricultural and economic contexts.



**How to Use This Notebook**

1. Open the Jupyter notebook:
    Machine_Learning_Honey_Project_final.ipynb

2. Run cells sequentially to reproduce the analysis.

3. Review model comparison sections for performance insights and interpretation.

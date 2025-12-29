##Project Overview
Mental health disorders represent a significant and growing public health challenge. This project develops an interpretable machine-learning pipeline to forecast serious psychological distress (SPD) at population level using data from the U.S. National Health Interview Survey (NHIS).

The study prioritises transparency, ethical use, and interpretability, combining predictive modelling with SHAP-based explanations and an interactive dashboard to support non-technical stakeholders.

This work was completed as part of an MSc Data Science / Computing MSc project.

Project Objectives
Identify demographic, socioeconomic, and health-related factors associated with serious psychological distress

Train and evaluate multiple supervised machine-learning models for mental health risk prediction

Apply interpretable machine-learning techniques (SHAP) to explain model behaviour

Present results through an interactive dashboard suitable for public health analysis.

##Data Source
National Health Interview Survey (NHIS) – Adult datasets (2021–2023)

Publicly available, anonymised survey data provided by the U.S. Centers for Disease Control and Prevention (CDC)

Target variable:

K6SPD_A – Serious Psychological Distress indicator derived from the Kessler-6 scale


##Methodology
The project follows the CRISP-DM framework:

Business Understanding – Defining SPD as a binary prediction task

Data Understanding – Exploring NHIS structure and data quality

Data Preparation – Cleaning and merging multi-year survey data

Modelling – Training multiple classifiers and tuning performance

Evaluation – ROC-AUC, F1-score, precision and recall

Deployment (Conceptual) – Dashboard-based decision support


##Tools Used
Python
pandas, numpy
scikit-learn
SHAP
matplotlib, seaborn
Power BI

##Models Implemented
Six supervised machine-learning algorithms were evaluated:

Logistic Regression
Decision Tree
Random Forest
Gradient Boosting (primary model)
Support Vector Machine (SVM)
K-Nearest Neighbours (KNN)

Gradient Boosting achieved the strongest overall performance.


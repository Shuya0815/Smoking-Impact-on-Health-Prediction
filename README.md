# Smoking-Impact-on-Health-Prediction
1. Problem Statement
• Objective: Smoking is a significant public health issue linked to numerous diseases such as lung cancer,
cardiovascular disease, and diabetes. This project aims to develop a machine learning model capable of
detecting smoking behaviors based on body signals and health metrics. The goal is to enable early
intervention and personalized health strategies, ultimately reducing smoking-related health risks.
2. Data Collection & Analysis
• Data Source: The dataset is sourced from Kaggle (Body Signal of Smoking). It contains 27 features,
including demographic details, biometric measures, and smoking status (target variable).
• Data Exploration:
Key Features: Gender, age, height, weight, waist circumference, blood pressure (systolic and relaxation),
fasting blood sugar, cholesterol, triglyceride levels, and oral health indicators.
Target Variable: Smoking (binary: 1 for smokers, 0 for non-smokers).
• Data Characteristics: Shape: 55,692 rows and 27 columns. Types: 18 float64, 6 int64, and 3 object
columns.
3. Survey of Existing Solutions
• Literature Review: Studies focus on using wearable devices or limited physiological metrics (e.g., heart
rate, blood pressure) to detect smoking.
Machine learning models like logistic regression and random forest are common.
Few approaches leverage comprehensive health metrics in combination with deep learning.
• Gap Analysis: Feature Limitation: Existing models often underutilize diverse health metrics like
cholesterol or oral health indicators.
Generalizability: Models lack validation across diverse populations, leading to reduced reliability.
Advanced Models: Limited exploration of ensemble or deep learning models for this problem.
4. Model Selection Process
• Proposed Models: Logistic Regression, Random Forest, Gradient Boosting, Deep Learning Models:
Fully Connected Neural Network (FCNN) or AutoEncoders for complex pattern detection.
• Model Evaluation & Interpretation: Primary Metrics: AUC-ROC to evaluate classification capability.
Secondary Metrics: Accuracy, F1-score for balanced assessment of performance.
5. Healthcare Impact & Implementation
• Use Case: Healthcare providers can use the model to identify smokers in routine health check-ups and
offer personalized cessation programs.
• Decision Support: The model provides actionable insights, enabling public health initiatives to target atrisk
groups effectively. It also serves as an educational tool for patients to understand smoking's impact
on their physiological metrics.

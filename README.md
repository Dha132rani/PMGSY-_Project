Intelligent Classification of Rural Infrastructure Projects




Problem Statement 35 - Intelligent Classification of Rural Infrastructure Projects
    The Pradhan Mantri Gram Sadak Yojana (PMGSY) is a flagship rural development program in India, initiated to provide all-weather road connectivity to eligible unconnected habitations. Over the years, the program has evolved through different phases or schemes (PMGSY-I, PMGSY-II, RCPLWEA, etc.) — each with potentially distinct objectives, funding mechanisms, and project specifications.
For government bodies, infrastructure planners, and policy analysts, efficiently categorizing thousands of ongoing and completed projects is crucial for:
Effective monitoring
Transparent budget allocation
Assessing the long-term impact of schemes
Manual classification is time-consuming, prone to errors, and difficult to scale.
The goal is to design, build, and evaluate a Machine Learning model that can automatically classify a road or bridge construction project into its correct PMGSY scheme based on its physical and financial characteristics.

Objective: 
Develop an AI-powered classification system that can predict the PMGSY scheme category for any given rural infrastructure project using available structured data.

Dataset: 
We are using the AI Kosh dataset provided by the Ministry of Rural Development, Government of India:
Pradhan Mantri Gram Sadak Yojana Dataset

Technology Stack: 
IBM Cloud Lite Services (Mandatory)
Python (Data processing, model building, and evaluation)
Pandas, NumPy (Data handling)
Scikit-learn (Machine Learning algorithms)
Matplotlib / Seaborn (Data visualization)

Approach: 

Data Collection – Download and load the dataset from the official AI Kosh portal.
Data Preprocessing – Clean, transform, and handle missing or inconsistent values.
Exploratory Data Analysis (EDA) – Identify patterns, correlations, and trends.
Feature Engineering – Select and transform features for better model performance.
Model Building – Train various classification algorithms such as:
 Logistic Regression
 Decision Trees 
 Random Forest
 Gradient Boosting
Model Evaluation – Use accuracy, precision, recall, and F1-score metrics.
Deployment – Deploy the best-performing model on IBM Cloud Lite for real-time prediction.

Expected Outcomes: 
Automated, scalable classification of PMGSY projects.
Reduction in manual classification errors.
Improved transparency in government reporting and budget allocation.

License: 
This project is developed for educational and research purposes and is subject to the terms of the dataset provider.

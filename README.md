# Heart-Disease-Spark-China

A Big Data healthcare analytics project using Apache Spark SQL and Spark MLlib to analyze cardiovascular disease (CVD) risk factors among over 239,266 individuals in China. The study investigates how six key factor groups — demographics, lifestyle behaviors, underlying medical conditions, genetic and environmental factors, socioeconomic status, and access to healthcare — contribute to the likelihood of heart disease. Using both SQL queries and machine learning models, the project provides data-driven insights for public health intervention and disease prevention.

## Project Objectives

- Analyze a large-scale simulated healthcare dataset from China to uncover significant risk factors of cardiovascular disease (CVD).
- Apply Spark SQL for data querying and exploration on big data.
- Implement machine learning models (K-means clustering, Logistic Regression, Decision Tree, SVM) using Spark MLlib to identify at-risk groups and predict heart disease.
- Provide insights for public health policy and preventive strategies.

## Tools Used

- Apache Hadoop (for environment setup)
- Apache Spark (Spark SQL & Spark MLlib)
- Python Libraries: Pandas, NumPy, Matplotlib, Seaborn, PySpark
- PyCharm (Jupyter Notebook)

## Dataset

- Name: Heart Attack Risk Dataset of China
- Source: Kaggle
- Size: ~239,266 records
- Features: Demographics, lifestyle behaviors, clinical conditions, environmental exposure, healthcare access, socioeconomic status, and cardiovascular history.
  
### Outcome

- Spark SQL enabled fast querying over large-scale health data to reveal patterns in heart disease prevalence.
- Machine Learning results:
  
K-Means clustering successfully grouped individuals into distinct health profiles.

Logistic Regression provided the most reliable predictive performance with high recall.

Decision Tree and SVM showed competitive but slightly lower performance metrics.
- Generated health risk profiles to help identify vulnerable populations for targeted interventions.

## Key Insights Presented

- Strong CVD predictors: Older age, rural residency, stress, smoking, alcohol consumption, chronic conditions (e.g., hypertension, diabetes).
- Weak/no association: Gender, family history, diet score.
- Environmental and access issues: Air pollution and limited healthcare access were associated with higher heart disease prevalence.
- Clustering analysis: Revealed two major health clusters with distinct risk profiles.
- Policy Implication: Suggests prioritizing healthcare for elderly, rural populations, and individuals with chronic conditions.

#  Optimizing Semiconductor Manufacturing Through Advanced Feature Selection and Predictive Modeling:

Designed and implemented a robust feature selection and predictive modeling pipeline using the SECOM semiconductor manufacturing dataset. Applied advanced techniques like PCA and Recursive Feature Elimination (RFE) for dimensionality reduction, and employed SMOTE and ADASYN to resolve class imbalances. Integrated Bayesian optimization for hyperparameter tuning across models, including Random Forest, Logistic Regression, SVM, and XGBoost. Delivered a high-performing model with precision (0.92), recall (0.89), and F1 score (0.90), significantly improving yield prediction accuracy, reducing production costs, and enhancing throughput efficiency.

## Investogator: Sam Gharib-Nezhad

[![](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ehsan-gharib-nezhad/) 
[![](https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/exoEhsan) 
[![](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/EhsanGharibNezhad?tab=repositories) 



Semiconductor manufacturing is a complex process involving hundreds of steps, and slight variations can lead to defects in chips. Machine learning (ML) has the potential to improve various problems in the semiconductor industry, especially in areas where vast amounts of data are generated or where precision is crucial. ML can help:
   
   
## Project Name: 
"Optimizing Semiconductor Manufacturing Through Advanced Feature Selection and Predictive Modeling"

### Description
Led a project aimed at enhancing semiconductor manufacturing processes by applying advanced feature selection and predictive modeling techniques to the SECOM dataset. The dataset contains 1,567 samples, each with 591 features, with outcomes categorized as pass (0.1) or fail (1) based on in-house line testing.

### Key Contributions:

Feature Selection and Reduction: Implemented various feature reduction techniques, including Principal Component Analysis (PCA) and Recursive Feature Elimination (RFE), to isolate the most relevant signals impacting product yield. This step was crucial in filtering out irrelevant and noisy features from the dataset.

### Handling Class Imbalance: 
Applied oversampling methods such as SMOTE and ADASYN to address class imbalance, ensuring that both pass and fail classes were adequately represented in the training data.

###  Model Development and Optimization: 
Utilized a range of machine learning models, including Random Forest, Logistic Regression, Support Vector Machines (SVM), and XGBoost. Conducted Bayesian optimization for hyperparameter tuning to enhance model performance and accuracy.

###  Evaluation and Insights: 
Assessed model performance using cross-validation and various metrics, including accuracy, precision, recall, and F1 score. Compared results with and without feature reduction techniques to identify the impact on predictive accuracy. Provided actionable insights to process engineers, improving understanding of key factors affecting yield and guiding decisions to optimize manufacturing processes.


![image](https://github.com/user-attachments/assets/d54667a2-1697-4162-90e6-a14323660fec)


### Dataset Description

The SECOM dataset represents a selection of features from a semiconductor manufacturing process, where each example corresponds to a single production entity with associated measured features. The labels indicate a pass/fail result from in-house line testing, with 0.1 representing a pass and 1 representing a fail. Additionally, a timestamp is included for each test point.

### Objective
The goal is to use feature selection techniques to rank features based on their influence on overall product yield. By identifying causal relationships between features and yield outcomes, the key features contributing to process variability can be pinpointed.

### Evaluation
Results will be evaluated based on the relevance of selected features to predictability, using error rates as the primary metric. Cross-validation is recommended to ensure robust performance assessments. Baseline results for initial analysis were obtained using basic feature selection techniques, paired with a kernel ridge classifier and 10-fold cross-validation.

### Baseline Results
Initial preprocessing involved standardizing the dataset and removing constant features. A simple classifier was then applied to the top 40 ranked features, selected through feature selection algorithms. The model was evaluated using 10-fold cross-validation, with the balanced error rate (BER) as the performance metric.

### SECOM Dataset Overview:

    - Examples: 1567
    - Features: 591
    - Failures: 104
    
![image](https://github.com/user-attachments/assets/8ca50d54-8173-4b94-8399-1e1e77e4ee03)

![image](https://github.com/user-attachments/assets/c4b8d8ef-84fd-44a7-bf14-ce44641593ab)


![image](https://github.com/user-attachments/assets/4b780f22-1b14-4b40-bc38-7d339bfd981c)


    


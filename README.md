#  Optimizing Semiconductor Manufacturing Through Advanced Feature Selection and Predictive Modeling:



## Investogator: Ehsan (Sam) Gharib-Nezhad

[![](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ehsan-gharib-nezhad/) 
[![](https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/exoEhsan) 
[![](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/EhsanGharibNezhad?tab=repositories) 


## Summary: 
Designed and implemented a robust feature selection and predictive modeling pipeline using the SECOM semiconductor manufacturing dataset. Applied advanced techniques like PCA and Recursive Feature Elimination (RFE) for dimensionality reduction, and employed SMOTE to resolve class imbalances. Integrated Bayesian optimization for hyperparameter tuning across models, including Random Forest, Logistic Regression, SVM, and XGBoost. Delivered a high-performing model with precision (0.92), recall (0.89), and F1 score (0.90), significantly improving yield prediction accuracy, reducing production costs, and enhancing throughput efficiency. Key steps are:

 1. **Feature Selection and Reduction**: Implemented various feature reduction techniques, including Principal Component Analysis (PCA) and Recursive Feature Elimination (RFE), to isolate the most relevant signals impacting product yield. This step was crucial in filtering out irrelevant and noisy features from the dataset.

 2. **Handling Class Imbalance**: Applied oversampling methods such as SMOTE and ADASYN to address class imbalance, ensuring that both pass and fail classes were adequately represented in the training data.

 3. **Model Development and Optimization**: Utilized a range of machine learning models, including Random Forest, Logistic Regression, Support Vector Machines (SVM), and XGBoost. Conducted Bayesian optimization for hyperparameter tuning to enhance model performance and accuracy.

   4. **Evaluation and Insights**: Assessed model performance using cross-validation and various metrics, including accuracy, precision, recall, and F1 score. Compared results with and without feature reduction techniques to identify the impact on predictive accuracy. Provided actionable insights to process engineers, improving understanding of key factors affecting yield and guiding decisions to optimize manufacturing processes.


### Dataset Description

The SECOM dataset represents a selection of features from a semiconductor manufacturing process, where each example corresponds to a single production entity with associated measured features. The dataset contains 1,567 samples, each with 591 features, with outcomes categorized as pass (0.1) or fail (1) based on in-house line testing. The labels indicate a pass/fail result from in-house line testing, with 0.1 representing a pass and 1 representing a fail. Additionally, a timestamp is included for each test point.

#### SECOM Dataset Overview:

    - Examples: 1567
    - Features: 591
    - Failures: 104


## Domain Knowledge: 
Semiconductor manufacturing is an intricate process involving hundreds of precise steps. Even slight variations during production can result in defects, making it essential to maintain strict control over quality. With the growing complexity and the vast amounts of data generated at every stage, machine learning (ML) has emerged as a powerful tool to address critical challenges. ML can enhance defect detection, optimize yield, and ensure process precision, significantly improving efficiency in semiconductor production.

To get a broad understanding of how this intricate process transforms tiny grains of sand into functional wafers, watch the following short video.

[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/Bu52CE55BN0/0.jpg)](https://www.youtube.com/watch?v=Bu52CE55BN0)


The dataset contains 1567 examples, 591 features, and 104 failures.
    
![image](https://github.com/user-attachments/assets/8ca50d54-8173-4b94-8399-1e1e77e4ee03)




![image](https://github.com/user-attachments/assets/c4b8d8ef-84fd-44a7-bf14-ce44641593ab)


![image](https://github.com/user-attachments/assets/4b780f22-1b14-4b40-bc38-7d339bfd981c)


    


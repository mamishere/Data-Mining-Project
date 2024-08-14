# **Predictive Modeling of Chest Pain and Shortness of Breath in a Diverse Population: A Multivariate Analysis of Health and Lifestyle Factors**  

<div style="text-align: justify">

## Overview and Question Explanations

This project focuses on developing predictive models to assess the likelihood of individuals experiencing chest pain and shortness of breath, symptoms often linked to serious cardiovascular conditions such as heart attacks. The analysis leverages a diverse dataset from the National Health and Nutrition Examination Survey (NHANES), which includes a wide range of demographic, health, and lifestyle variables. The primary objective is to create accurate and reliable models that can help in identifying individuals at risk, thus supporting early intervention and preventive healthcare measures.

## Dataset Introduction and the Process of Merging

The datasets utilized in this project were sourced from the NHANES, a program of studies designed to assess the health and nutritional status of adults and children in the United States. These datasets cover various aspects, including demographic information, health indicators, and lifestyle factors, providing a comprehensive view of the population under study.

The initial step involved selecting the relevant datasets from NHANES and merging them into a single cohesive dataframe. This process required careful consideration to ensure that all critical features were preserved and accurately aligned. The merging was conducted based on common identifiers such as participant IDs, which allowed for the integration of multiple datasets into a unified structure. After merging, the data was superficially prepared to make it suitable for further analysis.

## The Learning Process and the Results

The learning process began with thorough data preprocessing, essential for ensuring the models' accuracy and reliability. This step involved the following key activities:

1. **Handling Missing Values:** Various imputation techniques were employed to address missing data, ensuring that the dataset remained comprehensive and robust.

2. **Scaling Numeric Features:** Numeric features were scaled to standardize the data, making it suitable for machine learning algorithms that are sensitive to feature magnitude.

3. **Encoding Categorical Variables:** Categorical variables were encoded into numerical formats, allowing them to be used effectively by the machine learning models.

With the preprocessed data in hand, multiple machine learning models were implemented, including Logistic Regression, Decision Tree, Random Forest, Naive Bayes, and a Multi-Layer Perceptron. Each model was trained on the dataset and evaluated using metrics such as accuracy, precision, recall, and F1 score. The results highlighted the strengths and weaknesses of each model, providing valuable insights into the most effective approaches for predictive modeling in this context.

</div>


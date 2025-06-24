Title: 💧Predicting Water Potability with XGBoost & SMOTE: A Comparative Study on Balanced & Imbalanced ML Models

Citation:
> Saisheshadhri, Varshaa Sai Sripriya, Chellamani, Ganesh Kumar, & Premalatha, G. (2023). *Machine Learning Methods for Balanced and Imbalanced Datasets to Predict Consumable Water*. ICRTDA, 149–156. [DOI: 10.13052/rp-9788770040723.029](https://www.researchgate.net/publication/373908648_Machine_Learning_Methods_for_Balanced_and_Imbalanced_Datasets_to_Predict_Consumable_Water)

Description:
This repository presents an advanced machine learning pipeline for predicting potable (drinkable) water using real-world quality indicators and handling class imbalance through data augmentation techniques like SMOTE and ADASYN. This work addresses a critical global problem with practical ML deployment implications.
🔍 Key Features:

    Problem Addressed: Potability classification from physicochemical water parameters considering real-world class imbalance (minority potable cases).

    Data: Synthetic dataset (5,000 samples) curated using WHO water quality guidelines — includes features like pH, hardness, TOC, trihalomethanes, sulfate, and conductivity.

    Models Used:

        Logistic Regression, Decision Trees, Random Forest

        XGBoost, SVM, AdaBoost, Gradient Descent

        k-NN

    Handling Imbalanced Data:

        Comparative evaluation of original vs. oversampled data using SMOTE and ADASYN

        Performance validation through precision, recall, F1-score, accuracy

        Demonstrated that XGBoost + SMOTE yielded best generalization

    EDA & Visualization:

        Heatmaps, boxplots, correlation analysis on potability vs water quality factors

        Outlier treatment and scaling via StandardScaler

    Result:

        ~78% accuracy in imbalanced setup → improved to ~89% with XGBoost+SMOTE

        Precision and recall tradeoffs documented for each class

🧠 Novelty & Impact:

    Introduces data-centric approach to a traditionally algorithmic problem

    Highlights risks of biased ML decision-making on minority (potable) class

    Leverages explainable AI principles to show decision boundaries and sampling impact

    Demonstrates real-world applicability of ML to public health and environmental risk

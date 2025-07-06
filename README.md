# Project Overview

This repository contains the complete code and final report for my ST3189 Machine Learning coursework. The project consists of three major machine learning tasks—Unsupervised Learning, Regression, and Classification—each executed on separate real-world datasets sourced from Kaggle and the UCI Machine Learning Repository. The aim was to perform end-to-end data analysis and model development to answer practical research questions with strong interpretability and actionable insight.

---

# Project Structure

### 1. Unsupervised Learning: Customer Segmentation  
- **Dataset:** [Customer Personality Analysis (Kaggle)](https://www.kaggle.com/datasets/imakash3011/customer-personality-analysis/data)  
- **Objective:**
  - Identify distinct customer segments using KMeans and Hierarchical Clustering  
  - Perform dimensionality reduction using PCA  
  - Validate clustering using Elbow Method and Silhouette Scores  
  - Profile each cluster using behavioural and demographic attributes  
- **Key Insights:**
  - Four meaningful customer personas were derived  
  - Clear marketing strategies proposed for each segment  
  - KMeans offered better interpretability and separation compared to Hierarchical Clustering

---

### 2. Regression: Predicting Life Expectancy  
- **Dataset:** [WHO Life Expectancy Dataset (Kaggle)](https://www.kaggle.com/datasets/lashagoch/life-expectancy-who-updated)  
- **Objective:**
  - Predict life expectancy using socioeconomic and health indicators  
  - Apply models: Multiple Linear Regression, Ridge, Lasso, Random Forest, Gradient Boosting  
  - Use log transformation and IQR capping for skewed features  
  - Evaluate using MAE, RMSE, R², and Cross-Validation  
- **Key Insights:**
  - Random Forest achieved the best accuracy (R² = 0.987)  
  - Top drivers: under-5 mortality, adult mortality, GDP, HIV prevalence, and education  
  - Feature exclusion revealed new latent influences on life expectancy

---

### 3. Classification: Predicting Term Deposit Subscriptions  
- **Dataset:** [Bank Marketing Dataset (UCI)](https://archive.ics.uci.edu/ml/datasets/bank+marketing)  
- **Objective:**
  - Predict whether a customer will subscribe to a term deposit  
  - Preprocessing: handling ‘unknowns’, aggregating categories, feature engineering  
  - Models used: Logistic Regression, Decision Tree (base and pruned), Random Forest, XGBoost  
  - Address class imbalance using `class_weight` and `scale_pos_weight`  
- **Key Insights:**
  - XGBoost provided the best balance of recall (0.59) and F1-score (0.46)  
  - Key predictors: `nr.employed`, `age`, `euribor3m`, `cons.conf.idx`  
  - Contact timing and prior engagement were crucial indicators of subscription

---

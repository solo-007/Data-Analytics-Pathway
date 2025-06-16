# Client Term Deposit Subscription Prediction

## **Project Overview**
This project analyzes client subscription behavior for term deposits, using machine learning to predict whether a customer will subscribe (`y=1`) or not (`y=0`). The dataset includes demographic, financial, and campaign-related features, offering insights to optimize marketing strategies and improve customer engagement.

---

## **Workflow Overview**
### **Exploratory Data Analysis (EDA) & Preprocessing**
- **Data Inspection:** Examined missing values, feature distributions, and potential correlations.
- **Preprocessing:** Handled missing values, encoded categorical variables, and standardized numerical features.
- **EDA Insights:** Identified key patterns influencing subscriptions, including job type, education, and previous campaign success.

### **Feature Transformation & Model Training**
- **Feature Engineering:** Applied scaling (`StandardScaler`) and categorical encoding (`OneHotEncoder`).
- **Model Training:** Built predictive models using **Logistic Regression, Random Forest, and XGBoost**.
- **Hyperparameter Tuning:** Improved model performance through grid search optimization.

### **Model Evaluation & Comparison**
- **Evaluation Metrics:** Accuracy, precision, recall, F1-score, and ROC-AUC.
- **Cross-Validation:** Ensured robust generalization of models across different dataset splits.
- **Best Performing Model:** **XGBoost**, with a strong balance of accuracy (`0.8897`), precision (`0.6205`), recall (`0.2218`), and AUC (`0.7671`).

### **Interpretation & Final Report**
- **Feature Importance:** Identified significant predictors like job type, past campaign success, and balance.
- **Error Analysis:** Examined misclassified cases to refine strategies.
- **Final Deliverable:** A structured report summarizing findings, insights, and recommendations.

---

## **Key Findings & Business Implications**
 **Previous campaign success strongly predicts future subscriptions.**  
 **Cellular communication outperforms telephone contacts in marketing effectiveness.**  
 **Higher balance and education levels increase subscription likelihood.**  
 **XGBoost offers the best balance for predictive accuracy and feature importance.**  

---

## **Next Steps & Recommendations**
Further improve model performance using **advanced feature engineering**.  
Implement **personalized marketing strategies** based on high-potential customer segments.  
Deploy the **XGBoost model for real-time predictions** in marketing campaigns.  

 **Files:**  
- `ExpDataAna.ipynb` – EDA & Preprocessing  
- `PredModel.ipynb` – Model Training, Model Evaluation, Final Report  
- `bank-full.csv/` – Processed dataset  
- `models/` – Trained model files  

 **License:** This project is open-source and licensed under the **MIT License**.

---

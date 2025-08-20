# Credit-Default-Risk-Prediction-with-Explainable-Machine-Learning
This repository contains the research paper and implementation code for **“Credit Default Risk Prediction with Explainable Machine Learning: Integrating Socioeconomic Interaction Effects.”**  
The project evaluates both traditional and modern machine learning methods for predicting credit default risk, with a focus on model interpretability and socioeconomic interaction effects.

---

## 📄 Project Overview
Accurately predicting credit default risk is critical for lenders, regulators, and policymakers.  
This project benchmarks six supervised learning algorithms on a real-world loan dataset of **28,638 applicants**:

- Logistic Regression  
- Decision Tree  
- Random Forest  
- Gradient Boosting  
- AdaBoost  
- K-Nearest Neighbors  

### Key Contributions
- **Performance Comparison**: Ensemble-based models (Random Forest, Gradient Boosting) outperform Logistic Regression in accuracy, recall, and AUC-ROC.  
- **Explainability**: SHAP (SHapley Additive exPlanations) provides insights into the most influential features such as loan-to-income ratio, interest rate, and homeownership status.  
- **Socioeconomic Insights**: Interaction effects between renter status and loan purpose (e.g., debt consolidation, home improvement) are identified as critical differentiators of default risk.  


---

## ⚙️ Methods
1. **Data Preprocessing**  
   - Cleaned and filtered 28,632 valid loan records.  
   - Handled missing values and encoded categorical variables.  

2. **Model Development**  
   - Implemented six classifiers under a consistent evaluation framework.  
   - Applied **stratified 5-fold cross-validation** to address class imbalance.  

3. **Evaluation Metrics**  
   - Accuracy  
   - Precision, Recall, F1 (for default class)  
   - ROC AUC (primary metric)  

4. **Explainability**  
   - Applied SHAP for global and local interpretability.  
   - Highlighted nonlinear and interactional effects.  

---

## 📊 Key Results
- **Gradient Boosting** achieved the best performance (Accuracy = 92.5%, AUC = 0.930).  
- **Random Forest** closely followed with robust ROC performance.  
- **Logistic Regression** remained interpretable but underperformed in recall (0.539).  
- SHAP confirmed the importance of **loan-to-income ratio**, **interest rate**, and **housing tenure** as key predictors.  

---

## 🚀 How to Use
Clone the repository:
```bash
git clone https://github.com/<your-username>/Credit-Default-Risk-Prediction-with-Explainable-Machine-Learning.git
cd Credit-Default-Risk-Prediction-with-Explainable-Machine-Learning


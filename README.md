# **AI Governance & Risk Assessment: Heart Disease Prediction Model**

## **📌 Project Overview**
This project evaluates an AI-driven **clinical decision support model** for heart disease prediction. It incorporates **machine learning, risk assessment, and AI governance principles** to ensure fairness, transparency, and ethical use in healthcare settings.

## **📊 Dataset Used**
- **Type:** Synthetic clinical dataset (1,000 patient records)
- **Features:** Age, Gender, Blood Pressure, Cholesterol, Glucose Levels, Smoking Status, BMI, Exercise Hours/Week
- **Target Variable:** **Heart Disease (1 = Present, 0 = Absent)**
- **Generated using Python’s NumPy & Faker libraries**

## **⚙️ Machine Learning Model**
- **Algorithm:** Logistic Regression & Random Forest
- **Accuracy:** 93%
- **Top Features Influencing Predictions:**
  - **Cholesterol Level** (High impact)
  - **Age** (High impact)
  - **Smoking Status** (Moderate impact)
  - **Systolic Blood Pressure** (Moderate impact)
  - **BMI** (Low impact)

## **🔍 Bias & Fairness Analysis**
- **Gender Performance Differences:** Model performed slightly better for **male patients** than **female patients**.
- **False Positives & Negatives:** Evaluated real-world risks of misclassification.
- **AI Risk Considerations:** Potential for **overdiagnosis or underdiagnosis** based on dataset balance.

## **📈 Model Performance Metrics**
- **Confusion Matrix:** Assessed classification errors
- **ROC Curve & AUC Score:** Evaluated model confidence in predictions
- **Precision, Recall, F1-Score:** Measured prediction reliability

## **⚠️ Ethical & Risk Considerations**
| Scenario | Risk |
|----------|------|
| **False Positives** | Unnecessary stress, costly medical tests, over-medication |
| **False Negatives** | Missed diagnoses, delayed treatment, potential health risks |

## **📝 AI Governance & Recommendations**
✅ **Improve Gender Fairness:** Balance training data to enhance recall for female patients.
✅ **Threshold Tuning:** Adjust classification thresholds to minimize false negatives.
✅ **Human-in-the-Loop Validation:** Ensure final decisions involve clinical review.
✅ **Explainability Techniques:** Implement SHAP for feature interpretability.
✅ **Regulatory Compliance:** Align AI model with **HIPAA and FDA** guidelines.

## **📂 Files in Repository**
- **`synthetic_heart_disease_human_readable.csv`** → Synthetic patient dataset
- **`heart_disease_model.ipynb`** → Jupyter Notebook with model training & analysis
  


## **🚀 How to Run This Project**
### **1️⃣ Install Dependencies**
```bash
pip install pandas numpy scikit-learn matplotlib seaborn faker
```

### **2️⃣ Run the Jupyter Notebook**
Open and execute **`heart_disease_model.ipynb`** in Jupyter Notebook or Google Colab.

### **3️⃣ Explore the Data & Model Outputs**
- Modify dataset size or features in the data generation step.
- Tune hyperparameters for improved model performance.

## **🔗 Project Link**
https://github.com/jreed2021/AI_Governance_Heart_Disease_Model/edit/main/README.md

## **👤 Author**
- **Janessa Reed**
- **Email:** reed.janessa21@gmail.co,,
- **LinkedIn:** https://www.linkedin.com/in/janessa-clark-reed-els-aab-413263111/


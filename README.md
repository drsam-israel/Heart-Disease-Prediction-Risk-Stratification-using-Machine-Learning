# Heart-Disease-Prediction-Risk-Stratification-using-Machine-Learning
Machine learning–based heart disease prediction and interpretable risk stratification systems for clinical decision support.

## Overview
Heart disease remains a leading cause of mortality worldwide, making early and accurate detection essential for improving patient outcomes.  
This repository presents **two complementary machine learning–based healthcare projects** focused on **heart disease prediction and risk stratification**, designed strictly as **clinical decision-support systems**.

The work combines:
- **High-performance ensemble modeling** (Random Forest, XGBoost)
- **Clinically interpretable modeling** (Decision Tree–based protocol)

---

## Repository Contents
heart-disease-ml-risk-stratification/
│
├── README.md
│
└── docs/
    ├── HEART_DISEASE_PREDICTION_USING_MACHINE_LEARNING_MODELS.pdf
    └── HEART_DX_RISK_STRATIFICATION_PROTOCOL_PRESENTATION.pdf


### 1: Heart Disease Prediction Using Machine Learning Models
 **File:** `HEART DISEASE PREDICTION USING MACHINE LEARNING MODELS.pdf`

**Objective**
- Predict the presence of heart disease using clinical data
- Prioritize **high recall (sensitivity)** to minimize missed diagnoses

**Dataset**
- UCI Heart Disease Dataset
- 303 patient records
- 13 clinical features
- No missing values

**Models Evaluated**
- Decision Tree (baseline)
- Random Forest (final model)
- XGBoost (advanced competitor)

**Final Model Performance (Random Forest)**
- Accuracy: **83.6%**
- ROC-AUC: **0.90**
- Recall (Heart Disease): **97%**
- False Negatives: **1**

**Key Insight**
> Ensemble learning significantly improves robustness and generalization while maintaining strong clinical relevance.

---

### 2: Heart Disease Risk Stratification Protocol (Interpretable Decision Tree)
  **File:** `HEART DX RISK STRATIFICATION PROTOCOL PRESENTATION.pdf`

**Purpose**
- Provide an **interpretable, stepwise risk stratification protocol**
- Support clinicians in prioritizing patients for further cardiac evaluation

**Model Characteristics**
- Shallow Decision Tree (depth ≤ 3)
- Clear IF–THEN clinical rules
- Uses routinely available clinical inputs

**Core Features Used**
- Thalassemia category
- Chest pain type
- ST depression (Oldpeak)
- Total cholesterol
- Exercise-induced angina

**Operating Modes**
- **Screening / Triage:** Low threshold to maximize recall
- **Decision Support:** Balanced sensitivity and specificity

**Clinical Emphasis**
- Transparency
- Explainability
- Alignment with clinical reasoning

---

## Clinical Decision Rationale
- False negatives are more dangerous than false positives in heart disease screening
- Both systems are designed to **support**, not replace, clinical judgment
- Predictions guide prioritization, not diagnosis

---

## Ethics, Fairness, and Governance
- Decision-support use only
- External validation required before deployment
- Potential demographic bias acknowledged due to limited dataset diversity
- Fairness audits and performance monitoring recommended
- Patient data privacy must be strictly preserved

---

## Limitations
- Small, single-source dataset
- No longitudinal or imaging data
- No external clinical validation
- Ensemble models have reduced interpretability compared to linear models

---

## Future Work
- Multi-center and population-diverse datasets
- Integration of laboratory, imaging, and longitudinal data
- SHAP-based explainability
- Prospective clinical validation studies
- Secure deployment as a clinical decision-support system

---

## Conclusion
Together, these projects demonstrate how machine learning can be responsibly applied to healthcare by balancing **predictive performance, interpretability, and ethical deployment**, supporting early heart disease detection and clinical risk stratification.

---

### Author
**Dr. Samuel Israel,M.Sc. Data Science & AI**   
Healthcare & Clinical Data Scientist  



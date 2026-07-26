# Explainable Public-Sector Fraud Detection  
### Synthetic Data • SHAP Explainability • Responsible AI • PhD Research Project

This repository contains an end‑to‑end **Explainable AI model for welfare fraud detection**, developed using **synthetic data**, **rule‑based fraud scoring**, and **SHAP interpretability**.  
It forms the technical foundation of my **PhD research proposal** on building a Responsible AI framework for public‑sector fraud detection.

---

## 📌 Project Overview

Public‑sector welfare systems (e.g., Universal Credit) face complex fraud challenges that require both **accuracy** and **explainability**.  
This project demonstrates how machine learning and explainable AI can be combined to create transparent, auditable fraud‑risk insights.

The work includes:

- A **synthetic dataset** simulating realistic fraud behaviours  
- A **fraud‑scoring function** inspired by operational patterns  
- A **Random Forest classifier** trained on encoded features  
- **Global explainability** using SHAP summary plots  
- **Local explainability** using SHAP force plots  
- **High‑risk vs low‑risk case comparison**  
- A foundation for a future **Responsible AI framework**  

This repository is intended for supervisors, researchers, and practitioners interested in explainable fraud detection, synthetic data generation, and public‑sector AI governance.

---

## 🧠 Motivation

Fraud detection in welfare systems is a high‑stakes domain.  
Models must be:

- **Transparent**  
- **Fair**  
- **Auditable**  
- **Operationally grounded**  
- **Privacy‑preserving**

This project demonstrates how synthetic data and explainable machine learning can support these goals while avoiding the privacy risks associated with real claimant data.

---

## 🏗️ What’s Included

### **1. Synthetic Dataset**
A structured dataset generated using NumPy, simulating fraud patterns across:

- Identity  
- Tenancy  
- Childcare  
- Employment  
- Documentation  
- Behavioural inconsistencies  

### **2. Fraud Scoring Function**
A rule‑based scoring system reflecting realistic fraud indicators such as:

- Inconsistent tenancy agreements  
- Weak or fraudulent ID documents  
- Childcare claimed while not working  
- Handwritten childcare evidence  
- Advance‑then‑close claim patterns  

### **3. Machine Learning Model**
A Random Forest classifier trained on encoded features with:

- Balanced class weights  
- Train/test split  
- Evaluation metrics (precision, recall, F1)

### **4. Explainability**
- **SHAP summary plot** (global feature importance)  
- **SHAP force plots** (local explanations)  
- **High‑risk vs low‑risk case analysis**  

### **5. PhD Proposal**
A full academic proposal outlining the long‑term vision for a **Responsible AI framework** integrating:

- Explainability  
- Fairness  
- Governance  
- Human‑in‑the‑loop design  
- Operational insight  

---

## 📂 Repository Structure
explainable-public-sector-fraud-detection/
│
├── data/                     # Synthetic dataset (optional)
├── notebooks/                # Jupyter notebook with full pipeline
├── images/                   # SHAP plots and visual outputs
├── proposal/                 # PhD proposal PDF
│
├── README.md                 # Project overview
└── LICENSE                   # CC BY 4.0 License

---

## 🔍 Key Visuals

The `images/` folder contains:

- SHAP summary plot  
- High‑risk SHAP force plot  
- Low‑risk SHAP force plot  
- Side‑by‑side comparison visuals  

These help demonstrate model transparency and case‑level reasoning.

---

## 📜 License

This project is licensed under the **Creative Commons Attribution 4.0 International License (CC BY 4.0)**.  
You may use, share, or adapt the work **with proper attribution**.

---

## 📬 Contact

**Author:** Odinaka  
**Location:** Birmingham, United Kingdom  
**LinkedIn:** linkedin.com/in/odinaka-asidanya  
**email:** oasidanya@yahoo.com

If you are a supervisor or researcher interested in this work, feel free to reach out.

---

## 🌱 Future Work

This project is Phase 1 of a larger research vision.  
Future development will include:

- A scalable synthetic data engine  
- Fairness and bias auditing  
- Counterfactual explanations  
- Governance and auditability features  
- Human‑in‑the‑loop investigator tools  
- A full Responsible AI framework for welfare fraud detection  

---

## ⭐ Acknowledgements

This project is informed by real operational insight from my role as a Service Delivery Coach in the public sector, combined with academic training in Data Analytics and Responsible AI.


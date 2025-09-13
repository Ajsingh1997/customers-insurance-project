# Project InsureScore – Customer Risk Profiling & Claim Prediction  

This project builds an **end-to-end machine learning pipeline** for the insurance sector to **predict claim probabilities, score customers by risk, and flag potential fraud**.  

---

## 📖 Problem Statement  
Insurance companies often struggle with:  
- Identifying high-risk customers.  
- Predicting claim probabilities accurately.  
- Preventing fraudulent payouts.  

**Goal:** Build a predictive and interpretable system that helps insurers optimize pricing, reduce risks, and build trust.  

---

## 📊 Data Used  
- **Customer Demographics:** Age, Gender, Region Code, Driving License.  
- **Policy Details:** Annual Premium, Policy Sales Channel, Vintage (tenure).  
- **Vehicle Details:** Vehicle Age, Vehicle Damage.  
- **Target Variable:** `Response` (1 = Claim, 0 = No Claim).  

---

## 🛠 Approach  
1. **EDA** → Analyzed customer & claim history.  
2. **Feature Engineering** → Risk features, categorical encoding.  
3. **Modeling** → Logistic Regression, Random Forest, XGBoost (Ensemble).  
4. **Evaluation** → ROC-AUC, Precision, Recall.  
5. **Risk Scoring** → Probabilities scaled into 0–100, grouped as Low / Medium / High risk.  
6. **Interpretability** → SHAP plots & LIME explanations for model transparency.  
7. **Fraud Flagging** → Rule-based + anomaly detection for suspicious cases.  

---

## 📂 Deliverables  
- `final_predictions.csv` → Risk scores, risk buckets, fraud flags.  
- `fraud_flagged_customers.csv` → High-risk, flagged customers.  
- `shap_summary.png` → Global feature importance.  
- `lime_explanation_example.html` → Local explanation of predictions.  

---

## ✅ Outcomes  
- **Risk segmentation** for smarter underwriting.  
- **Claim probability prediction** with high accuracy.  
- **Fraud detection system** to reduce losses.  
- **Explainable AI outputs** for business adoption.  

---

## 💻 Tech Stack  
- **Languages & Libraries:** Python, Pandas, NumPy, Scikit-learn, XGBoost, Matplotlib, Seaborn  
- **Explainability Tools:** SHAP, LIME  
- **Environment:** Jupyter Notebook  

---

## 📌 Author  
**Ajay Singh Rana**  
Certified Data Analyst & Data Scientist  

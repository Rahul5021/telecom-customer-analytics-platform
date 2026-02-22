# 📡 Telecom Customer Analytics Platform

---

## 📋 Project Status
| Task | Status |
|------|--------|
| Environment & Dataset | ✅ Initialized & loaded (2,666 observations) |
| Data Cleaning | ✅ Resolved categorical mapping & case-sensitivity issues |
| Exploratory Data Analysis | 🔄 Phase 1 complete (Key drivers identified) |
| Next Milestone | 📅 Feature engineering & Predictive Modeling |

---

<details>
<summary>1️⃣ Problem Statement</summary>

This project tackles **Rising Customer Churn**. Retaining existing customers is far more cost-effective than acquiring new ones. This platform identifies the **"Why"** and **"Who"** behind customer attrition.  

**Key Questions:**  
- ❓ What are the primary triggers causing customers to leave?  
- ❓ Can we predict a high-risk customer before they churn?  
- ❓ How does specific plan usage (International/Voice Mail) impact loyalty?  

</details>

<details>
<summary>2️⃣ Objective</summary>

Build an end-to-end data science solution that:  

- **🔍 Diagnoses:** Correlations between usage patterns and churn  
- **🤖 Predicts:** Uses ML (XGBoost/Scikit-learn) to flag at-risk users  
- **💡 Optimizes:** Provides actionable recommendations to reduce churn  

</details>

<details>
<summary>3️⃣ Dataset & Initial Insights</summary>

- **Source:** Kaggle Telecom Churn Dataset  
- **Target Variable:** Churn (Binary: 0/1)  

**🚨 Early EDA Findings:**  
- **🌐 International Plan Paradox:** Users with an International Plan churn at **43.7%**, vs. **11.3%** without  
- **📞 Usage Correlation:** High **Total Day Minutes** & **Customer Service Calls** positively correlated with churn (0.20), indicating service frustration or bill shock  

</details>

<details>
<summary>4️⃣ Planned Architecture</summary>

1. **Data Preprocessing:** Handle NaNs, encode categorical variables, scale features  
2. **EDA:** Statistical profiling & correlation heatmaps  
3. **Machine Learning Pipeline:**  
   - Model training (Random Forest, XGBoost)  
   - Hyperparameter tuning  
4. **Explainability (SHAP):** Understand feature importance  
5. **Business Simulation:** Estimate revenue saved through proactive retention  

</details>

<details>
<summary>5️⃣ Technology Stack</summary>

| Category | Tools |
|----------|-------|
| Language | Python 3.x |
| Libraries | Pandas, NumPy, Scikit-learn, XGBoost |
| Visualization | Matplotlib, Seaborn, SHAP |
| Environment | Jupyter Notebook, Git |

</details>

<details>
<summary>6️⃣ How to Use</summary>

1. **Clone the repository**  
2. **Install dependencies:**  
```bash
pip install -r requirements.txt
```
3. **Run the EDA Notebook:**
```bash
Open EDA_Notebook.ipynb
```
</details>
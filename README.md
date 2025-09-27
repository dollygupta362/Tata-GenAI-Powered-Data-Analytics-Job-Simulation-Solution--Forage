#<h1 align="center"> Tata GenAI Powered Data Analytics Job Simulation Solution Forage</h1>
<h2 align="center">Geldium Loan Delinquency Prediction & Ethical AI Collections System 🚀</h2>

A comprehensive data science project that defines a predictive model for loan delinquency and proposes an ethical, AI-driven strategy for proactive collections management.

---

## 💡 Project Goals and Deliverables

This project fulfilled four critical steps in building a reliable credit risk framework: data quality assessment, predictive modeling, business strategy recommendation, and AI system conceptualization.

| Task ID | Focus Area | Deliverable File |
| :--- | :--- | :--- |
| **Task 1** | Exploratory Data Analysis (EDA) and Risk Profiling | `Task 1.pdf` |
| **Task 2** | Predictive Model Plan and Justification | `Task 2.pdf` |
| **Task 3** | Business Recommendation Report (SMART Goal) | `Task 3.pdf` |
| **Task 4** | AI-Driven Collections System Executive Briefing | `Task 4.pptx` |

---

## ✅ Task 1: Exploratory Data Analysis (EDA) Summary

The EDA established the integrity of the dataset and surfaced strong financial and behavioral risk indicators.

### Key Risk Indicators
| Indicator | Threshold | Why It Matters |
| :--- | :--- | :--- |
| **High Credit Utilization** | > 0.6  | Indicates financial strain and overextension. |
| **Frequent Missed Payments** | $\ge 4$  | Direct behavioral signal of delinquency risk. |
| **High Debt-to-Income Ratio** | $> 0.4$  | Suggests poor affordability and high default probability. |

### Data Quality Issues & Treatment
* **Problem:** `Credit_Utilization` had values exceeding 1.0, and `Income` was missing in several entries.
* **Solution:**
    * `Credit_Utilization`: Handled via **Median Imputation** to reduce skew.
    * `Income`: Handled via **Synthetic Generation** based on age/employment for realistic values.

---

## 📈 Task 2: Predictive Model Plan

A model pipeline was designed to forecast delinquency, prioritizing **interpretability** alongside accuracy.

### Model Choice and Top Features
* **Model:** **Logistic Regression**.
* **Justification:** Chosen for high interpretability and efficiency, which is critical for compliance and transparency in financial services.
* **Top 5 Input Features:**
    1.  Missed\_Payments 
    2.  Credit\_Utilization 
    3.  Debt\_to\_Income\_Ratio 
    4.  Monthly Payment History (Month\_1 to Month\_6) 
    5.  Credit\_Score 

### Evaluation Strategy
Model success is measured through performance and fairness checks.
* **Performance Metrics:** F1 Score, AUC-ROC (to assess class distinction), Precision, and Recall.
* **Fairness Checks:** **Demographic Parity** (equal positive prediction rates) and **Equal Opportunity** (consistent true positive rates across subgroups).

---

## 🎯 Task 3: Business Recommendation

Insights were formalized into a strategic, actionable recommendation for the Head of Collections.

### Core Recommendation (SMART Goal)
* **Insight:** High credit utilization (>90%) is the strongest predictor of customer delinquency.
* **Recommendation:** Launch a targeted intervention program focused on customers with **credit utilization above 90%**, offering tailored repayment plans and financial counselling.
* **Measurable Goal:** Aim to **reduce delinquency in this segment by 15%** over a 6-month pilot period.

### Fairness & Mitigation
| Fairness Risk | Mitigation Strategy |
| :--- | :--- |
| **Demographic Bias** (disproportionately flagging lower-income or younger groups)  | Apply fairness audits and reweighing techniques to ensure equitable treatment. |
| **Proxy Bias** (Employment status acting as a proxy for socioeconomic background)  | Conduct feature sensitivity analysis and adjust model inputs accordingly. |

---

## 🤖 Task 4: AI-Driven Collections System

A conceptual high-level design for a scalable, responsible AI collections system.

### End-to-End System Workflow
1.  **Inputs:** Customer Data Profile, repayment history, and bureau scores.
2.  **Decision Logic:** Predictive model segments customers into risk tiers (Low/Med/High).
3.  **Targeted Actions:** Automated SMS/email reminders and personalized restructuring offers.
4.  **Learning Loop:** Outcomes are tracked to retrain the model and refine the strategy quarterly.

### Autonomy vs. Human Oversight
| Autonomous Activities | Human Oversight Required |
| :--- | :--- |
| Risk scoring and segmentation  | Final approval for restructuring offers  |
| Automated outreach (email/SMS nudges)  | Escalation handling for sensitive cases  |
| Model retraining based on feedback loops  | Reviewing fairness audit reports  |

### Business Impact & Outcomes
* **Business KPIs:** Expected **15–25% reduction in delinquency rates** and **20% decrease in operational costs** via automation.
* **Customer Outcomes:** Increased trust and transparency through personalized, empathetic outreach.

---

## 📞 Contact

👤 **Dolly Gupta**  
📍 Data Science & Analytics Enthusiast  
📧 *dollygupt362@gmail.com*  
🔗 [LinkedIn](http://www.linkedin.com/in/dolly-gupta-3b54b8229)  




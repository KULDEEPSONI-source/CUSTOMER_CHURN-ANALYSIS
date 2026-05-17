# Customer Churn Analysis & Retention Strategies

## 📌 Project Overview
This repository contains a comprehensive data analysis focused on identifying the key drivers behind customer churn. By analyzing customer demographics, account information, and service usage patterns, this project uncovers actionable insights to guide targeted customer retention strategies and improve long-term customer lifetime value (CLV).

---

## 🎯 Project Objective
The primary objective of this analysis is to investigate the underlying factors influencing customer churn. Specifically, the study evaluates how contract structures, payment configurations, customer tenure, and service types impact a customer's likelihood to leave the service.

---

## 📊 Key Insights & Findings

### 📅 1. Contract Type vs. Churn
Longer contract periods serve as a strong retention tool, as customers with extended commitments show significantly higher loyalty.
*   **Month-to-Month Contracts:** Exhibit the highest risk, with a **42%** churn rate.
*   **One-Year Contracts:** Churn drops drastically to **11%**.
*   **Two-Year Contracts:** Highly stable, featuring a mere **3%** churn rate.

### 💳 2. Payment Methods & Churn
Payment friction and billing convenience heavily influence customer retention.
*   **Electronic Checks:** Show a critical churn rate of **45%** (nearly 3x higher than other methods).
*   **Alternative Methods:** Credit cards, bank transfers, and mailed checks remain highly stable, averaging a **15% – 18%** churn rate.
*   *Implication:* Potential underlying issues with transaction failures, billing trust, or manual effort associated with electronic checks.

### ⏳ 3. Churn by Customer Tenure
The first year is the most volatile period in the customer lifecycle, highlighting the critical importance of onboarding.
*   **Shorted Tenure (< 1 Year):** **50%** churn rate.
*   **Mid-Term Tenure (1–3 Years):** Churn decreases to **35%**.
*   **Long-Term Tenure (> 3 Years):** Settles into a highly loyal baseline of **15%**.

### 🌐 4. Internet Service Impact
*   **Fiber Optic Users:** Experience a **30%** churn rate.
*   **DSL Users:** Experience a lower **20%** churn rate.
*   *Implication:* Despite higher speeds, fiber optic customers might face issues regarding price sensitivity, service reliability, or aggressive competitor poaching.

### 👥 5. Demographic Highlights (Senior Citizens)
*   **Senior Citizens (65+):** Show a high vulnerability to churn at **41%**.
*   **Non-Senior Citizens:** Maintain a significantly lower churn rate of **26%**.

---

## 📉 Data Visualizations Summary
The exploratory data analysis (EDA) utilizes structured visualizations to back these findings:
*   **Bar Charts:** Highlight the stark disparity in churn across payment methods and contract types.
*   **Line Graphs:** Show a clear, downward sloping trendline for churn as customer tenure increases, confirming that retention risks mitigate over time.

### Quick-Look Metrics Distribution
| Factor Category | Sub-Category | Churn Rate (%) | Risk Level |
| :--- | :--- | :---: | :--- |
| **Contract Type** | Month-to-Month | 42% | 🔴 High |
| | One-Year | 11% | 🟡 Medium |
| | Two-Year | 3% | 🟢 Low |
| **Payment Method**| Electronic Check | 45% | 🔴 High |
| | Credit Card / Bank Transfer | 15% - 18% | 🟢 Low |
| **Tenure** | < 1 Year | 50% | 🔴 High |
| | > 3 Years | 15% | 🟢 Low |

---

## 💡 Strategic Recommendations

1.  **Promote Long-Term Commitments:** Create targeted marketing campaigns or financial incentives (e.g., small monthly discounts) to migrate high-risk Month-to-Month users onto 1-year or 2-year agreements.
2.  **Optimize Payment Onboarding:** Incentivize users to switch from manual electronic checks to automated, lower-churn methods like Auto-pay via Credit Card or Direct Bank Transfer. 
3.  **Proactive First-Year Onboarding:** Implement specialized customer success check-ins at the 3-month, 6-month, and 9-month marks to address friction early and reduce the 50% first-year drop-off rate.
4.  **Targeted Senior Care Programs:** Develop simplified billing processes, dedicated customer service channels, or tailored discounts specifically designed to retain the senior citizen demographic.
5.  **Audit Fiber Optic Technical Health:** Investigate the root cause behind the 30% fiber optic churn rate—focusing on pricing strategies, setup transparency, or localized network stability issues.

---

## 🛠️ Repository Structure
```text
├── data/                  # Raw and processed datasets
├── notebooks/             # Jupyter notebooks covering EDA and analysis
├── visualizations/        # Exported charts and plots
├── README.md              # Project executive summary and overview
└── requirements.txt       # Python dependencies configuration

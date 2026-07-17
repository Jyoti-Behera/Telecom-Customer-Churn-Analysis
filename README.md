#  Telecom Customer Churn Analysis Dashboard

##  Project Overview
This project focuses on analyzing customer churn behavior within the telecom sector to identify key risk factors and optimize retention strategies. Utilizing an end-to-end data analytics workflow, the raw historical customer dataset was cleaned, transformed, and modeled to extract critical business intelligence. 

The final deliverable is an interactive, corporate-standard Power BI dashboard that provides stakeholders with data-driven insights regarding customer demographics, contract types, account metrics, and service preferences.

---

##  Executive Summary & Key Metrics
Based on the dashboard analysis of active and churned accounts under the current filter criteria:
*   **Total Customers:** 3,334 total accounts analyzed.
*   **Churned Customers:** 1,503 customers have churned.
*   **Retention Rate:** 55% of the customer base is successfully retained.
*   **Churn Rate:** A significant 45% churn rate, indicating critical areas for retention intervention.

---

##  Key Business Insights

### 1. Contract & Structural Risk
*   **Month-to-Month Vulnerability:** Customers on short-term Month-to-month contracts represent the highest churn volume (~1.5K churned vs ~1.8K retained). Transitioning these accounts to longer-term annual or biennial commitments is a high-priority retention lever.

### 2. Demographic Distribution
*   **Gender Neutrality:** Churn is almost evenly split between genders, with **Male** accounts accounting for 1,678 churn cases and **Female** accounts representing 1,656. Churn patterns are driven by service features and pricing rather than gender demographics.

### 3. Tenure Patterns (High-Risk Windows)
*   **Early Lifecycle Churn:** The highest risk of customer attrition occurs in the earliest phase of customer tenure. A massive spike is observed at the start, which stabilizes significantly once a customer crosses initial milestones, showing high retention stability for older accounts.

### 4. Financial Triggers (Monthly Charges)
*   **The Sweet Spot & High Churn Zones:** The highest volume of churn sits heavily within the **60-90** monthly charges bin, closely followed by the high-tier **90-120** bracket. Conversely, customers in the **0-30** and **30-60** budget tiers demonstrate much higher stability and lower churn rates.

### 5. Product & Internet Service Vulnerability
*   **Fiber Optic Risk:** Customers utilizing **Fiber Optic** internet services show a disproportionately high churn volume (1.0K churned vs 0.7K retained) compared to **DSL** users (0.4K churned vs 0.7K retained). This suggests potential issues regarding pricing expectations, service reliability, or competition in the high-speed tier.

---

##  Tech Stack & Methodology

*   **Data Preparation & Engineering:** Cleaned and structured using Python and SQL to resolve missing values, parse continuous fields, and establish uniform data formats.
*   **Advanced Data Modeling (DAX):** Implemented custom DAX measures within Power BI for dynamic metrics including `Retention Rate` and `Churn Rate`.
*   **Data Grouping & Binning:** Created optimized intervals/bins for structural columns (`Tenure` and `Monthly Charges`) to eliminate visual clutter and track distributions effectively.
*   **Data Visualization:** Built a tailored multi-slicer Power BI UI utilizing a professional dual-tone color scheme to maximize data density and scannability.

---


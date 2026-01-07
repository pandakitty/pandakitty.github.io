# Project Deep Dive: Customer Segmentation using RFM Analysis

### 1. The Challenge (Problem Statement)
Not all customers are equal. To maximize marketing ROI, businesses must categorize customers based on their value. I aimed to segment a retail dataset of 10,000+ customers into actionable groups.

### 2. Methodology: RFM Framework
I implemented the **RFM** (Recency, Frequency, Monetary) framework using **Python**:
* **Recency:** How many days since the last purchase?
* **Frequency:** How many times did they buy?
* **Monetary:** What is the total revenue from this customer?

### 3. Technical Execution
* **Data Aggregation:** Used Pandas to transform transaction-level data into a customer-level summary.
* **Scoring:** Developed a custom algorithm to assign a score of 1-5 for each RFM category.
* **Segmenting:** Categorized customers into groups such as "Champions," "At Risk," and "Hibernating."

### 4. Business Impact
* **Targeting:** Identified the top 20% of customers responsible for 60% of total revenue.
* **Strategy:** Provided recommendations for "re-engagement" campaigns for the "At Risk" segment, similar to patient retention strategies in community health environments.

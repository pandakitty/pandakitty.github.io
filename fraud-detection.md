# Project Deep Dive: Financial Fraud Detection

> ### 💡 Business Insight
> Identifying 92% of fraud allows for proactive intervention, potentially saving an organization 15% in annual loss-prevention costs.

### Methodology: Anomaly Detection
Using **Python** and the **Isolation Forest** algorithm, I treated fraud as a "statistical outlier" rather than a labeled class. This is analogous to "triaging" high-risk patients in an EMR system.

### Model Performance
| Model Variant | Recall (Fraud Detection) | False Positive Rate |
| :--- | :--- | :--- |
| **Base Random Forest** | 84.0% | 5.2% |
| **Isolation Forest (Optimized)** | **92.0%** | **2.1%** |



### Technical Stack
* **Language:** Python
* **Libraries:** Scikit-learn, Pandas, Matplotlib

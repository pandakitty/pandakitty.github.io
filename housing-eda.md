# Project Deep Dive: Exploratory Data Analysis (EDA) - Housing Prices

### 1. The Challenge (Problem Statement)
Real estate markets are influenced by hundreds of variables. For a Business Analytics Specialist, the challenge is to determine which "signals" actually drive price and which are just "noise." This project focused on identifying the most impactful features in the Kaggle Housing Price dataset.

### 2. Analytical Approach
Using **Python (Pandas/Seaborn)**, I performed a rigorous statistical exploration of the data:
* **Correlation Mapping:** Created heatmaps to identify strong linear relationships between square footage, neighborhood, and sale price.
* **Outlier Detection:** Used box plots to identify and handle 5% of data points that would have skewed the predictive model.
* **Feature Engineering:** Combined variables (like "Year Built" and "Year Remodeled") to create a "Property Age" metric for better insights.

### 3. Results & Findings
* **Key Driver:** Confirmed that "Overall Quality" and "GrLivArea" (Above ground living area) had the highest correlation with price.
* **Data Quality:** Cleaned 20+ columns of missing data, ensuring a high-integrity dataset for further modeling.

### 4. Professional Significance
This project demonstrates my ability to handle large, messy datasets and extract the "story" behind the numbers—a skill I use daily when analyzing complex patient flow metrics and healthcare data trends.

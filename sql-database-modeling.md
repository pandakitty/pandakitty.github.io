# Project Deep Dive: Retail Database Modeling & CLV Analysis

### 1. The Challenge (Problem Statement)
For any retail business, understanding the long-term value of a customer is more important than a single sale. The goal of this project was to design a robust relational database from scratch that could handle complex transactions and provide data for advanced business analytics, specifically calculating Customer Lifetime Value (CLV).

### 2. Database Architecture
Leveraging my experience with complex EMR systems like **Epic and Cerner**, I understood the importance of data integrity and normalized table structures. I designed a schema with 7 interconnected tables:
* **Core Tables:** Customers, Products, and Orders.
* **Supporting Tables:** Order_Details, Categories, Employees, and Shippers.
* **Integrity:** Implemented Primary and Foreign Keys to ensure no "orphan" data, similar to the strict medical and legal data standards I followed as a Medical Scribe.

### 3. Methodology: Advanced SQL Querying
I utilized 3+ years of SQL experience to extract business intelligence from the raw data.
* **Techniques:** Used complex **JOINs**, **Subqueries**, and **Window Functions**.
* **Metric Calculation:** Developed a script to aggregate total spend per customer over time, adjusted by purchase frequency, to determine the CLV on a quarterly basis.

### 4. Results & Business Impact
* **Visibility:** Created a clear view of which customer segments were the most profitable.
* **Strategic Insight:** Identified high-value segments (similar to the RFM analysis I performed on 10,000+ customers), allowing marketing teams to allocate budget more efficiently.

### 5. Professional Skills Demonstrated
This project highlights my proficiency in **Relational Databases** and my ability to structure an ambiguous business problem into a technical solution.

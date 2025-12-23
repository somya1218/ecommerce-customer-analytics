🛍️ E-Commerce Customer Analytics & Segmentation

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![Status](https://img.shields.io/badge/Status-Complete-success.svg)

📊 Project Overview
Comprehensive analysis of 100,000+ Brazilian e-commerce transactions to solve a critical retention problem: **97% of customers were one-time buyers**. Used RFM analysis and K-Means machine learning to segment customers and design targeted strategies with **R$ 3-4M projected annual impact**.

🎯 Business Problem
The marketplace was spending heavily on customer acquisition but **97% of customers never made a second purchase**. Customer acquisition costs 5-7x more than retention, making this business model unsustainable.

Solution Approach
Data Analysis Pipeline:
1.Data Collection & Cleaning
   - Merged 4 separate datasets (orders, customers, products, payments)
   - Cleaned 110,000 transactions
   - Handled missing values and outliers

2.Exploratory Data Analysis
   - Created 10 business visualizations
   - Uncovered seasonal patterns (Black Friday +71% spike)
   - Identified geographic concentration (São Paulo = 37% revenue)

3.Customer Segmentation
   - Applied RFM Analysis (Recency, Frequency, Monetary)
   - Used K-Means clustering to create 4 customer segments
   - Developed targeted strategies for each segment

Key Findings

Business Metrics
- Total Revenue:** R$ 13,591,643
- Total Orders:** 99,441
- Average Order Value:** R$ 154.10
- Customer Retention Rate:** 3% (97% one-time buyers)
- Average Delivery Time:** 12 days

Critical Insights
1. Retention Crisis
97% of customers buy only once - the #1 business priority

2. Geographic Concentration  
- São Paulo: 37% of total revenue
- Top 3 states: 63.4% of revenue

3. Seasonal Opportunity
November 2017 revenue = R$ 987K (71% above monthly average) - Black Friday effect

Customer Segments
Cluster 0 - At-Risk (36.9% | 29.3% revenue)
Characteristics:
- Average Recency: 254 days (8+ months inactive)
- Average Orders: 1
- Average Spend: R$ 109

Strategy:
- Win-back email campaign with 15% discount
- "We miss you" messaging
- Survey to understand drop-off reasons

Impact:30% recovery = +R$ 900K revenue

Cluster 1 - Recent Buyers (37.0% | 30.6% revenue)
Characteristics:
- Average Recency: 87 days (3 months)
- Average Orders: 1
- Average Spend: R$ 113

Strategy:
- Convert to repeat customers NOW (golden window!)
- Loyalty program launch
- Personalized product recommendations
- Follow-up email sequence

Impact:20% conversion =+R$ 800K revenue

Cluster 2 - High-Value VIPs (2.8% | 21.1% revenue)
Characteristics:
- Average Recency: 239 days
- Average Orders: 1
- Average Spend: R$ 1,046 (10x higher!)

Strategy:
- VIP loyalty program
- Exclusive early access
- Personal thank-you messages
- Referral incentives

Impact:Protect R$ 2.7M annual revenue


Cluster 3 - Lost Customers (23.3% | 18.9% revenue)
Characteristics:
- Average Recency: 457 days (15+ months)
- Average Orders: 1
- Average Spend: R$ 111

Strategy:
- Last-chance 30% discount offer
- Exit survey
- Remove from active campaigns if no response

Impact:Save R$ 200K in wasted ad spend

Projected Business Impact

| Initiative | Expected Impact |
|------------|-----------------|
| At-Risk Win-Back (30% recovery) | +R$ 900,000 |
| Recent Buyer Conversion (20%) | +R$ 800,000 |
| VIP Retention Program | R$ 2,700,000 protected |
| Q4 Seasonal Optimization | +15-20% revenue |
| Stop Waste on Lost Customers | -R$ 200,000 costs |

Total Potential: R$ 3-4 Million annually (22-30% revenue increase)


Technical Stack
- Python 3.8+
- pandas - Data manipulation and cleaning
- NumPy - Numerical computing
- scikit-learn - Machine learning (K-Means clustering, StandardScaler)
- matplotlib & seaborn - Data visualization
- Jupyter Notebook - Interactive analysis

📁 Project Structure

ecommerce-customer-analytics/
│
├── data/
│   ├── olist_orders_dataset.csv
│   ├── olist_order_items_dataset.csv
│   ├── olist_customers_dataset.csv
│   ├── olist_products_dataset.csv
│   ├── rfm_data.csv
│   └── rfm_segments.csv
│
├── notebooks/
│   └── 01_data_exploration.ipynb
│
├── images/
│   ├── 01_sales_trends.png
│   ├── 02_top_states.png
│   ├── 03_order_distribution.png
│   ├── 04_delivery_performance.png
│   ├── 05_purchase_frequency.png
│   ├── 06_rfm_distribution.png
│   ├── 07_elbow_method.png
│   ├── 08_customer_segments.png
│   └── 09_cluster_analysis.png
│
└── README.md

How to Run

Prerequisites
bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter


Steps
1. Clone this repository
bash
git clone https://github.com/yourusername/ecommerce-customer-analytics.git
cd ecommerce-customer-analytics

2. Download the [Brazilian E-Commerce Dataset from Kaggle](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)

3. Place CSV files in `/data` folder

4. Open Jupyter Notebook
bash
jupyter notebook notebooks/01_data_exploration.ipynb

5. Run all cells sequentially

📈 Key Visualizations

Sales Trends Over Time
![Sales Trends](images/01_sales_trends.png)

Geographic Distribution
![Top States](images/02_top_states.png)

Customer Segments
![Segments](images/08_customer_segments.png)


Future Enhancements

- [ ] Predictive churn model (identify at-risk customers before they leave)
- [ ] Product recommendation engine (collaborative filtering)
- [ ] Real-time dashboard (Streamlit or Power BI)
- [ ] A/B testing framework for campaigns
- [ ] Cohort analysis for retention trends
- [ ] Geographic expansion strategy analysis

Author
[somya jain]
LinkedIn:[https://www.linkedin.com/in/somya-jain-aa04b524b/]
GitHub: [https://github.com/somya1218]
Email: [jsomya1218@gmail.com]

License
This project is licensed under the MIT License.

Acknowledgments
- Dataset: [Olist - Brazilian E-Commerce Public Dataset](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)
- Inspiration: Customer analytics best practices from leading e-commerce companies

Project Stats
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange)
![Python](https://img.shields.io/badge/Python-3.8+-blue)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-green)
![Scikit Learn](https://img.shields.io/badge/Scikit--Learn-ML-red)

If you found this project helpful, please give it a star!





















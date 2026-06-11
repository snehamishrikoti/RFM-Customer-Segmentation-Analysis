📊 RFM Customer Segmentation Analysis

Overview

Comprehensive RFM (Recency, Frequency, Monetary) analysis on 541,000+ e-commerce transactions, segmenting 4,339 customers into 10 behavioral cohorts for targeted marketing and customer retention strategies.


🎯 Business Objective

Identify and classify customers based on purchasing behavior to:


📈 Maximize revenue from high-value segments (Champions, Loyal Customers)
🚨 Detect and re-engage at-risk customers before churn
🔄 Reactivate hibernating customers with targeted campaigns
💡 Provide actionable insights for customer lifecycle management



📊 Dataset

MetricValueTotal Transactions541,000+Unique Customers4,339Total Revenue£6.2MAverage Customer Value£2,050Analysis Period2011-2012


🔍 RFM Methodology

What is RFM Analysis?

RFM is a customer segmentation technique that scores customers on three dimensions:

MetricDefinitionInterpretationRecency (R)Days since last purchaseRecent buyers = higher engagementFrequency (F)Number of unique ordersMore orders = higher loyaltyMonetary (M)Total spend in currency (£)Higher spend = more valuable

Scoring System


Each metric scored 1-5 (1=low, 5=high)
Combined into RFM Code (e.g., 555 = Champion)
10 distinct segments identified



📈 Key Findings

1️⃣ Champions (1,121 customers)


RFM Code: 555 (Perfect Score)
Average Spend: £5,238
Frequency: 10.1 orders
Recency: 13 days
Revenue Share: 40%+ of total
Action: VIP loyalty programs, exclusive benefits


2️⃣ Loyal Customers (329 customers)


RFM Code: Mixed (primarily 4-5 range)
Average Spend: £2,462
Frequency: 5.7 orders
Revenue Share: 15%+ of total
Action: Cross-sell & upsell opportunities


3️⃣ At Risk (601 customers)


RFM Code: Low recency, good history
Average Spend: £1,256
Recency: 142 days (declining engagement)
Action: Win-back campaigns, special offers


4️⃣ Hibernating (867 customers)


RFM Code: Low recency & frequency
Average Spend: £473
Recency: 240 days
Action: Reactivation emails, product recommendations


5️⃣ New Customers (138 customers)


RFM Code: High recency, low frequency
Average Spend: £368
Action: Nurture with onboarding campaigns


📉 Other Segments


About to Sleep: Declining engagement - needs attention
Promising: Early-stage engagement - monitor closely
Cannot Lose Them: High-value at-risk - immediate action
Need Attention: Recent but low spend - opportunity
Potential Loyalist: Building engagement - nurture



🛠️ Tools & Technologies

Programming:     Python 3.x
Data Processing: Pandas, NumPy
Visualization:   Matplotlib, Seaborn
Dashboard:       Power BI
Version Control: Git & GitHub
Environment:     Jupyter Notebook


📁 Project Structure

RFM-Customer-Segmentation-Analysis/
│
├── 📓 notebooks/
│   ├── 01_data_cleaning.ipynb              # Data preprocessing & cleaning
│   ├── 02_rfm_calculation.ipynb            # RFM metric calculation
│   ├── 03_segmentation.ipynb               # Customer segmentation
│   └── 04_analysis_visualization.ipynb     # EDA & visualizations
│
├── 📊 data/
│   ├── raw_transactions.csv                # Original dataset (541K+ rows)
│   ├── cleaned_data.csv                    # Preprocessed data
│   └── rfm_scores.csv                      # RFM calculations
│
├── 📈 outputs/
│   ├── segment_profiles.csv                # Segment-level metrics
│   ├── customer_segments.csv               # Final segmentation
│   └── kpi_summary.csv                     # KPI metrics
│
├── 📸 visualizations/
│   ├── rfm_heatmap.png                     # R, F, M distribution
│   ├── recency_vs_frequency.png            # Scatter plot
│   ├── revenue_by_segment.png              # Revenue distribution
│   ├── customer_count_by_segment.png       # Size distribution
│   └── segment_distribution.png            # Pie chart
│
├── 📋 README.md                             # This file
├── 📄 LICENSE                               # MIT License
└── .gitignore                               # Git ignore file


🚀 Quick Start

Prerequisites

bashPython 3.7+
pip (Python package manager)

Installation


Clone the repository


bashgit clone https://github.com/snehamishriko1/RFM-Customer-Segmentation-Analysis.git
cd RFM-Customer-Segmentation-Analysis


Install dependencies


bashpip install pandas numpy matplotlib seaborn jupyter


Launch Jupyter Notebook


bashjupyter notebook


Run notebooks in order

Start with 01_data_cleaning.ipynb
Progress through to 04_analysis_visualization.ipynb






📊 Analysis Workflow

Raw Data (541K transactions)
        ↓
Data Cleaning & Preprocessing
        ↓
RFM Metric Calculation
(Recency, Frequency, Monetary)
        ↓
RFM Scoring (1-5 scale)
        ↓
Customer Segmentation (10 segments)
        ↓
Segment Profiling & Analysis
        ↓
Business Recommendations
        ↓
Power BI Dashboard Creation


📊 Visualizations Included

1. RFM Heatmap


Average R, F, M values per segment
Color-coded intensity mapping
Key insight: Champions score 5 across all metrics


2. Recency vs Frequency Scatter Plot


Distribution of all customers
Color-coded by segment
Shows clustering patterns


3. Revenue by Segment Bar Chart


Total revenue contribution per segment
Champions dominate (~£5.24M)
Identifies underutilized segments


4. Customer Count by Segment


Customer distribution across segments
Champions: 1,121 customers (25.8%)
Hibernating: 867 customers (20%)



💡 Key Insights & Recommendations

🎯 Strategic Insights


Concentration Risk

Champions (26% of base) = 40% of revenue
Vulnerable to churn - needs retention focus
Action: Dedicated account management



Untapped Potential

Hibernating (20% of base) + At Risk (14%) = 34%
~1,468 customers with reactivation potential
Action: Targeted reactivation campaigns



Early Warning System

At Risk segment shows declining engagement
Average recency: 142 days (previous 46 days for active)
Action: Automated alerts for engagement drop



Growth Opportunity

New Customers (138) show early promise
Onboarding critical for conversion
Action: Enhanced nurture sequences





📋 Actionable Recommendations

SegmentActionExpected ImpactChampionsVIP programs, exclusive accessPrevent churn, increase CLTVLoyal CustomersUpsell/cross-sell, referral programs15-20% revenue liftAt RiskWin-back campaigns, special offersRecover £500K+ revenueHibernatingRe-engagement emails, incentivesReactivate 10-15% cohortNew CustomersOnboarding sequences, educationImprove conversion to repeat


🔢 Core Metrics Summary

Total Customers:              4,339
Total Revenue:                £6.2M
Average Customer Value:       £1,429
Average Days Since Purchase:  92.52 days

Top Segment Revenue:          Champions - £5.24M (40.2%)
Fastest Growing Segment:      Loyal Customers (5.7 avg. orders)
Highest Churn Risk:           At Risk (142 days recency)
Reactivation Opportunity:     Hibernating (867 customers)


📚 Learning Outcomes

This project demonstrates proficiency in:

✅ Data Analysis


Data cleaning & preprocessing with Pandas
Exploratory Data Analysis (EDA)
Statistical analysis & interpretation


✅ Customer Analytics


RFM segmentation methodology
Customer lifecycle analysis
Behavioral cohort identification


✅ Business Intelligence


KPI definition & measurement
Segment profiling
Actionable insights generation


✅ Data Visualization


Multi-dimensional visualizations
Dashboard creation (Power BI)
Storytelling with data


✅ Python Programming


Data manipulation (Pandas, NumPy)
Visualization (Matplotlib, Seaborn)
Jupyter Notebook workflows



🔮 Future Enhancements


 Predictive Churn Modeling - ML model to predict churn probability
 Customer Lifetime Value (CLV) - Forecast long-term customer value
 Automated Segmentation - Production pipeline for real-time updates
 Real-time Dashboard - Live monitoring of customer metrics
 Cohort Analysis - Track segment evolution over time
 Recommendation Engine - Personalized product recommendations
 A/B Testing Framework - Measure campaign effectiveness



📊 Power BI Dashboard

An interactive Power BI dashboard has been created for this analysis featuring:


📈 Key metrics & KPIs
🎯 Segment-level deep-dives
📉 Trend analysis
🔍 Filtering & drill-down capabilities


Dashboard link: [Add your Tableau Public or PowerBI link here]


📞 Contact & Connect


GitHub: github.com/snehamishriko1
LinkedIn: [Add your LinkedIn URL]
Email: [Add your email]



📜 License

This project is licensed under the MIT License - see the LICENSE file for details.

You are free to:


✅ Use this analysis for learning
✅ Modify and adapt for your use case
✅ Share and distribute
✅ Use commercially



Acknowledgments


Dataset: E-commerce transaction data
Analysis conducted as part of data analytics training at QSpiders
Inspired by industry best practices in customer segmentation



📝 Notes


This analysis was conducted on historical data (2011-2012)
Recommendations should be validated with current data
Segment definitions may need adjustment based on business context
Regular re-analysis recommended (quarterly or monthly)



⭐ If you found this helpful, please star the repository!

Your support encourages more detailed analysis and open-source contributions.


Last Updated: June 2026
Status: ✅ Complete & Production-Ready

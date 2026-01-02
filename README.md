# Supply-Chain-Risk-Assessment
End-to-end data analytics project identifying $998M in supply chain risk and building predictive models with 91.79% accuracy to optimize supplier networks and improve delivery performance.

<img width="1170" height="656" alt="Screenshot 2026-01-02 131547" src="https://github.com/user-attachments/assets/b8886ba1-f5f4-4a41-969d-1ac5ae0c6bf1" />

<img width="1161" height="659" alt="Screenshot 2026-01-02 131611" src="https://github.com/user-attachments/assets/15cf30a9-0c2f-47a6-bc0c-42fe6f88a4c0" />

<img width="1168" height="651" alt="Screenshot 2026-01-02 131627" src="https://github.com/user-attachments/assets/a5482d31-ee24-4fd8-a6b5-ffc6cbcba027" />

📊 Business Problem
A global supply chain faced critical vulnerabilities:

68% of suppliers classified as high-risk exposing $998M in revenue
7.94% delivery performance vs 90% target (-91% gap)
84% of risk concentrated in Asia-Europe, creating geographic vulnerability
Average 6.75-day delays, 238% above industry benchmarks
No predictive capability or visibility into risk drivers

Business Impact: $30-50M annual losses from delays, quality issues, and expediting costs; high probability of major disruption within 24 months.

🎯 Project Objectives

Quantify supply chain risks across 100 suppliers and 1,201 transactions
Build predictive models to forecast delivery delays with >90% accuracy
Create interactive dashboards for data-driven decision-making
Develop strategic recommendations to reduce risk and improve performance
Secure executive buy-in for $30-45M investment in risk mitigation


🛠️ Technical Stack
Tools: Microsoft Excel (Power Query, Advanced Formulas), Power BI Desktop
Data: 100 suppliers, 1,201 transactions, 8 risk factors per supplier (Jan 2023 - Dec 2024)
Techniques: Time series analysis, predictive modeling, statistical analysis, risk scoring, scenario planning

📈 Key Analysis & Methodology
1. Risk Scoring Framework

Developed composite risk score from 8 weighted factors: Political Risk (15%), Economic Risk (15%), Environmental Risk (10%), Cyber Security (15%), Financial Stability (15%), Single Source Dependency (10%), Geographic Concentration (10%), Compliance Risk (10%)
Categorized suppliers: Critical (≥7), High (5-7), Medium (3-5), Low (<3)

2. Predictive Modeling

Built delay prediction model using historical patterns, risk scores, and order volumes
Achieved 91.79% accuracy (validated with MAPE methodology)
Enabled proactive inventory planning and customer communication

3. Time Series Analysis

Monthly aggregation of order volume, delays, and quality metrics
Identified seasonal patterns: Q3 peak performance (17M orders), Q4 deterioration (14M orders)
3-month moving averages to smooth volatility

4. Scenario Planning

Modeled 4 scenarios: Base Case, High Risk (+30%), Low Risk (-20%), Critical Disruption
Quantified impact on revenue, affected suppliers, and recovery time


📊 Dashboard Design
Three Interactive Power BI Dashboards:
1. Executive Overview

KPI cards: Total suppliers (100), High-risk (68), Delivery performance (6.75 days), Revenue at risk ($998M)
Regional risk distribution, supplier type breakdown, monthly trends
Target Users: C-suite, Board of Directors

2. Risk Analysis Deep Dive

Risk contributor waterfall chart (Geographic Concentration: 6.36 highest)
Supply chain health gauge (1.47K / 2.95K = 49.8%)
Geographic heat map, supplier-level risk matrix
Target Users: Risk managers, Supply chain directors

3. Performance & Predictions

Actual vs Predicted delays (91.79% accuracy visualization)
KPI with trend: Current 7.94% vs Target 90%
Supplier performance scorecard with conditional formatting
Interactive slicers: Date range, Region, Supplier type, Risk category
Target Users: Operations managers, Procurement teams

Features: Cross-filtering, drill-through pages, bookmarks for scenarios, synced slicers across all pages

🔍 Key Findings


| **Finding** | **Impact** | **Recommendation** |
|------------|-----------|-------------------|
| **68% high-risk suppliers** | $998M revenue exposure; single failures = $10–30M loss | Launch emergency supplier audit; establish dual-source strategy for critical items within 90 days |
| **Geographic concentration (84% in Asia–Europe)** | Regional disruption could cripple 80%+ of supply chain | Rebalance to 30% Asia, 25% Europe, 30% Americas, 15% Other within 12 months |
| **Delivery crisis (7.94% vs 90% target)** | $10–15M annual costs in penalties, expediting, lost sales | Implement supplier performance tiers; deploy predictive model for proactive planning |
| **Top risk drivers: Geographic (6.36), Financial (6.30), Single-source (5.93)** | Account for 60%+ of total risk | Strategic network redesign focusing on diversification and supplier financial support |
| **Q4 performance degradation** | $5–8M predictable Q4 losses | Build inventory in Q3; pre-position safety stock; increase Q4 supplier monitoring |


💡 Strategic Recommendations
Immediate (0-3 Months) - $5M Investment

Emergency supplier summit with 20 worst performers
Financial health audits of all high-risk suppliers
Customer communication protocol using predictive model
Expected Impact: Reduce delays to 5.5 days, improve delivery to 40%, prevent 3-5 supplier failures

Short-Term (3-12 Months) - $15M Investment

Onboard 5-7 new suppliers in Americas for geographic diversification
Supplier development program for 15 underperformers
Real-time risk monitoring dashboard with automated alerts
Expected Impact: Reduce high-risk suppliers to 45%, improve geographic balance to 75/25

Long-Term (1-3 Years) - $30-45M Total Investment

Achieve <30% high-risk suppliers, 95%+ on-time delivery, <2 days avg delay
Deploy supply chain control tower with real-time visibility
Advanced analytics expansion (quality prediction, financial distress, geopolitical risks)
Expected Impact: $190-310M total value creation (420-690% ROI)


📏 Results & Validation
Model Performance

Prediction Accuracy: 91.79% (exceeds industry standard of 75-85%)
Correlation: 0.73 between risk scores and actual delays (strong relationship)
Validation: Out-of-sample testing on 20% holdout data; 95% confidence intervals

Business Impact

Risk Quantified: $997.98M revenue at risk from high-risk suppliers
Value Creation: $190-310M over 3 years (risk reduction, cost savings, revenue protection)
ROI: 420-690% on $30-45M investment
Stakeholder Buy-In: Unanimous executive approval for Phase 1 implementation

📊 Key Metrics Tracking

| **Metric** | **Baseline** | **Target (12 Months)** | **Status** |
|-----------|-------------|-----------------------|-----------|
| **Delivery Performance** | 7.94% | 85% | 🔴 To Improve |
| **Avg Delay Days** | 6.75 | 3.0 | 🔴 To Improve |
| **High-Risk Suppliers %** | 68% | 45% | 🔴 To Improve |
| **Supply Chain Health** | 1.47K (50%) | 2.2K (75%) | 🔴 To Improve |
| **Prediction Accuracy** | 91.79% | 93% | 🟢 Achieved |

🎓 Skills Demonstrated
Technical: Excel (XLOOKUP, SUMIFS, Power Query), Power BI (DAX, data modeling), Statistical Analysis, Predictive Modeling, Data Visualization
Business: Risk Management, Supply Chain Analysis, Strategic Planning, Stakeholder Management, ROI Analysis, Executive Communication
Soft Skills: Problem-solving, Critical Thinking, Data Storytelling, Attention to Detail (91.79% accuracy)

🚀 Future Enhancements

Real-time data integration via APIs for live risk monitoring
Machine learning models for quality defect and financial distress prediction
Multi-tier supplier mapping to identify upstream dependencies
Prescriptive analytics for automated optimization recommendations
External data enrichment (weather, financial markets, news sentiment)
ESG/Sustainability metrics integration



🏆 Project Outcomes
✅ Identified $998M in revenue at risk
✅ Built predictive model with 91.79% accuracy
✅ Created 3 interactive executive dashboards
✅ Delivered $190-310M value case with 420-690% ROI
✅ Secured executive approval for $30-45M investment
✅ Provided actionable roadmap for supply chain transformation


This project demonstrates end-to-end data analytics capabilities: from problem definition and data analysis to predictive modeling, dashboard creation, and strategic recommendations with quantified business impact.

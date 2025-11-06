# Crisis Management | Food & Beverages (F & B)

### Perform business/data analysis to provide insights and recommendations for crisis management in an online food delivery startup.

## 📌 Table of Contents
- <a href="#overview">Overview</a>
- <a href="#credits">Credits</a>
- <a href="#business-problem">Business Problem</a>
- <a href="#tools-technologies">Tools & Technologies</a>
- <a href="#project-structure">Project Structure</a>
- <a href="#research-questions--key-findings">Research Questions & Key Findings</a>
- <a href="#dashboard">Dashboard</a>
- <a href="#final-recommendations">Final Recommendations</a>
- <a href="#author-contact">Author & Contact</a>


<h2><a class="anchor" id="overview"></a>📝 Overview</h2>

This project aims to provide insights and recommendations for crisis management in an online food delivery startup. These recommendations will help senior leadership to plan and execute strategies to recover brand value, upgrade delivery infrastructure and monitor real-time customer sentiment.
- Preform primary analysis of client data across phases (pre-crisis vs. crisis)
- Prepare analysis report and recommendations with real-time dashboard
- Present insights and recovery implementation plan to stakeholders.

<h2><a class="anchor" id="credits"></a>🪪 Credits</h2>

This project is a part of the “_CodeBasics Resume Challenge #17_” course offered by **Codebasics** - All rights reserved.

- **Platform**: codebasics.io – All rights reserved.

<h2><a class="anchor" id="business-problem"></a>❓Business Problem</h2>

**QuickBite** Express is a Bengaluru-based food-tech startup, established in 2020 that connects customers with local restaurants and cloud kitchens through its food delivery platform.

**Mid-2025 Operational Crisis**:

In June 2025, they faced a major crisis that impacted operations and brand value. A viral social media incident involving food safety violations at partner restaurants, combined with a week-long delivery outage during the monsoon season, triggered massive customer backlash. Competitors capitalized with aggressive campaigns, worsening the situation.

**Crisis impact on Business**:

1. A large portion of active users disengaged within a short period. 
2. Daily orders saw a sharp decline compared to earlier months. 
3. Customer satisfaction scores fell sharply, signaling trust issues. 
4. Many partner restaurants shifted to competing platforms. 
5. Customer acquisition costs rose significantly. 


<h2><a class="anchor" id="tools-technologies"></a>🛠️ Tools & Technologies</h2>

| Tool/Platform | Purpose |
| :--- | :--- |
| Python | Primary Analysis |
| Tableau | Analysis Report |
| Power BI | Dashboard |
| Copilot | Code Assistance |
| ChatGPT | Content Writing |
| Nano Banana | Image Generation |
| Gamma AI | Presentation |

<h2><a class="anchor" id="project-structure"></a>📂 Project Structure</h2>

```
crisis-management-analysis/
│
├── README.md
├── .gitignore
├── problem-statement.pdf
│
├── notebooks/                  # Jupyter notebooks
│   ├── exploratory-data-analysis.ipynb
│
├── report/                    # Tableau Packaged Workbook file
│   ├── crisis-report.twbx
│
├── dashboard/                  # Power BI dashboard file
│   └── quickbite-dashboard.pbix
│
├── presentation/               # PowerPoint file
│   └── quickbite-dashboard.pbix
│
├── visuals/                    # Portable Network Graph files
│   └── quick-bite-logo.png
│   └── icon-set.png
│   └── food-delivery-icon.png
```

<h2><a class="anchor" id="research-questions--key-findings"></a>📝 Research Questions & Key Findings</h2>

### Question 1: 
- Monthly Orders: Compare total orders across pre-crisis (Jan–May 2025) vs crisis (Jun–Sep 2025). How severe is the decline?
- Revenue Impact: Estimate revenue loss from pre-crisis vs crisis (based on subtotal, discount, and delivery fee).

#### 🔍 Finding:
Due to the negative virality on social media, orders dropped by 58.86% in June 2025 with an overall downturn of 68.93% showcasing significant loss in demand loss and customer trust. Revenue followed a similar trend, falling 61.22% in June and 70.92% overall, leading to a significant financial strain.

#### 📊 Visualization:


### Question 2: 
- Which top 5 city groups experienced the highest percentage decline in orders during the crisis period compared to the pre-crisis period?
- Among restaurants with at least 50 pre-crisis orders, which top 10 high-volume restaurants experienced the largest percentage decline in order counts during the crisis period? 

#### 🔍 Finding:
Kolkata faced the largest drop among all 8 operational cities. However, it is also the city with the lowest order volume, fewest restaurant partners, and smallest customer base. Notably, the downturn for cities is between the range of 58% to 63%. A similar trend is observed in revenue. Moreover, the majority of our top restaurant partners (those with over 50 orders) have experienced a drop between 60% and 90%.

#### 📊 Visualization:

### Question 3: 
- Cancellation Analysis: What is the cancellation rate trend pre-crisis vs crisis, and which cities are most affected?
- Delivery SLA: Measure average delivery time across phases. Did SLA compliance worsen significantly in the crisis period?
- Ratings Fluctuation: Track average customer rating month-by-month. Which months saw the sharpest drop?
- Sentiment Insights: During the crisis period, identify the most frequently occurring negative keywords in customer review texts.
- Loyalty Impact: Among customers who placed five or more orders before the crisis, determine how many stopped ordering during the crisis, and out of those, how many had an average rating above 4.5? 

#### 🔍 Finding:
Customer experience and sentiment have been severely affected. Cancellation rates spiked to 12.51% indicating deep trust issues with the customers. Our pre-crisis SLA compliance pre-crisis was already below 50% but it has now dropped to 12.20% due to the week-long delivery outage during monsoon. Consequently, our healthy customer rating of 4.9 has dropped to 2.3. The major concern raised by the customers are poor food quality and safety issues. This has led to a significant increase in negative reviews and sentiment. Moreover, majority of our loyal customers (those with over 5 orders) have stopped ordering.


#### 📊 Visualization:

### Question 4: 
- Customer Lifetime Decline: Which high-value customers (top 5% by total spend before the crisis) showed the largest drop in order frequency and ratings during the crisis? What common patterns (e.g., location, cuisine preference, delivery delays) do they share? 

#### 🔍 Finding:
Nearly 84% of our top 5% customers have stopped ordering on our platform during the crisis, leading to a loss of 11% revenue potential (assuming similar purchase pattern). Bangaluru saw the largest drop in top 5% customers, which is notable considering it has the largest customer base. For the remaining 16% of the active top customers, the average sentiment score has declined. This decline is likely due to the overall negative customer experience. 

#### 📊 Visualization:

<h2><a class="anchor" id="dashboard"></a>Dashboard</h2>

### Executive View: 

### Restaurant & Delivery Partner View: 

### CRM View: 

<h2><a class="anchor" id="final-recommendations"></a>📝 Final Recommendations</h2>

### Root Cause Analysis & Quality Reinforcement
1. Execute thorough food & safety audits across the top 10 kitchens in each of the 8 cities to identify root causes of quality issues.
2. Introduce a “Quality Verified” badge to partner restaurants meeting strict hygiene and safety standards.
3. Launch “We Heard You” — a social media campaign acknowledging feedback and showcasing corrective measures.
4. Roll out “Quick Bhi, Quality Bhi” — emphasizing fast yet quality assured delivery standards.

### SLA Compliance & Partner Performance
1. Introduce a new “Dispatch Time” metric to track kitchen efficiency and handover speed.
2. Enable real-time order tracking for customers and partners to increase transparency.
3. Deploy a Real-Time SLA Compliance Dashboard with performance-based bonuses for partners achieving defined SLA targets (Expected Delivery Time).

### Customer Win-Back & Retention
1. Use customer purchase history to send targeted push notifications and product recommendations to re-engage dormant users.
2. Introduce “Aur Quantity Bhi” weekend promos (numeric discounts or BOGOF offers) to drive weekend traffic.
3. Launch Reward Points for customers with more than three completed orders, redeemable for discounts.
4. Partner with regional food reviewers, lifestyle, and fitness creators to promote new offerings.
5. Fitness creators will spotlight our high-protein and vegan meal catalogue, positioning the brand as a healthier choice.


<h2><a class="anchor" id="author-contact"></a>🧑🏽‍🦱 Author & Contact</h2>

**Gaurav Patil** (Data Analyst) 
- 🔗 [LinkedIn](https://www.linkedin.com/in/gaurav-patil-in/)


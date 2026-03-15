# **A/B Testing Analysis: Landing Page Conversion Experiment**

A company tested a new landing page design to determine whether it improves user conversion rates compared to the existing page.

The objective of this analysis is to evaluate whether the treatment page produces a statistically significant improvement in conversion performance.

**Total Users:** 290,584

Control Group: 145,274 users
Treatment Group: 145,310 users

**Metrics analyzed:**
• User conversions
• Conversion rate
• Daily experiment performance

**Tools Used:**

SQL – experiment metric calculations
Python – statistical analysis and visualization
Tableau – interactive dashboard and reporting

## **Analysis Workflow**

1. **Data Cleaning**

Removed duplicates and ensured balanced experiment groups.

2. **Conversion Rate Analysis**

Control Conversion Rate:   12.04%
Treatment Conversion Rate: 11.88%
Conversion Lift:          -1.33%

3. **Statistical Testing**

Performed a two-proportion z-test to determine if the difference in conversion rates is statistically significant.

**Result:**

p-value > 0.05

The experiment does not show statistically significant improvement.


**Tableau dashboard:** https://public.tableau.com/views/WebsiteABTestAnalysis/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

Key Insights
• Traffic distribution between experiment groups was balanced.
• Treatment page slightly underperformed the control page.
• No statistically significant improvement was observed.
• The company should retain the existing landing page.

**Repository Structure:**
data/        – experiment datasets
notebooks/   – Python analysis
dashboard/   – Tableau dashboard screenshot

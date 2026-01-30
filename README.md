# Bank-churn-Analysis-project
Interactive Excel dashboard analyzing bank customer churn, engagement, credit score, and balance trends using KPIs, pivot tables, slicers, and data visualization to derive actionable business insights.
Customer churn is one of the most expensive problems in the banking industry.
Acquiring a new customer costs 5–7× more than retaining an existing one. Even a small increase in churn can lead to significant revenue loss, reduced lifetime value, and weaker customer trust.

Objective of this project:
To identify behavioral, financial, and engagement-based factors that influence customer churn and provide actionable insights for improving customer retention.

2️ Key Business Questions Answered

This project was designed to answer real executive-level questions, such as:

Who is most likely to churn?

Does geography influence churn or credit quality?

Do engaged customers (credit cards, multiple products) churn less?

Are early-stage customers at higher risk?

Which KPIs should leadership monitor to reduce churn?

 Data & Metrics Used (WHAT was analyzed)

The dataset includes customer-level information such as:

Geography (France, Germany, Spain)

Gender

Credit score

Account balance

Number of products used

Credit card ownership

Active membership status

Customer tenure

Churn indicator

From this data, I derived business KPIs, not just raw numbers.

 KPI Framework (WHY these KPIs were chosen)
 Churn Rate

Purpose:
Measures customer attrition and highlights risk concentration.

Why it matters:
This is the primary metric banks track to evaluate retention performance.

 Active Member Percentage

Purpose:
Identifies customer engagement levels.

Why it matters:
Engaged customers interact more frequently, build habits, and are less likely to churn.

 Average Balance

Purpose:
Estimates customer value to the bank.

Why it matters:
High-balance customers contribute more to profitability and deserve priority retention efforts.

 Average Credit Score

Purpose:
Evaluates financial stability and risk profile.

Why it matters:
Helps determine whether churn is driven by risk or behavior.

 Deep Dive: Key Insights & Professional Reasoning
 Insight 1: Customers with fewer products show significantly higher churn

What the data shows:
Customers using only one product have the highest churn rates, while churn decreases as product count increases.

Professional Reasoning:
Customers with multiple products (e.g., savings + credit card + loans) are more embedded in the bank’s ecosystem. This creates switching costs—both financial and psychological—making churn less likely.

Business Recommendation:

Focus on cross-selling strategies

Offer bundled products early in the customer lifecycle

Use churn risk models to identify low-product customers

 Insight 2: Credit card ownership strongly correlates with engagement

What the data shows:
Credit card holders are more active and churn less than non-cardholders.

Professional Reasoning:
Credit cards increase:

Transaction frequency

Customer touchpoints

Dependency on bank services

This makes customers habit-driven, which improves retention.

Business Recommendation:

Promote credit card adoption among new customers

Use card usage as an engagement KPI

Target inactive cardholders with reactivation campaigns

 Insight 3: Geography does NOT significantly impact credit score or churn risk

What the data shows:
ANOVA results indicate no statistically significant difference in average credit scores across France, Germany, and Spain.

Professional Reasoning:
This suggests that customer financial behavior is consistent across regions, and churn drivers are more behavioral than geographic.

Business Recommendation:

Avoid region-specific credit policies

Apply standardized risk and retention strategies

Focus resources on behavior-based segmentation instead

 Insight 4: Early-tenure customers have the highest churn risk

What the data shows:
Customers in the early years of tenure churn more than long-term customers.

Professional Reasoning:
Early customers:

Haven’t built trust

Haven’t integrated deeply with bank services

Are still comparing alternatives

Once tenure increases, relationship strength and inertia reduce churn.

Business Recommendation:

Strengthen onboarding programs

Introduce loyalty incentives in the first 2–3 years

Assign proactive outreach to early-tenure customers

 Statistical Validation (WHY decisions are trustworthy)

Instead of relying only on visuals:

T-tests were used to compare balances of churned vs non-churned customers

ANOVA tested credit score differences across geographies

Result:
Findings are data-backed and statistically validated, not assumptions.

 Dashboard Design Philosophy (HOW insights are delivered)

The dashboard was built to support:

Executive decision-making

Interactive exploration via slicers

Clear KPI visibility

Storytelling through visuals
Customer churn is driven primarily by engagement and tenure rather than geography or credit risk. Customers with fewer products, no credit card, and shorter tenure show the highest churn risk. Improving early engagement, increasing product adoption, and leveraging credit cards as retention tools can significantly reduce churn and improve customer lifetime value.

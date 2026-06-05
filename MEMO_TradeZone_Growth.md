---
 **MEMO**
 
To: Head of Growth & Head of Seller Operations

From: Gloria Austin, Data Analyst

Date: April 2025

Subject: TradeZone Performance Review, 2023 to 2024

**Executive Summary**

TradeZone saw strong growth between 2023 and 2024, but this growth is masking two key  issues that need immediate attention. Conversion rates remain below 50% across all states, and platform revenue is heavily dependent on a small group of high-spending customers. Both pose a real risk to sustainable growth going into 2025.

**Key Findings**

- New customers are not converting (Q1): Lagos recorded the highest number of new customers in 2024 (146), but only 49.32% of them made a purchase within their first 30 days. Other states performed even worse, Kano at 31.03% and Oyo at 33.33%. Across all five states, more than half of new users signed up but never completed a transaction within their first month. This shows we are bringing users in but not activating them. 
- Electronics is carrying the entire platform (Q2): All top 10 products that generated the highest revenue in 2024 came from the Electronics category. The HP Pavilion 15 Laptop alone generated over ₦26 million in revenue. No other category appeared in the top 10, despite ongoing promotion across the platform. This suggests that revenue is not well distributed, and other categories are underperforming compared to investment.
- Revenue depends on very few customers (Q5): A total of 603 High Spenders generated over ₦866 billion, while Medium and Low Spenders combined (74 customers) contributed less than ₦3 billion. This shows a very high dependency on a small segment of users. If even a small portion of these customers churn, the impact on revenue will be significant.

**Recommendations**

1. Launch a 30-day activation programme for new sign-ups
The Growth team should introduce a structured onboarding flow, including a first purchase discount or incentive within 48 hours of sign-up, backed by reminders and targeted product suggestions.
If Lagos conversion improves from 49% to even 60%, this will lead to a noticeable increase in transactions monthly.

Expected outcome (60–90 days):
A 10 to 15% increase in conversion rates in all states. (Based on Q1)

2. Build a retention programme for High Spenders
Growth and Seller Operations should identify the top 200 High Spenders and place them on a retention track. This can include faster fulfilment, priority support, or loyalty rewards. Given how much revenue this group drives, even small improvements will have a big impact.

Expected outcome (60–90 days):
Improved retention and reduced churn within the high value customer segment. (Based on Q5)

**Data Quality Notes**

Two major issues stood out during cleaning:
- There were inconsistencies in key categorical fields across the dataset. City names appeared in multiple formats with some clear typos.These were standardized to ensure consistency. In addition, some mismatches between sellers and their assigned product categories were observed. For example, SkinGlow NG and GlowBeauty Shop were listed under Books & Stationery instead of Beauty & Personal Care. This issue was identified during analysis but not adjusted in the dataset, which means some category-level results may be slightly distorted.
- 1,510 orders (about 50% of total orders) had missing delivery dates. Most of these were linked to orders that were not delivered, so the missing values were expected. However, orders marked as “Delivered” without a delivery date were treated as data entry issues, flagged, and excluded from fulfilment analysis.
If some of these excluded records were actually valid deliveries, then the seller's fulfillment results in Q3 may appear slightly faster than they truly are.

**What the Data Cannot Tell Us**

The dataset does not explain why customers are not converting within their first 30 days.
To answer this properly, we need to;
- Access user behaviour data like app activity and product views.
- Determine what drove the users to our platform. 
- Conduct customer feedback or session tracking. This will help us understand whether the issue is pricing, user experience, trust, or product relevance.
---

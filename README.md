# Customer Segmentation & Retention Insights in Vehicle Insurance

## Table of Contents
1. [Project Background](#1-project-background)
2. [Executive Summary](#2-executive-summary)
3. [Recommendations](#3-recommendations)
4. [Key Takeaways](#4-key-takeaways)

---

## 1. Project Background
In today's highly competitive insurance industry, understanding customer behavior is critical for mitigating risk, enhancing retention, and optimizing pricing strategies. This project focuses on customer segmentation to uncover actionable insights in key areas, including:

- The impact of discount strategies on claims and risk.
- The relationship between cancelled accounts and their effect on written premiums.
- How age and credit scores influence risk and retention.

The analysis was conducted using Python, leveraging its powerful libraries for data cleansing, processing, and visualization to generate meaningful insights through comprehensive charts and graphs.

---

## 2. Executive Summary
This analysis delves into key metrics for customer segmentation and retention within the personal vehicle insurance industry, uncovering insights into risk, behavior, and performance across various dimensions:

### Discount Combinations and Claims Analysis:
- The top 5 discount combinations were selected based on the highest total loss payments and were analyzed to evaluate their impact on both loss payments, loss counts, and loss ratios:
  - **"OCCU"**: $1.89 million in total loss payments and 137 loss counts, with a loss ratio of 89.14% (healthy).
  - **"OCCU SENI"**: $1.22 million in total loss payments and 81 loss counts, with a loss ratio of 104.24% (requires reassessment).
  - **"LOYA OCCU"**: $448K in total loss payments and 33 loss counts, with a loss ratio of 89.97% (healthy).
  - **"FARM OCCU"**: $268K in total loss payments and 18 loss counts, with a loss ratio of 93.45% (healthy).
  - **"FARM OCCU SENI"**: $215K in total loss payments and 15 loss counts, with a loss ratio of 103.88% (requires reassessment).

![TOP5_loss_earned_Discount](https://github.com/user-attachments/assets/230c50b2-66bb-4cb8-9247-b92c91238839)
![Disc_comb_losscount](https://github.com/user-attachments/assets/043ff344-2363-4a30-9719-eb7cd7c06b25)
![Disc_comb_vs_Loss_payment](https://github.com/user-attachments/assets/36dcca84-762b-4bff-8a7d-d87aba48c31e)

### Cancelled Accounts and Premium Trends:
- From January to March, the number of cancelled accounts and the total written premiums were at their lowest.
- After March, there was a significant increase, with September to November being the three highest months for cancellations and written premiums.
  
![Written_Prem_VS_Cancelled_accts](https://github.com/user-attachments/assets/6e5acace-d6b2-43f3-b716-f9642c8b9c0d)



### Age-Related Risk Factors:
- The 26-34 age group demonstrates a loss ratio of 98.65%, indicating high claims relative to premiums.
- The 55-64 age group has a 100% loss ratio, representing a critical area for risk assessment and management.
  
![RateAndLossRatio_vs_age_range](https://github.com/user-attachments/assets/6602e0a3-71d9-4003-8a6b-93e78c96db30)

### Credit Score and Retention Analysis:
- The analysis of credit groups (0-580, 581-650, and 651 and above) showed no consistent trend in churn rates across months.
- Churn rates varied significantly, with higher rates observed in certain months, such as December, where the 0-580 group reached 37.14%, and the 651+ group reached 49.75%.
  
![credit_score_vs_churn_rate](https://github.com/user-attachments/assets/9aac36df-e11e-4b89-a48d-9df9e53a7b0e)

---

## 3. Recommendations
Based on the key findings, the following recommendations are proposed:

### Discount Combinations and Claims Analysis:
1. Reassess the pricing structure and eligibility criteria for **"OCCU SENI"** and **"FARM OCCU SENI"** due to their loss ratios exceeding 100%.
2. Focus on promoting discount strategies that demonstrate better cost-effectiveness without significantly increasing loss exposure.

### Cancelled Accounts and Premium Trends:
1. Investigate the reasons for the increase in cancellations after March and during the high-cancellation months (September to November).
2. Implement retention strategies, such as personalized offers or loyalty rewards, during periods of historically high cancellations to reduce churn.

### Age-Related Risk Factors:
1. Review underwriting policies for the 26-34 and 55-64 age groups to address the high loss ratios observed.
2. Introduce age-specific risk mitigation measures, such as targeted marketing campaigns, risk-based premiums, or tailored insurance packages.

### Credit Score and Retention Analysis:
1. Conduct further analysis of customer behavior across credit score groups to understand the drivers of churn, particularly for groups with higher churn rates.
2. Strengthen engagement strategies for the 0-580 and 581-650 credit groups by offering financial counseling, flexible payment options, or value-added services to increase retention.

---

## 4. Key Takeaways

### Discount Combinations and Claims:
- While some discount groups, such as **"OCCU"**, show high loss payments, their loss ratios remain in a healthy range.
- **"OCCU SENI"** and **"FARM OCCU SENI"** exceed a 100% loss ratio, indicating the need for reassessment to maintain profitability.

### Cancelled Accounts and Premium Trends:
- Cancellation trends reveal critical periods (post-March and September to November) where customer retention efforts need reinforcement. These patterns can guide targeted interventions to reduce churn during high-risk months.

### Age-Related Risk Factors:
- Specific age groups, such as 26-34 and 55-64, exhibit notably high loss ratios, indicating the need for age-tailored strategies to mitigate risk and enhance underwriting practices.

### Credit Score and Retention:
- Credit score appears to influence churn rates, but the patterns vary across months and groups. A deeper understanding of customer needs and behaviors in lower credit tiers can help refine retention initiatives.

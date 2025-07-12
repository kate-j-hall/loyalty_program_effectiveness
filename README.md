# 🛒 Loyalty Program Effectiveness Case Study

This repository analyzes the effectiveness of a loyalty program using transactional and customer segmentation data, focusing on sales trends before and after a competitor’s campaign.

---

## 📦 Project Overview

- **Dataset:** 4 CSV files (transactions, reward card mapping, customer segments, engagement data)
- **Goal:** Identify key drivers behind sales declines post-competitor campaign and recommend data-driven loyalty incentives.
- **Approach:**
  - Loaded and joined data using BigQuery SQL
  - Analyzed pre/post trends across sales, customers, sales per customer, share of wallet
  - Segmented by lifestage and value tiers to find impacted cohorts
  - Proposed targeted bonus reward campaigns
  - Modeled campaign lift and profitability

---

## 📁 Repository Contents

- `data/` : Raw input CSV files
- `reports/` : Written summary of insights and recommendations
- `README.md/` : Project documentation

---

## 💡 Key Findings

✅ Sales dropped -5.2% after Week 25 (competitor launched collectables campaign)  
✅ Main driver: lower **sales per customer** (-3.6%) vs fewer customers (-1.7%)  
✅ Family segments (Older & Young Families) accounted for ~56% of the decrease  
✅ Bonus reward offers could recoup ~84% of lost sales cost-effectively

---

## 💥 Recommendations

- Launch $5-off offers targeting high-value family segments with $250+ spend thresholds.
- Expand scope with segmented “Mystery Shop” offers tied to app/email sign-ups.
- Run A/B tests comparing bonus points vs discount offers.
- Conduct data quality checks on engagement signals to improve future targeting.

---

👤 **Created by:** Kate Hall (July 2025)

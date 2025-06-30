# Proactive Churn Reduction Strategy for Cell2Cell

**Objective:**  
Help Cell2Cell predict customer churn and deploy a proactive retention campaign to boost loyalty and reduce revenue loss.

---

## Expectations

1. **Part 1 (Modeling & Insights):**  
   - Build and compare a decision tree and logistic-regression churn model.  
   - Identify top churn drivers.  
   - Recommend targeted offers for four sample customers.  

2. **Part 2 (Campaign Design & Simulation):**  
   - Translate the best model into an Excel “pilot” spreadsheet.  
   - Specify which of the 31,047 at-risk customers to target, what offers to give, and how to communicate.  
   - Project retention lift, LTV gain, and ROI.

---

## What We Delivered

### Part 1: Predictive Modeling & Insights
- **Data Prep:** Cleaned calibration and test sets, accounted for over-sampling.  
- **Models:**  
  - **Decision Tree** (chosen): Recall 65.6%, Lift 1.33, Accuracy 60.0%  
  - **Logistic Reg.**: Recall 57.1%, Lift 1.30, Accuracy 57.6%  
- **Key Drivers:**  
  - Equipment age (Eqpdays) ↑ → churn risk  
  - Refurbished handsets → +29.5% churn odds  
  - Retention calls (Retcall) ↑ → churn risk  
  - Roaming usage (Roam) ↑ → churn risk  
- **Sample Offers:** Personalized device-upgrade discounts, loyalty credits, network-upgrade trials, with expected 30–40% churn reduction per user.

### Part 2: Proactive Retention Campaign
- **Targeting:** Clustered top risk segments (clusters 4, 11, 14, 17) vs. blanket approach.  
- **Offers & Channels:**  
  1. **Discounted phones** for long-tenure users  
  2. **Better overage plans** for high-usage customers  
  3. **Subscription optimization** for low-usage accounts   
- **Projected Impact (Clustered Pilot):**  
  - **1,667 customers targeted**  
  - **Churn down** 2.0%→1.9% (–5%)  
  - **LTV gain:** +\$4.39 M (ROI 757%)  
- **Comparison:**  
  - **Ungrouped targeting:** 7,238 customers → churn 1.7% (–15%), LTV +\$10.9 M (ROI 653%)

---

_Open the PPT decks for full visuals and speaker notes, and the Excel pilot for “what-if” simulations._

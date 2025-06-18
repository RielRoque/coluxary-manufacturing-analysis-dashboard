# Coluxary Manufacturing Analysis

<div align="center">
  <img src="https://github.com/RielRoque/coluxary-manufacturing-analysis-dashboard/blob/main/dashboard%20riel.png?raw=true" width="100%">
</div>

<div align="center">
> Project for the **EMERSON X DAPH National Data Challenge**  
> 📊 Focused on downtime diagnostics, operator performance, and production efficiency  
> 🔗
</div>
---

### Table of Contents

[1. Background](#background)  
[2. Objective](#objective)  
[3. Key Metrics](#key-metrics)  
[4. Downtime Analysis](#downtime-analysis)  
[5. Operator Performance](#operator-performance)  
[6. Daily Trends](#daily-trends)  
[7. Recommendations](#recommendations)  
[8. Key Takeaways](#key-takeaways)  

---

## 1. Background <a name="background"></a>

<p align="justify">
Coluxary is a manufacturing facility analyzed as part of the EMERSON x DAPH National Data Challenge. This project explores production inefficiencies, downtime factors, operator behavior, and batch process failures using real operational logs. The findings aim to guide data-informed decisions for improving plant performance.
</p>

---

## 2. Objective <a name="objective"></a>

<p align="justify">
The goal is to conduct a comprehensive analysis of Coluxary’s operational performance, identify major contributors to inefficiency, and offer actionable, data-driven strategies. This includes evaluating root causes of downtime, operator gaps, and batch-level disruptions.
</p>

---

## 3. Key Metrics <a name="key-metrics"></a>

- **🟡 Current Efficiency**: 64%  
- **🎯 Target Efficiency**: 85%  
- **📉 Efficiency Gap**: 21% (23 hours of unproductive time out of 64 hours logged)  

> 41 hours productive vs. 23 hours lost = urgent need to minimize downtime.

---

## 4. Downtime Analysis <a name="downtime-analysis"></a>

**Total Downtime**: 1,388 minutes (~23 hours)  
- 🔧 Machine Adjustment – 332 mins  
- ⚙️ Machine Failure – 254 mins  
- 📦 Inventory Shortage – 226 mins  
- 🔄 Batch Change – 161 mins  
- 🧾 Coding Error – 146 mins  

📊 **Breakdown**:
- 56% of downtime = Operator-related  
- 44% = Machine-related  
- 🧠 Top 5 reasons = 80% of total downtime

---

## 5. Operator Performance <a name="operator-performance"></a>

| Operator | Efficiency | Uptime (mins) | Downtime (mins) | Notes |
|----------|------------|----------------|------------------|-------|
| Charlie  | 66.84%     | 774            | 384              | Top Operator |
| Mac      | 60.94%     | 518            | 332              | Least Efficient Operator |

> Charlie outperformed peers but still fell short of the 85% benchmark. Mac's performance highlights gaps in training and consistency.

---

## 6. Daily Trends <a name="daily-trends"></a>

- 📅 **September 2**: Highest recorded downtime — 503 mins  
- 📅 **August 30**: Second highest — 444 mins  

These recurring spikes suggest specific dates are operational bottlenecks, possibly tied to shift changes, machine wear, or poor inventory planning.

---

## 7. Recommendations <a name="recommendations"></a>

- **👨‍🏭 Address Operator Gaps**:  
  - Train Mac, document and replicate Charlie’s methods  
  - Set efficiency KPIs per operator  

- **🔧 Reduce Downtime at Source**:  
  - Standardize machine setup  
  - Improve preventive maintenance  
  - Reinforce inventory availability

- **📦 Fix Batch Process Breakdown**:  
  - Investigate root causes of 35/38 failed batches  
  - Strengthen handoffs and SOP compliance  

- **📈 Phase-Based Targeting**:  
  - Start with 70% efficiency goal in 2 weeks  
  - Use weekly reviews + operator scorecards

- **🗓️ Introduce Daily Monitoring**:  
  - Log downtime by category/operator  
  - Visualize recurring trends via heatmaps

---

## 8. Key Takeaways <a name="key-takeaways"></a>

- **🚫 Underperformance Drivers**:  
  - Mechanical inefficiencies  
  - Inconsistent batch execution  
  - Uneven operator performance  

- **✅ Action Priorities**:  
  - Fix machine adjustments  
  - Address Mac’s performance  
  - Improve batch transition process

---

### Tools & Technologies Used

- Power BI (Interactive Dashboard & Visuals)  
- Excel (Pre-analysis inspection)  
- Power Query


---

**Crafted with purpose for the EMERSON X DAPH Data Challenge by Riel Roque** 🚀

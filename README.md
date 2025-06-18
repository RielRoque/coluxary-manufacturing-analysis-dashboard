# Coluxary Manufacturing Analysis

<div align="center">
  <img src="https://github.com/RielRoque/coluxary-manufacturing-analysis-dashboard/blob/main/coluxary%20dashboard.png" width="100%">
</div>

> Project for the **EMERSON X DAPH National Data Challenge**  
> 🔗

---

### Table of Contents <a name="toc"></a>

[1. Background](#background)  <br>
[2. Objective](#objective)<br>
[3. Insights Deep-Dive](#insights-deep-dive) <br>
&nbsp;&nbsp;&nbsp;&nbsp;[3.1. Key Metrics](#key-metrics)  <br>
&nbsp;&nbsp;&nbsp;&nbsp;[3.2. Impact Of Operator and Machine-Related Downtime On Production Efficiency](#Impact-Efficiency)  <br>
&nbsp;&nbsp;&nbsp;&nbsp;[3.3. Primary Causes of Downtime](#Causes-Downtime)  <br>
&nbsp;&nbsp;&nbsp;&nbsp;[3.4. Uptime and Downtime Vary Among Operators](#Downtime-Days)  <br>
&nbsp;&nbsp;&nbsp;&nbsp;[3.5. Peak Downtime Days](#DowntimeUptime-Operators)<br>
&nbsp;&nbsp;&nbsp;&nbsp;[3.6. Operator Performance](#operator-performance)  <br>
[4. Recommendations](#recommendations)  <br>
[5. Key Takeaways](#key-takeaways)  <br>

---

## 1. Background <a name="background"></a>

<p align="justify">
Coluxary is a manufacturing company analyzed as part of the EMERSON x DAPH National Data Challenge. This project explores production inefficiencies, downtime factors, operator behavior, and batch process failures using real operational logs. The findings aim to guide data-informed decisions for improving plant performance.
</p>

---

## 2. Objective <a name="objective"></a>

<p align="justify">
To provide comprehensive analysis of Coluxary's production efficiency, focusing on performance-impacting factors and offering data-driven recommendations. We will explore the root causes of downtime, assess batch flow interruptions, evaluate operator performance, and identify notable daily trends. The goal is to support operations managers and decision-makers with insights to guide targeted improvements aligned with efficiency objectives.
</p>

---
## 3. Insights Deep-Dive <a name="insights-deep-dive"></a>
<a href="#toc">[ back to contents ]</a>

### 3.1. Key Metrics <a name="key-metrics"></a>  <a href="#toc">[↑]</a>

<div align="center">
  <img src="https://github.com/RielRoque/coluxary-manufacturing-analysis-dashboard/blob/main/KP1.png?raw=true" width="85%">
  <img src="https://github.com/RielRoque/coluxary-manufacturing-analysis-dashboard/blob/main/KPI2.png?raw=true" width="85%">
</div> <br>

- <p align="justify"> Production Efficiency:
Current efficiency stands at 64%, falling short of the 85% target. The performance gap suggests room for improvement, particularly by examining the practices of high-performing operators like Charlie, compared to lower-performing ones such as Mac. Although Charlie seems the highest performing operator, we cannot deny the fact the he is still way below the 85% standard production efficiency. Therefore all of them must undergo a comprehensive training and a weekly monitoring of performance </p>

- <p align="justify"> Production Time:
Out of 64 total hours, only 41 hours were spent in actual production, with 23 hours lost to downtime. The leading cause of this downtime is "Machine Adjustment." Addressing this issue could significantly improve overall productivity. </p>

- <p align="justify"> Batches Processed:
A total of 38 batches were processed, but only 3 were completed, with 35 experiencing disruptions. Batch 422147 was identified as a major source of issues. Further investigation is needed to determine the root causes of batch delays and implement corrective actions </p>

---
### 3.2. Impact Of Operator and Machine-Related Downtime On Production Efficiency <a name="Impact-Efficiency"></a>  <a href="#toc">[↑]</a>

<div align="center">
  <img src="https://github.com/RielRoque/coluxary-manufacturing-analysis-dashboard/blob/main/impact%20of%20operator%20and%20machine%20downtime%20on%20production%20efficiency%20chart.png?raw=true" width="60%">
</div> <br>

- <p align="justify"> Impact Of Operator and Machine-Related Downtime On Production Efficiency:
Production efficiency is currently at 64%, underscoring a significant performance gap. Of the 23 hours lost to downtime, 56% stem from operator-related issues, while the remaining 44% are due to mechanical failures and maintenance. Notably, the CO-600 product accounts for the highest share of downtime, with 494 minutes. This product represents a key operational bottleneck and warrants immediate attention to improve overall output.</p>

---
### 3.3. Primary Causes of Downtime <a name="Causes-Downtime"></a>  <a href="#toc">[↑]</a>

<div align="center">
  <img src="https://github.com/RielRoque/coluxary-manufacturing-analysis-dashboard/blob/main/primary%20causes%20chart.png?raw=true" width="60%">
</div> <br>

- <p align="justify"> Downtime Causes:
Production efficiency is currently at 64%, underscoring a significant performance gap. Of the 23 hours lost to downtime, 56% stem from operator-related issues, while the remaining 44% are due to mechanical failures and maintenance. Notably, the CO-600 product accounts for the highest share of downtime, with 494 minutes. This product represents a key operational bottleneck and warrants immediate attention to improve overall output.</p>


### 3.4. Uptime and Downtime Vary Among Operators <a name="Downtime-Days"></a>  <a href="#toc">[↑]</a>

<div align="center">
  <img src="https://github.com/RielRoque/coluxary-manufacturing-analysis-dashboard/blob/main/UPTIME%20AND%20DOWNTIME%20AMONG%20OPERATORS.png?raw=true" width="60%">
</div> <br>

- <p align="justify"> Charlie records the highest uptime at 774 minutes, indicating the largest operational contribution among all operators. However, he also has the highest downtime at 384 minutes, pointing to a significant amount of non-productive time. In contrast, Mac shows a lower uptime of 518 minutes—comparable to Dennis—but still accumulates a notable 332 minutes of downtime. This suggests that while Charlie handles substantially more workload, his efficiency is offset by frequent interruptions</p>


### 3.5. Peak Downtime Days <a name="DowntimeUptime-Operators"></a>  <a href="#toc">[↑]</a>

<div align="center">
  <img src="https://github.com/RielRoque/coluxary-manufacturing-analysis-dashboard/blob/main/uptime%20and%20downtime%20among%20operators%20chart.png?raw=true" width="60%">
</div> <br>

- <p align="justify"> The chart highlights two distinct peaks in downtime: the highest on September 2nd (503 minutes), and a significant peak on August 30th (444 minutes). Downtime was notably lower on August 29th (244 minutes), reached its lowest point on August 31st (165 minutes), and dropped to very low levels by September 3rd. This indicates a fluctuating pattern with specific days experiencing major operational interruptions.</p>

### 3.6. Operator Performance <a name="operator-performance"></a>  <a href="#toc">[↑]</a>

<div align="center">
  <img src="https://github.com/RielRoque/coluxary-manufacturing-analysis-dashboard/blob/main/operator%20performance%20table.png?raw=true" width="60%">
</div> <br>

- <p align="justify">Charlie leads in efficiency at 66.84%, the highest among all operators, with the lowest inefficiency rate of 33.16%. He completed 1 batch despite experiencing 10 disruptions. In contrast, Mac is the least efficient at 60.94%, with the highest inefficiency rate of 39.06%, also completing 1 batch but with fewer disruptions (7). Dennis, although he completed no batch, maintains a 63.17% efficiency, affected by 8 disruptions. Dee falls in the middle with a 64.08% efficiency, completing 1 batch and encountering 10 disruptions. The overall team efficiency stands at 64.02%.</p>


## 7. Recommendations<a name="recommendations"></a>

- <p align="justify">Reduce Downtime at Source
Prioritize top 3 causes: Machine Adjustment, Failure, Inventory Shortage. Standardize setup, strengthen preventive maintenance, and ensure stock readiness.</p>

- <p align="justify">Address Operator Gaps
Provide targeted coaching to Mac, benchmark Charlie's methods, and set operator-level KPIs for efficiency, disruptions, and uptime.</p>

- <p align="justify">Fix Batch Process Breakdown
Analyze reasons for batch failures (35 of 38), investigate SOPs for starting/switching batches, and improve cross-role communication during handoffs.</p>

- <p align="justify">Introduce Daily Monitoring
Log daily downtime by category, operator, and machine. Investigate recurring delays on peak days, and use visuals to spot patterns.
</p>

- <p align="justify">Phase-Based Targeting
Set short-term goals (e.g., 70% efficiency in 2 weeks). Use weekly reviews and operator scorecards to track progress, avoiding rushing to 85% as it might have a negative impact instead of positive.

</p>

- <p align="justify">Implementing these strategic recommendations will be critical for our success. We advocate for a phased approach, starting with immediate actions to reduce downtime and improve operator performance. Establishing clear KPIs and regular monitoring will ensure accountability and allow us to adapt our strategy as we progress towards our ultimate efficiency goals.
</p>


## 8. Key Takeaways <a name="key-takeaways"></a>

- <p align="justify">Underperformance Causes
Production is underperforming due to mechanical inefficiencies, batch execution problems, and uneven operator performance.

</p>

- <p align="justify">Key Improvement Areas
Focus on the top 5 downtime issues, reinforce operator training, and improve batch workflow to directly raise efficiency.

</p>

- <p align="justify">Immediate Priorities
Begin with Machine Adjustments, Macs performance, and the underlying causes of batch disruptions for the most immediate impact. 

</p>

---

### Tools & Technologies Used

- Power BI (Interactive Dashboard & Visuals)  
- Excel (Pre-analysis inspection)  
- Power Query (Data Manipulation and Cleaning)


---

**EMERSON X DAPH Data Challenge by Riel Roque** 🚀

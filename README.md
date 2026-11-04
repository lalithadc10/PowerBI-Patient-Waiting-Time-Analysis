#  Patient Waiting Time Analysis | Power BI

Welcome to my **Patient Waiting Time Analysis** project.

This project was inspired by **Workout Wednesday 2026 – Week 39**, which challenged me to create a histogram with adjustable bin widths using Power BI.

Instead of stopping at the original challenge, I extended the analysis into a three-page interactive dashboard using the same clinic waiting-time dataset.

The objective was to understand patient waiting-time patterns across two clinic locations, explore how waiting times change over time, and identify cases that require further investigation.

My approach focused on connecting **business questions, analytical thinking, DAX calculations, and meaningful visualizations**.

---

#  Project Analysis Summary

| Page | Analysis | Business Questions | Key Concepts |
|------|----------|-------------------|--------------|
| Page 1 | Waiting Time Distribution | Do both clinic locations provide a similar waiting-time experience? | Histogram, Dynamic Bin Width, Standard Deviation, Disconnected Tables, SELECTEDVALUE |
| Page 2 | Waiting Time Trends & Patterns | When do waiting times vary? Are certain days associated with longer waits? | Time Analysis, AVERAGE, COUNTROWS, Day-of-Week Analysis, Matrix |
| Page 3 | Waiting Time Investigation | Which locations and individual cases require further attention? | CALCULATE, FILTER, DIVIDE, Threshold Analysis, Interactive Slicers |

---

#  Page-wise Analysis

## 1. Waiting Time Distribution

**Business Question:**

Are patients experiencing similar waiting times at Site A and Site B, even though their average waiting times are almost identical?

### What I Explored

- Average waiting time across both locations.
- Standard deviation to understand variation.
- Dynamic histogram with adjustable grouping intervals of 1, 2, 5 and 10 minutes.
- Distribution comparison using small multiples.
- Percentage of cases within each waiting-time range.

### Key Findings

- Both clinic locations recorded an average waiting time of approximately **14.78 minutes**.
- Site A had a standard deviation of approximately **5.3 minutes**.
- Site B had a standard deviation of approximately **2.7 minutes**.
- Site A showed greater variation in waiting times, while Site B had a more concentrated distribution.

**Key Learning:**

The same average does not necessarily mean the same experience. Standard deviation and histograms help reveal patterns that averages alone cannot explain.

![Waiting Time Distribution](../Screenshots/wow_39_challenge.png)

---

## 2. Waiting Time Trends & Patterns

**Business Question:**

When do patient waiting times change, and are certain days or periods associated with longer waits?

### What I Explored

- Daily case volume.
- Average waiting-time trends by location.
- Average waiting time by day of the week.
- Site-wise comparison across weekdays using a heatmap.
- Percentage of cases completed within 15 minutes.

### Key Findings

- Compared daily case volumes with average waiting-time trends.
- Examined weekday patterns to identify variations in waiting times.
- Compared Site A and Site B across different days.
- Used the analysis to identify dates and weekdays that may deserve closer attention.

**Key Learning:**

Looking at waiting times over time helps identify patterns that a single average cannot reveal. Comparing workload and waiting-time trends also helps investigate whether higher-volume days coincide with longer waits.

![Waiting Time Trends](../Screenshots/waiting_time_trends_patterns.png)

---

## 3. Waiting Time Investigation

**Business Question:**

Where are longer waiting times concentrated, and which cases require further investigation?

### What I Explored

- Cases exceeding the 15-minute threshold.
- Percentage of cases exceeding 15 minutes by location.
- Identification of the longest waiting cases.
- Date and location slicers for focused investigation.
- A detailed table to identify individual cases with longer waits.

### Key Findings

- **43.5% of cases** exceeded the 15-minute threshold used for this analysis.
- Site B recorded **46.2%** of cases above 15 minutes.
- Site A recorded **40.9%** of cases above 15 minutes.
- The longest observed waiting time was **42.4 minutes**.

The comparison shows that Site B had a higher proportion of cases exceeding the selected threshold, despite both locations having almost identical average waiting times.

**Key Learning:**

Counts help identify how many cases need attention, while percentages help compare locations fairly. Identifying longer waits is the first step; understanding their underlying causes requires further investigation.

> **Note:** The 15-minute threshold is an assumed benchmark for this analysis, not a confirmed official clinic target.

![Waiting Time Investigation](../Screenshots/waiting_time_investigation.png)

---

#  Key Skills Developed

### Data Preparation & Modeling
- Power Query
- Data Cleaning
- Data Transformation
- Disconnected Helper Tables

### DAX & Calculations
- CALCULATE
- COUNTROWS
- AVERAGE
- STDEV.P
- FILTER
- ALL
- ALLEXCEPT
- SELECTEDVALUE
- MOD
- DIVIDE

### Data Visualization
- Dynamic Histograms
- Small Multiples
- Line Charts
- Column Charts
- Matrix Visuals
- KPI Cards
- Conditional Formatting
- Interactive Slicers

### Analytical Skills
- Distribution Analysis
- Statistical Interpretation
- Time-Based Analysis
- Threshold Analysis
- Location Comparison
- Business Insight Generation

---

#  Key Takeaways

This project taught me that building a dashboard is not just about selecting the right visual or writing DAX formulas.

It is about understanding the business problem and choosing the right analytical approach.

My biggest learnings:

- Two locations can have the same average but completely different waiting-time distributions.
- Standard deviation helps explain how consistently a process performs.
- Histograms reveal where observations are concentrated.
- Dynamic grouping provides flexibility to explore data at different levels of detail.
- Time-based analysis helps identify when patterns occur.
- Threshold analysis helps identify cases that deserve further attention.
- Business insights should be supported by data rather than assumptions.

### My Biggest Takeaway

**The average gives us a number. Standard deviation tells us how much it varies. The histogram tells us the story behind those numbers.**

And most importantly:

**Business Question → Understand Data → Analytical Approach → DAX & Visualization → Validate → Business Insights**

#  Reference & Acknowledgement

**Workout Wednesday 2026 – Week 39**

The original challenge encouraged me to explore dynamic histograms and adjustable grouping intervals in Power BI.

I extended that learning into a broader three-page analytical project to explore patient waiting-time distribution, trends, and investigation opportunities.



**LinkedIn:** [Jayalalitha T](https://www.linkedin.com/in/jayalalitha-t/)

*Continuously learning, building, and exploring the power of data analytics.*

# IBM Employee Attrition Analysis
### A Data-Driven Retention Strategy | USC Marshall DSO 550

![Python](https://img.shields.io/badge/Python-3.x-blue) 
![Power BI](https://img.shields.io/badge/PowerBI-Dashboard-yellow)
![Status](https://img.shields.io/badge/Status-Completed-green)

---

## Business Problem

IBM's voluntary attrition rate stands at **16.12%** — well above healthy benchmarks — 
with 237 out of 1,470 employees leaving annually. The resulting replacement cost is 
**$9.25M per year** (based on SHRM's 50% of annual salary benchmark).

> **Core question:** Which factors most strongly predict attrition, and where should 
IBM intervene first to maximize ROI?

---

## Key Findings

| Factor | Impact |
|---|---|
| Overtime (Yes vs No) | 30.5% vs 10.4% attrition — **20pp gap** |
| Frequent business travel | **6.06x** higher attrition odds (logistic regression) |
| Low job involvement (Level 1) | **33.73%** attrition vs 9.03% at Level 4 |
| Early-career + no stock options | Highest-risk segment: ~38% attrition |
| Sales Representatives | **39.76%** attrition — nearly 4 in 10 leave |

**Highest-risk persona:** Employees under 30, Job Level 1, working overtime → 
**53.19% attrition rate** (3.54x above baseline)

---

## ROI Analysis

| Scenario | Attrition Reduction | Investment | Net Savings | ROI |
|---|---|---|---|---|
| A (targeted) | 15% | $0.1M | $1.3M | **1,300%** |
| B (broad) | 40% | $0.5M | $3.2M | **640%** |

Both scenarios strongly outperform inaction. Scenario A maximizes efficiency; 
Scenario B captures maximum dollar savings.

---

## Methods & Tools

**Exploratory Analysis & Visualization**
- Power BI dashboard with custom DAX measures (Income Band, Promotion Stage, 
  Risk Tier, Training Impact)
- Attrition segmentation across 15+ variables

**Statistical Modeling (Python)**
- `Logistic_Regression.ipynb` — Odds ratio analysis identifying key attrition drivers
- `Decision_Tree.ipynb` — Persona segmentation (5 high-risk clusters identified)
- `Regressions_Visuals.ipynb` — Supporting regression visualizations

**Business Case**
- ROI modeling based on SHRM replacement cost benchmarks
- Two-scenario financial projection with sensitivity analysis

---

## Strategic Recommendations

1. **Reduce structural overtime** — especially for employees under 30; set OT KPIs 
   per team
2. **Mitigate high-travel risk** — rotate travel burden, add recovery time, 
   compensate fairly
3. **Standardize promotion timelines** — normal 4–5 year cycle reduces attrition; 
   delays and early promotions both increase risk

---

## Project Structure

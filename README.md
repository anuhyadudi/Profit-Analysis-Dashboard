
# 📊 Superstore Profit Analysis Dashboard

> An interactive Tableau dashboard identifying profit 
leaks and growth opportunities across regions, 
categories, and customer segments.

---

## 📌 Problem Statement
Senior leadership wants to grow profit next year 
but lacks clarity on where to focus sales resources.

> "We currently lack visibility into which products, 
regions, and customer segments are driving or eroding 
profit — limiting our ability to allocate resources 
effectively."

---

## 📁 Dataset
- **Source:** Sample Superstore (public dataset)
- **Size:** 10,000+ orders
- **Period:** 2023 – 2026
- **Dimensions:** 4 regions, 3 segments, 
  3 categories, 17 subcategories
- **Geography:** United States + Canada

---

## 🔍 Analytical Approach

### Questions Asked Before Touching Data
1. What does "grow profit" mean — margin or total?
2. Which time period to focus on?
3. Who is the audience?
4. What decision will this analysis inform?

## 💡 Key Findings

### Finding 1 — Central Region Underperforming
| Region | Profit | Avg Discount | Margin |
|--------|--------|--------------|--------|
| West   | $110K  | 11%          | 14.9%  |
| East   | $94K   | 14%          | 13.7%  |
| South  | $46K   | 15%          | 11.9%  |
| Central| $39K   | 24%          | 7.9%   |

Central discounts at **2x the rate of West** 
but generates **less than half the profit margin.**

### Finding 2 — Furniture Losing Money in Central
| Category        | Avg Discount | Profit Margin |
|----------------|--------------|---------------|
| Technology      | 13%          | +20%          |
| Office Supplies | 25%          | +5.5%         |
| Furniture       | 30%          | **-2%**       |

Every furniture sale in Central is losing money.

### Finding 3 — Home Office Most Efficient Segment
| Segment     | Profit | Margin |
|-------------|--------|--------|
| Consumer    | $140K  | 12%    |
| Corporate   | $95K   | 13%    |
| Home Office | $60K   | **14%**|

Lowest volume but highest margin — 
an underleveraged growth opportunity.

### Finding 4 — Profit Growing 16% YoY
- Consistent Q4 peak every year
- Q1 dips are seasonal — not a crisis
- Overall upward trajectory confirmed by trend line

---

## ✅ Recommendations

1. **Reduce Central furniture discounts** from 30% 
   to 15-20% — benchmarked against Technology 
   discount strategy
2. **Investigate Texas** — $170K sales but 
   -$25K profit — likely same discounting issue
3. **Grow Home Office segment** — highest margin 
   efficiency, currently underleveraged
4. **Protect West and California** — highest 
   profit and margin, don't introduce heavy discounts

---

## 🛠 Dashboard Features
- ✅ Year filter (2023–2026) with YoY comparison
- ✅ Dual axis profit map by state
- ✅ Interactive filter actions — click region 
     to drill down across all charts
- ✅ Lollipop charts showing Furniture negative margin
- ✅ Scatter plot isolating Central as discount outlier
- ✅ Treemap showing subcategory profit/loss
- ✅ Dynamic trend line with seasonality analysis

---

## 🧰 Tools Used
- **Tableau Desktop** — dashboard and visualizations
- **Calculated Fields** — YoY metrics, 
  profit margin, dynamic labels
- **Parameters** — year selection
- **Filter Actions** — cross-chart interactivity

---

## 📸 Dashboard Preview
![Dashboard Screenshot](screenshot.png)

---

## 👩‍💻 Author
**Anuhya Dudi**  
MS Engineering Management (Data Analytics) — CSUN  
[LinkedIn](your linkedin) | 
[Portfolio](your portfolio) | 
[Tableau Public](your tableau)

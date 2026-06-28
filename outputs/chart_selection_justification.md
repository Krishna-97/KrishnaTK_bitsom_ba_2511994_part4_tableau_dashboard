# Chart Selection Justification

## 1. Sales Trend

**Business Question**

How are sales changing over time?

**Chart Used**

Line Chart

**Reason**

Line charts effectively display trends and seasonality across time.

**Fields**

* Columns: Order Date
* Rows: Sales
* Color: Region

**Design Principle**

Chronological ordering.

**Mistake Avoided**

Avoided using bar charts for continuous time-series analysis.

---

## 2. Regional Performance

**Business Question**

Which regions contribute the highest sales and profit?

**Chart Used**

Horizontal Bar Chart

**Reason**

Bar charts enable accurate comparison across regions.

**Fields**

* Region
* Sales
* Profit

**Design Principle**

Descending sort improves readability.

**Mistake Avoided**

Avoided pie charts that make comparisons difficult.

---

## 3. Category Profitability

**Business Question**

Which categories generate profit or losses?

**Chart Used**

Horizontal Bar Chart

**Reason**

Positive and negative values are clearly visible.

**Fields**

* Category
* Sub-Category
* Profit

**Design Principle**

Color distinguishes profitability.

**Mistake Avoided**

Avoided stacked bars that hide negative values.

---

## 4. Discount vs Profit

**Business Question**

How do discounts affect profitability?

**Chart Used**

Scatter Plot

**Reason**

Scatter plots effectively show relationships between two numerical variables.

**Fields**

* Discount
* Profit
* Sales (Size)

**Design Principle**

Point size represents sales volume.

**Mistake Avoided**

Avoided line charts that imply a sequential relationship.

---

## 5. Shipping Performance

**Business Question**

Which shipping modes experience delivery delays?

**Chart Used**

Bar Chart

**Reason**

Easy comparison of average shipping delays.

**Fields**

* Ship Mode
* Shipping Delay

**Design Principle**

Simple comparison across categories.

**Mistake Avoided**

Avoided unnecessary heat maps.

---

## 6. Customer Segment

**Business Question**

Which customer segments contribute most to revenue?

**Chart Used**

Bar Chart

**Reason**

Supports direct comparison across discrete categories.

**Fields**

* Segment
* Sales

**Design Principle**

Consistent color and sorting.

**Mistake Avoided**

Avoided pie charts with similar-sized segments.

---

## 7. Return Analysis

**Business Question**

Which categories experience higher product returns?

**Chart Used**

Bar Chart

**Reason**

Clearly compares return rates.

**Fields**

* Category
* Return Rate

**Design Principle**

Consistent axis scaling.

**Mistake Avoided**

Avoided tables that reduce visual impact.

---

# Overall Dashboard Design Principles

* Consistent color palette
* Minimal visual clutter
* Executive-friendly layout
* Interactive filtering
* Clear KPI hierarchy
* Readable labels
* Consistent formatting
* Meaningful color encoding
* No misleading scales
* Appropriate chart selection for each business question

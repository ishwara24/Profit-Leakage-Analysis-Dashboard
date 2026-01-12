# Core DAX Measures — Profit Leakage Analysis

## Purpose
The DAX measures in this dashboard are designed to move beyond revenue reporting and focus on **true profitability and margin health**.

Each measure answers a specific business question.

---

## 🔹 Total Sales
**Business Question:**  
How much revenue is being generated overall?

**Logic:**  
Sum of sales value across all transactions.

**Why it matters:**  
This provides scale context but is not sufficient on its own to assess performance.

---

## 🔹 Profit After Discount
**Business Question:**  
How much profit remains after all discounts are applied?

**Logic:**  
Sales minus cost after accounting for discount impact.

**Why it matters:**  
This reflects real, realizable profit — not theoretical margins.

---

## 🔹 Profit Margin (%)
**Business Question:**  
How efficient is the business at converting revenue into profit?

**Logic:**  
Profit After Discount ÷ Total Sales


**Why it matters:**  
Margin trends reveal hidden inefficiencies even when revenue is growing.

---

## 🔹 Average Profit Margin
**Business Question:**  
Are many individual transactions unprofitable?

**Logic:**  
Average of transaction-level profit margins.

**Why it matters:**  
This measure exposes loss-making orders that aggregate margins can hide.

---

## 🔹 Loss-Making Transaction %
**Business Question:**  
What proportion of transactions generate negative profit?

**Logic:**  
Count of transactions with negative profit ÷ total transactions.

**Why it matters:**  
A high value indicates structural pricing or discounting issues.

---

## Analyst Note
These measures are intentionally designed to:
- Prioritize margin health over revenue
- Reveal hidden loss drivers
- Support pricing and discount strategy decisions

# adventure_works_sales_performance_analysis
An end-to-end Power BI data analytics pipeline analyzing $307.1M in cumulative global sales. Features interactive time-series tracking, data integrity auditing for historical truncation, and an operational risk assessment of product-wise portfolio concentration.

---

## 📊 Executive Summary & Data Integrity Audit
Before diving into core metrics, a critical data integrity finding must be established. The historical timeline in this dataset contains severe truncation anomalies:
* **Fiscal Year 2005** exclusively captures the final 6 months of data.
* **Fiscal Year 2008** abruptly cuts off after July.

Because evaluating these specific years based on cumulative totals would severely mislead strategic decision-making, this analysis relies strictly on normalized **Monthly Averages** to track true year-over-year operational run-rates.

---

## 📈 Macro Business Performance & Run-Rates
Across its entire historical lifespan, the business generated **$307.1M in Cumulative Revenue** against **$180.8M in Cost of Goods Sold (COGS)**. This yields a massive lifestyle corporate **Net Profit of $126.3M** sustained at a rock-solid **41.1% Profit Margin**. 

### Reporting Slice Baseline:
* **Order Volume:** 58.3K total historical orders.
* **Average Order Value (AOV):** Stable at $9.1K per transaction.
* **Temporal Distribution:** Weekday operations drive core baseline volume, while weekend sales capture a consistent **31.6% share** of total profitability.

---

## ⚠️ Portfolio Inventory & Client Concentration Risk
A deeper structural analysis reveals severe operational vulnerabilities contrasted against high customer diversification.

* **Product Inventory Stagnation:** Out of 606 total SKUs cataloged in the system, **448 unique products have zero lifetime sales**. This indicates that **74% of our entire product registry is completely dead stock**, locking up potential capital in unmoving lines.
* **Extreme Revenue Dependency:** Profitability is dangerously top-heavy. Just 5 specific configurations of the **Mountain-200 bike series** generate **$31.27M**, single-handedly driving **24.8% of entire corporate profits**. A supply chain halt or manufacturing block to this single line represents a catastrophic risk.
* **Margin Density vs. Unit Scaling:** The **"Very Costly" tier drives 85.81% of net profits**. While the **"Cheap" category yields the highest individual margins at 55.2%**, its low unit-price architecture cannot scale aggressively enough to compete with the sheer dollar density of the luxury lines.
* **Customer Landscape Immunity:** In sharp contrast to product risk, our customer base is highly secure. We possess **18K active clients** with a perfect demographic balance between male and female purchasers. Concentration risk is effectively zero—the top 5 clients combined generate **barely 0.2% of total profit**, fully insulating our bottom line against client churn.

---

## 🌍 Regional Trajectory & The July 2008 Cliff
Geographically, the corporate engine is anchored by the **United States and Australia**, with each market clearing **over $38M in lifetime net profit**, while all remaining territories plateau below the $15M threshold.

### Chronological Chronology:
* **2005 Baseline:** Operations opened with localized run-rates. The US and Australia quickly outpaced other regions, clearing $1M individual monthly profit thresholds to set our initial baseline Average Monthly Profit (AMP) at **$2.23M**.
* **2006 Stagnation:** Global momentum flattened. Only Canada and France sustained positive growth run-rates, while remaining core territories stagnated as mid-tier expansions failed to track.
* **2007 Scaling:** A historic performance surge. Global AMP jumped to **$3.5M**, marking an incredible **51% year-over-year expansion** as low-tier volumes scaled while luxury lines protected corporate margins.
* **2008 The Operational Collapse:** Running into 2008, optimization peaked at a spectacular global AMP run-rate of **$6.02M—a 69.88% growth explosion**. However, this tracking crashed into an operational cliff in July. Total revenue collapsed down to just **$532K** (down from $20M the previous month) as trade on our foundational "Very Costly" product lines completely locked up.

---

## 🎯 Strategic Recommendations
1. **Immediate Luxury Pipeline Diagnostic:** Launch an immediate forensic audit into the July 2008 operational gridlock to clear the bottlenecks stalling the "Very Costly" Mountain-200 lines, as this represents our primary margin engine.
2. **Aggressive SKU Remediation:** Liquidate or structurally phase out the **448 dead-stock SKUs** bloating operational overhead, reallocating capital to diversify our mid-tier product lines and lowering our structural reliance on just 5 key products.

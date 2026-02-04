This project simulates a Credit Risk and Loyalty Analysis. It takes raw customer transaction data and uses statistical procedures to "evolve" a customer's status.

What it does:

Data Synthesis: Creates a virtual dataset of customer balances and payment histories.

Heuristic Scoring: Calculates a "Risk Score" using weighted mathematical formulas (similar to a Fitness Function).

Data Segmentation: Automatically categorizes customers into tiers (Gold, Silver, High Risk) based on statistical thresholds.

Reporting: Generates a professional summary table of the "surviving" profitable customers.

What it uses:

DATA Steps: For data transformation and logic.

PROC FORMAT: To create custom mapping for data values.

PROC MEANS/SUMMARY: To calculate descriptive statistics.

Weighted Logic: To rank data based on importance (Heuristics).

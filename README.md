# MarketScope: Product Pricing, Rating & Quality Analysis

An end-to-end data analysis, machine learning, and Tableau visualization project analyzing 1,000 products across price and rating segments[cite: 2, 3].

## Key Findings
* **Market Distribution:** The catalog of 1,000 products has an average price of **$35.07** and an average rating of **2.92 / 5**[cite: 2]. Products are split evenly between Mid-Range (401) and Premium (403), with 196 in the Budget tier[cite: 2].
* **Price vs. Rating:** Correlation between price and customer rating is near zero ($r = 0.03$), showing that higher prices do not predict higher customer satisfaction[cite: 2, 3].
* **Data Limitations:** Original discount, stock availability counts, and brand metadata were absent from the source catalog and documented as exclusions rather than imputed[cite: 2, 4].

## Dashboards
### Customer Rating & Product Quality
![Rating Analysis](dashboards/images/dashboard3_rating_analysis.png)[cite: 3]

### Discount & Product Availability
![Discount and Availability](dashboards/images/dashboard4_discount_availability.png)[cite: 4]

### Product Comparison
![Product Comparison](dashboards/images/dashboard5_product_comparison.png)[cite: 5]

## Repository Structure
* `data/` — Cleaned datasets, data quality audit, and model comparison metrics.
* `models/` — Serialized `scikit-learn` Linear Regression model (`Price` feature).
* `dashboards/` — Tableau workbook and exported dashboard views[cite: 2, 3, 4, 5].
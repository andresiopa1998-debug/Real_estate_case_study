# Real Estate Case Study: Affordability & Incentive Analysis
**Analyst:** Andre Amorim Siopa  
**Tools:** Google Sheets, Python (Pandas), Tableau, AI Assistance

## Summary
This project analyzes real estate data sourced from Kaggle to identify high-impact markets for a "Rent-to-Own" program. The analysis compares luxury and entry-level markets to see where corporate down-payment incentives provide the most value to tenants.

## My Process
1. **Source:** Downloaded raw real estate data from Kaggle.
2. **Cleaning (Manual):** - Removed rows missing 'Locality' data.
    - Used locality-based medians to fill missing 'Carpet Area' values.
    - Resolved '(? )' property labels through manual inspection and categorization.
    - Validated pricing by aligning 'Estimated Value' with 'Sale Price'.
3. **Analysis (Python & AI):** Exported cleaned data to Python. Leveraged AI to assist with coding syntax for calculating `Price_Per_SqFt`, `Price_Per_Room`, and `5% Down Payment Credit`.
4. **Visualization:** Created comparative charts to demonstrate market disparities.

## Key Finding
The study found a 23x price-per-square-foot gap between luxury and affordable markets. I recommended focusing program resources on **Waterbury** and **Bridgeport**, where a 5% credit significantly lowers the barrier to homeownership, unlike in luxury markets where the same percentage offers minimal relative impact.
## Files
* `Real_estate_case_pyt.csv`: The cleaned and analyzed dataset.
* `analysis_notebook.py`: Python code used for calculations.
* Tableau Dashboard: https://public.tableau.com/authoring/Real_Estate_Project_17769088354790/Dashboard1#1

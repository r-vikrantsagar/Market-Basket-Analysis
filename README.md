# Market Basket Analysis

This project analyzes retail transaction data to uncover product associations and co-purchase patterns using market basket analysis techniques. The goal is to provide insights for product bundling, in-store placement, and cross-selling strategies.

## Problem Statement

Retailers often need to understand which products are purchased together to improve merchandising, increase basket size, and enhance customer experience. Market Basket Analysis helps identify these relationships through association rules and frequent itemsets.

## Approach

- **Data Cleaning**:
  - Processed `OnlineRetail.csv` by removing null entries, duplicates, and invalid transactions.
  - Filtered transactions to include only positive quantities and valid customer IDs.

- **Exploratory Data Analysis**:
  - Analyzed top-selling products, countries, and customer segments.
  - Visualized frequency distributions and transaction volumes.

- **Modeling**:
  - Applied the Apriori algorithm to extract frequent itemsets.
  - Generated association rules with metrics such as support, confidence, and lift.
  - Interpreted rules to identify strong product affinities.

## Solution

Generated a list of high-confidence product association rules. These insights can be used to:
- Design promotional bundles
- Optimize shelf placement
- Improve cross-selling in online recommendations

## Technologies Used

- Python
- Pandas, NumPy
- mlxtend (Apriori, association rules)
- Matplotlib, Seaborn
- Jupyter Notebooks

## Learnings

- Lift metric is crucial for identifying meaningful product associations.
- Data quality and transaction filtering significantly affect results.
- Visualizations enhance interpretation of complex item relationships.

## Future Work

- Integrate customer segmentation for personalized recommendations.
- Visualize itemsets using network graphs.
- Deploy results into retail CRM or POS systems for real-time actions.

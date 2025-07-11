# Association Rule Mining – Mini Assignment

**Name:** Rosamistica  
**Course:** DSA 2040A  
**Semester:** Summer 2025  

## Description

This notebook simulates 10 transactions and applies the Apriori algorithm using `mlxtend` to find frequent itemsets and generate association rules. A rule is then interpreted in real-world context.
1. Transaction Simulation
Created a list of 10 fake transactions in Python, each representing a customer’s purchase.

2. One-Hot Encoding
Converted the list of transactions into a binary matrix using mlxtend.preprocessing.TransactionEncoder.

3. Apriori Algorithm
Used mlxtend.frequent_patterns.apriori to find frequent itemsets with a minimum support of 0.3 (30%).

4. Generate Association Rules
Used mlxtend.frequent_patterns.association_rules with:

Metric: confidence

Threshold: 0.7 (70%)

## Libraries Used

- `pandas`
- `mlxtend`

## How to Run

1. Open `association_mining.ipynb` in Jupyter Notebook or VS Code.
2. Run all cells to simulate data, run Apriori, and view rules.

## Sample output
<img width="404" height="150" alt="image" src="https://github.com/user-attachments/assets/ffd00162-19e2-4533-bd10-92be515c76bf" />


- **Rule:** If Milk, then Juice
- **Confidence:** 0.75  
- **Interpretation:** When customers buy Milk, they also buy Juice 75% of the time.

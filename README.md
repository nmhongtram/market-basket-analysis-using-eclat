# Market Basket Analysis Using Eclat

## Project Overview
This project is the final assignment for the Data Mining course. The objective is to apply data mining techniques, specifically **Frequent Pattern Mining** and **Association Rule Mining**, to analyze customer purchasing behavior.

## Dataset
The dataset used in this project is **Groceries_3.csv**, which contains transaction records of various products purchased by customers. Each transaction consists of a set of products bought together.

## Data Mining Techniques Used
- **Frequent Itemset Mining**
  - Apriori Algorithm
  - FP-Growth Algorithm
  - ECLAT Algorithm
- **Association Rule Mining**
  - Confidence Calculation
  - Lift Measure Evaluation
  - Strong Association Rules Selection
- **Data Preprocessing & Visualization**
  - Exploratory Data Analysis (EDA)
  - Data Cleaning & Transformation
  - Visualization of Transaction Patterns

## Results
- **Frequent Itemsets Extraction:**
  - Applied **ECLAT**, **Apriori**, and **FP-Growth** to discover frequent itemsets in the dataset.
  - Selected **minimum support threshold (min_sup = 0.11)** based on data distribution analysis.
- **Association Rule Mining:**
  - Generated **246 association rules** from the frequent itemsets.
  - Selected **11 strong rules** with **minimum confidence = 0.5** and **Lift > 1**.
- **Business Insights:**
  - Identified key product combinations frequently purchased together.
  - Proposed **cross-selling strategies**, product placements, and inventory management suggestions to optimize business decisions.

## Contributors
- Team 11

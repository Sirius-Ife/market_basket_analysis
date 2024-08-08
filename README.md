# Market Basket Analysis on Grocery Data

## Project Overview

This project involves performing Market Basket Analysis on grocery store transaction data using the Apriori Algorithm. The goal of the analysis is to identify associations between different items frequently purchased together, providing insights that can be used to optimize product placement, cross-selling strategies, and promotional activities.

## Objectives

- **Explore and Clean the Data:** Conduct exploratory data analysis (EDA) to understand the structure of the data, identify patterns, and clean the data by handling missing values.
- **Apply the Apriori Algorithm:** Use the Apriori Algorithm to discover frequent itemsets and generate association rules.
- **Interpret the Results:** Analyze the resulting association rules to provide actionable insights for the grocery store.

## Data Overview

The grocery dataset consists of transaction records where each row represents a single transaction, and each column represents a product that was purchased. The data includes a large number of transactions, with multiple products being purchased in each transaction.

### Data Preprocessing

- **Missing Values:**  
  Missing values (NAs) were identified during the exploratory data analysis. These were removed to ensure the quality and accuracy of the analysis.

- **Data Transformation:**  
  The transaction data was transformed into a format suitable for the Apriori Algorithm, where each transaction was represented as a list of items.

## Methodology

1. **Exploratory Data Analysis (EDA):**  
   - Performed EDA to understand the distribution of transactions, most frequently purchased items, and other key characteristics of the data.
   - Visualized item frequencies and identified patterns that could inform the association rule mining process.

2. **Data Cleaning:**  
   - Removed rows with missing values to ensure the integrity of the analysis.
   - Transformed the data into a transactional format required for the Apriori Algorithm.

3. **Market Basket Analysis using Apriori Algorithm:**  
   - Applied the Apriori Algorithm to identify frequent itemsets, i.e., combinations of products that are often purchased together.
   - Generated association rules from these frequent itemsets, specifying the conditions under which certain products are likely to be purchased together.

4. **Analysis and Interpretation:**  
   - Analyzed the association rules using metrics such as support, confidence, and lift.
   - Interpreted the rules to provide insights into customer purchasing behavior and to suggest potential strategies for cross-selling and product placement.

## Conclusion

This Market Basket Analysis provides valuable insights into customer purchasing patterns at the grocery store. By leveraging the results of the Apriori Algorithm, the store can make data-driven decisions to enhance product placement, design effective cross-selling strategies, and ultimately increase sales.

## Files Included

- `data/`: Contains the cleaned and preprocessed grocery transaction data.
- `Rmd/`: R Markdown files documenting the entire analysis process.
- `README.md`: This document.

## How to Run

1. Clone the repository.
2. Install the required R packages listed in the `Rmd/` files.
3. Open the R Markdown files in the `Rmd/` directory and run the analysis to reproduce the results.

## Acknowledgments

This project was conducted as part of a study in Market Basket Analysis, focusing on discovering product associations in grocery store transactions using the Apriori Algorithm.

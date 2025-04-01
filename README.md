# Association Rules Market Basket Analysis using Apriori - R project

This project explores Market Basket Analysis using the Apriori algorithm to discover associations between products in a retail dataset. By identifying frequent itemsets, the analysis aims to uncover valuable insights into customer purchasing behavior, which can be applied to improve marketing strategies or product placements.

## Project Overview
In this project, the Apriori algorithm is applied to a dataset to generate frequent itemsets and association rules. The ultimate goal is to identify combinations of items that are frequently purchased together, providing actionable insights for cross-selling, promotional activities and store layouts.

## Key Steps
1. Data Preprocessing: The dataset is cleaned and transformed into a suitable format for the Apriori algorithm. Items are encoded in a binary matrix format where each transaction is represented by the presence or absence of items.
2. Applying Apriori Algorithm: The Apriori algorithm is used to generate frequent itemsets by evaluating combinations of items that appear frequently in the dataset.
3. Generating Association Rules: The frequent itemsets are then used to generate association rules, which show relationships between items based on support, confidence, and lift metrics.
3. Evaluating Rules: Association rules are evaluated based on the following metrics:
* Support: The proportion of transactions in which the itemset appears.
* Confidence: The likelihood that an item is purchased when another item is purchased.
* Lift: The ratio of the observed support to the expected support if the items were independent.
4. Visualization: The results are visualized using plots that display the most frequent itemsets and the strength of association rules, aiding in the interpretation of the findings.

## Techniques Used
* Apriori Algorithm: A classical algorithm for mining frequent itemsets and association rules. It helps to identify combinations of items that frequently co-occur in transactions.
* Evaluation Metrics: The project evaluates association rules using support, confidence, and lift to measure the strength and relevance of the discovered relationships.
* Data Visualization: The results of the analysis are visualized to provide insights into the patterns and correlations between different items.

## Steps to Open and Run the Project
1. To get started, clone this repository to your local machine.
2. Once the project is cloned, navigate to the folder where the project is saved.
3. Open the Pizza_Hut_Menu_Clustering.Rmd file in RStudio.
4. Run the R Markdown file.

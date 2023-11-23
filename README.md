# Market-Basket-Analysis-with-Apriori-Algorithm
This repository contains a Python script for performing Market Basket Analysis using the Apriori algorithm. The analysis is applied to a grocery sales dataset to discover associations between different products.

#### Description
- Whenever you visit a retail supermarket, you will find that milk, sugar and coffee, bread and butter, pizza base and cheese, chocolate, and pringles are positioned together in the store for sales. This is what market basket analysis is all about - analyzing the association of products bought together by customers.
  Market basket analysis is a versatile used case in the retail industry that helps cross-sell products in a physical outlet and also helps e-commerce businesses recommend products to customers based on product associations. Apriori and FP growth are the most popular machine learning algorithms used for association learning to perform market basket analysis.

## Overview
Market Basket analysis can provide valuable information to increase sales by better understanding customers purchasing paterns. This project aims to :
- Preprocess and analyze sales performance.
- Perform market basket analysis to understand the overall sales performance looking customers purchase behaviour.
- Determine which products are most likely bought together.
- Identifies pattern behaviour of customers.
- Visualize analysis results for product placement and up-sell tactics.
- Conduct in-depth analysis to extract insights and correlations.
  Project Steps

## The project involves the following main steps:
* Data Collection and Preprocessing
* Market Basket Analysis
* Data Visualization
* Insight Reporting and Visualization

## Getting Started
To get started with this project, follow these steps:

Clone the repository to your local machine.
Install the required dependencies.
Follow the project steps outlined in the code to analyze your grocery dataset.
To run this project, you need the following dependencies:

## Dependencies
- Python 3.x
- Jupyter Notebook (optional but recommended for interactive analysis)
- Libraries: pandas, numpy, matplotlib, seaborn, textblob (or other NLP libraries)
- You can install the required dependencies using pip:

## Usage
Clone the repository to your local machine.
Place your grocery dataset in the specified directory.
Run the Python scripts provided in each project step.
Follow the instructions in the scripts to analyze your data.
Results and Visualizations
The project provides various visualizations and insights into market basket analysis. Check the results and visualizations section for more details.

## Code structure
#### Data Loading and Cleaning:
Load the grocery sales data and perform initial data cleaning.
Convert 'Member_number' to a string and 'Date' to datetime format.

##### Unique Transactions:
Create a 'uniqueTransaction' column to group items purchased per customer per day.

#### Cross-Tabulation (Basket Creation):
Create a cross-tabulation ('basket') to represent the frequency of items in each unique transaction.
Create a binary-encoded DataFrame ('apriori_df').

#### Apriori Algorithm and Association Rules:
Apply the Apriori algorithm to generate frequent itemsets.
Use association rules, focusing on Zhang's metric for evaluation.
Heatmap Visualization:

#### Visualize product associations using a heatmap.
Interpret the heatmap to understand frequent itemsets.

#### Positive Association Visualization:

Explore pairs with positive Zhang's metric to highlight positive associations.

#### Visualization
Utilize heatmaps for clear and intuitive visualization of product associations.
Explore positive associations to understand which products complement each other.

#### Insights
Use Zhang's metric for a comprehensive evaluation of association rules.
Interpret negative and positive values to understand anti-associations and strong positive relationships.

## Contributing
Contributions are welcomed! Feel free to open issues, make pull requests, or provide feedback to enhance this project.

Feel free to modify this template to suit your specific project details and provide additional information as needed. A well-detailed README can help others understand and contribute to your project effectively.




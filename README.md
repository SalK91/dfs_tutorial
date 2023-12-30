# Featuretools Tutorial

This repository serves as a tutorial for using Featuretools, a powerful Python library designed for automated feature engineering. The tutorial walks through the application of Featuretools on a dataset sourced from Kaggle, containing information about clients, their loans, payments, and outcomes.


## Dataset Overview

### Tables:
1. **clients**: Information about clients at a credit union.
2. **loans**: Previous loans taken out by the clients.
3. **payments**: Payments made/missed on the previous loans.

### Data Source:
[Automated Feature Engineering Tutorial on Kaggle](https://www.kaggle.com/code/willkoehrsen/automated-feature-engineering-tutorial)



## Data Representation with EntitySets
Featuretools works with EntitySets, a collection of dataframes and their relationships. This section demonstrates the creation of an EntitySet and the addition of dataframes representing clients, loans, payments due, and outcomes.

## Adding Relationships
Featuretools leverages relationships between dataframes. The tutorial illustrates how to define relationships between clients and loans, loans and payments, and payments_due and outcomes.

## Feature Engineering with Cutoff Time
One essential aspect of feature engineering in Featuretools is incorporating a cutoff time to prevent leakage. This is crucial to ensure that features are created based on information available up to a certain point in time. The tutorial demonstrates the use of cutoff times in the following steps:

Define cutoff times based on the desired time point.
Apply cutoff times during deep feature synthesis to avoid data leakage.

## Feature Engineering
Featuretools simplifies feature engineering through feature primitives, which are building blocks for creating new features. The tutorial covers both aggregation and transformation primitives, demonstrating their application on the dataset.

## Visualizing Features
The tutorial includes visualizations of specific features, providing insights into their composition and relationships.

## Conclusion
This Featuretools tutorial is a hands-on guide to using the library for feature engineering. By following the provided code snippets, you'll gain a practical understanding of how to apply Featuretools on a relational dataset to extract meaningful features.

Feel free to explore and adapt the tutorial based on your specific use case and dataset. Enjoy feature engineering with Featuretools!
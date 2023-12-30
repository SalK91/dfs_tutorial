# Feature Engineering Tutorial with Featuretools

This repository serves as a tutorial for using Featuretools, a powerful Python library designed for automated feature engineering. The tutorial walks through the application of Featuretools on a dataset sourced from Kaggle, containing information about clients, their loans, payments, and outcomes.


## Dataset Overview

### Tables:
1. **clients**: Information about clients at a credit union.
2. **loans**: Previous loans taken out by the clients.
3. **payments**: Payments made/missed on the previous loans.

[Data Source] (https://www.kaggle.com/code/willkoehrsen/automated-feature-engineering-tutorial)



# Code Overview
The tutorial covers the following key aspects:

***Loading Data:** Loading and preprocessing the dataset, consisting of clients, loans, payments, and outcomes.

***Data Visualization:** Visualizing a subset of the data to gain insights into clients, loans, payments due, and outcomes.

***EntitySets:** Introducing EntitySets, a collection of dataframes and relationships between them, to prepare raw, structured datasets for feature engineering.

***Adding Relationships:** Establishing relationships between dataframes (clients, loans, payments_due, outcome) to facilitate feature engineering.

***Feature Primitives:** Exploring feature primitives, the building blocks of Featuretools, categorized as Aggregation and Transformation. The tutorial lists available primitives and their importance in creating new features.

***Cutoff Time:** Highlighting the significance of cutoff time in feature engineering to prevent leakage, demonstrated through the extraction and manipulation of cutoff times.

[Handling Time in Featuretools] (https://docs.featuretools.com/en/v0.16.0/automated_feature_engineering/handling_time.html#:~:text=The%20cutoff_time%20is%20the%20last,calculate_feature_matrix%20.)

***Deep Feature Synthesis:** Performing deep feature synthesis using Featuretools to generate features based on specified aggregation and transformation primitives.

***Visualization:** Visualizing a specific feature to better understand its structure.
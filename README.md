# Titanic Survival Exploration
Exploratory Data Analysis (EDA) - Titanic Survival Subset
This repository contains an initial Exploratory Data Analysis (EDA) performed on a subset of the Titanic dataset, focusing specifically on the PassengerId and Survived columns.

Project Goal

To conduct a preliminary EDA to understand:
The basic structure of the dataset,
Data completeness,
The initial distribution of the target variable (Survived).
This serves as a foundational step before incorporating more features for deeper analysis.

Key Findings
1. Dataset Structure
	 The df DataFrame contains 418 entries and 2 columns:
	 PassengerId (int64), 
	 Survived (int64)

2. Data Completeness
	 No missing values found in either column.
	 Indicates a clean starting dataset for the available features.

3. Survival Distribution
	 Not Survived (0): 266 passengers (~63.64%), 
	 Survived (1): 152 passengers (~36.36%)

This reveals a class imbalance, with a larger proportion of passengers not surviving in this subset.

Conclusion

This preliminary Exploratory Data Analysis on the Titanic survival subset provides a basic understanding of the dataset’s structure and the distribution of the target variable. With only PassengerId and Survived available, the analysis reveals a noticeable class imbalance, with a majority of passengers not surviving. While the dataset is clean and free of missing values, the limited number of features restricts the depth of insights that can be drawn.
To gain meaningful patterns, build predictive models, or perform a comprehensive analysis, it is essential to incorporate additional features such as Age, Sex, Pclass, Fare, and family-related attributes. This initial exploration serves as an important starting point, highlighting the need for richer data to advance further in the analytical process.

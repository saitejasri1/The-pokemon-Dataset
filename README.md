Pokémon Dataset Analysis 📊

Overview 🌟
This project dives into the Pokémon Dataset, capturing the essence of Pokémon through Generation 6, to predict which ones can undergo Mega Evolution. Leveraging logistic regression and enriched by SMOTE for class balancing, we tackle the dataset's class imbalance challenge head-on.

Dataset Description 📁
The dataset is a treasure trove of information for 721 Pokémon, including:

Basic Stats: HP, Attack, Defense, Special Attack, Special Defense, and Speed 📈.
Categorical Attributes: Type_1 and Type_2, among others 🏷️.
Unique Identifiers: Pokémon ID, name, legendary status, and more 🔑.
Analysis Approach 🔍
Feature Selection
Selected features for our predictive model are:

Numerical Features: 'Total', 'HP', 'Attack', 'Defense', 'Sp_Atk', 'Sp_Def', 'Speed', 'Generation', and 'Weight_kg', with outlier management 📏.
Categorical Features: 'Type_1' and 'Type_2', transformed via one-hot encoding 🔥.
Class Imbalance Treatment
The significant class imbalance, evident from a high true negative rate, was addressed using:

SMOTE: Enhancing the minority class representation for balanced training 🔄.
Further Improvements Considered
With more time, the following enhancements were envisaged:

Exploratory Data Analysis (EDA): Deep diving into each feature's influence on Mega Evolution 🕵️‍♂️.
Feature Transformation: Considering logarithmic, polynomial, etc., transformations to normalize distributions 🔧.
Statistical Testing: Utilizing t-tests and ANOVA for informed feature selection 📊.
Conclusion and Insights 📌
Our journey through logistic regression, feature selection, and class imbalance treatment reveals the critical role of EDA and feature engineering. Despite class imbalance challenges, our approach offered valuable insights, with room for further enhancements through identified strategies.

This project embodies the iterative essence of data science, highlighting the predictive modeling challenges and opportunities within the fascinating world of Pokémon.

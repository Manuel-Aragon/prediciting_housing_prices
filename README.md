# prediciting_housing_prices

Problem statement![image](https://github.com/Manuel-Aragon/prediciting_housing_prices/assets/73243037/aff34074-7459-4517-a391-91a471d48da6)

Accurately predicting house prices can be challenging due to the complex interplay of these factors. However, a reliable predictive model can provide valuable insights for stakeholders in the housing market, such as potential buyers and sellers, real estate agents, and investors. By utilizing machine learning techniques, it is possible to analyze large datasets containing historical house sales and identify patterns that can help predict future prices.
![image](https://github.com/Manuel-Aragon/prediciting_housing_prices/assets/73243037/67c6a3cd-a005-4e44-a119-160e667e18b9)


Datasets![image](https://github.com/Manuel-Aragon/prediciting_housing_prices/assets/73243037/7eee1516-19bc-4c05-aa91-0e73a657ef03)
The project will use the "House Prices - Advanced Regression Techniques" dataset available on Kaggle, which contains 79 explanatory variables describing various aspects of residential homes in Ames, Iowa. 
The dataset includes information on the size, location, age, quality, and condition of the houses, as well as features related to interior and exterior design, utilities, and neighborhood amenities.
![image](https://github.com/Manuel-Aragon/prediciting_housing_prices/assets/73243037/16cb0aa5-5245-4785-8e91-45e81d4b2885)

Machine learning strategy![image](https://github.com/Manuel-Aragon/prediciting_housing_prices/assets/73243037/f04f68c6-b113-420f-9a84-cf53b13f32b8)
Supervised Learning
labeled dataset 
features and target variable (house prices) available.
Feature Engineering and Selection:
Apply feature selection techniques to identify the most relevant features, such as correlation analysis, mutual information, or recursive feature elimination.
Model Selection: Experiment with Linear Regression, Decision Trees, and Random Forest algorithms and compare their performance.
![image](https://github.com/Manuel-Aragon/prediciting_housing_prices/assets/73243037/d460b4cd-be87-4f32-baa2-928fa9b5a325)
![image](https://github.com/Manuel-Aragon/prediciting_housing_prices/assets/73243037/67c4d656-c17b-43fe-9695-22441e3fb040)

![image](https://github.com/Manuel-Aragon/prediciting_housing_prices/assets/73243037/b5572afe-ae79-4e2f-9621-2285fa2d3427)
![image](https://github.com/Manuel-Aragon/prediciting_housing_prices/assets/73243037/7d2ab4d9-654c-4dca-9cdf-baa927e452e0)

Feature correlation![image](https://github.com/Manuel-Aragon/prediciting_housing_prices/assets/73243037/3a64e845-6236-4011-8753-1b0f439eae96)
Top 10 most correlated features with SalePrice: Index(['SalePrice', 'OverallQual', 'GrLivArea', 'GarageCars', 'GarageArea', 'TotalBsmtSF', '1stFlrSF', 'FullBath', 'BsmtQual_Ex', 'TotRmsAbvGrd', 'YearBuilt'], dtype='object') Top 5 least correlated features with SalePrice: Index(['ExterQual_TA', 'KitchenQual_TA', 'BsmtQual_TA', 'GarageFinish_Unf', 'MasVnrType_None'], dtype='object')
![image](https://github.com/Manuel-Aragon/prediciting_housing_prices/assets/73243037/0a076705-f996-4c57-8348-8e3de43e697a)

MODEL EVALUATION![image](https://github.com/Manuel-Aragon/prediciting_housing_prices/assets/73243037/773705bb-fab7-46ca-bc15-f71b25f9220c)
![Uploading image.png…]()

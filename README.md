Estimating Home Values with Machine Learning
Author
Manuel Aragon
Abstract
Accurately predicting house prices can be challenging due to the complex interplay of various factors. This project aims to develop a reliable machine learning model that provides valuable insights for stakeholders in the housing market, such as potential buyers, sellers, real estate agents, and investors. By utilizing machine learning techniques, we analyze large datasets containing historical house sales to identify patterns that can help predict future prices.

Housing Prices Prediction

Datasets
The project uses the "House Prices - Advanced Regression Techniques" dataset available on Kaggle. This dataset contains 79 explanatory variables describing various aspects of residential homes in Ames, Iowa. It includes information on the size, location, age, quality, and condition of the houses, as well as features related to interior and exterior design, utilities, and neighborhood amenities.
![e6e7b872-4ba9-4a8b-aeea-a5cb4a75a2e3](https://github.com/Manuel-Aragon/prediciting_housing_prices/assets/73243037/e005bec3-44c1-4352-9346-4460f881117b)

Housing Dataset

Machine Learning Strategy
Supervised Learning
A labeled dataset with features and the target variable (house prices) is available.
Feature Engineering and Selection
Apply feature selection techniques, such as correlation analysis, mutual information, or recursive feature elimination, to identify the most relevant features.
Model Selection
Experiment with Linear Regression, Decision Trees, and Random Forest algorithms and compare their performance.

Feature Correlation
![image](https://github.com/Manuel-Aragon/prediciting_housing_prices/assets/73243037/d460b4cd-be87-4f32-baa2-928fa9b5a325)

Top 10 most correlated features with SalePrice: ['OverallQual', 'GrLivArea', 'GarageCars', 'GarageArea', 'TotalBsmtSF', '1stFlrSF', 'FullBath', 'BsmtQual_Ex', 'TotRmsAbvGrd', 'YearBuilt']
Top 5 least correlated features with SalePrice: ['ExterQual_TA', 'KitchenQual_TA', 'BsmtQual_TA', 'GarageFinish_Unf', 'MasVnrType_None']


MODEL EVALUATION


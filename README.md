#Estimating Home Values with Machine Learning

#Abstract
Accurately predicting house prices can be challenging due to the complex interplay of various factors. This project aims to develop a reliable machine learning model that provides valuable insights for stakeholders in the housing market, such as potential buyers, sellers, real estate agents, and investors. By utilizing machine learning techniques, we analyze large datasets containing historical house sales to identify patterns that can help predict future prices.

Housing Prices Prediction
Housing Dataset
Datasets
The project uses the "House Prices - Advanced Regression Techniques" dataset available on Kaggle. This dataset contains 79 explanatory variables describing various aspects of residential homes in Ames, Iowa. It includes information on the size, location, age, quality, and condition of the houses, as well as features related to interior and exterior design, utilities, and neighborhood amenities.
![e6e7b872-4ba9-4a8b-aeea-a5cb4a75a2e3](https://github.com/Manuel-Aragon/prediciting_housing_prices/assets/73243037/e005bec3-44c1-4352-9346-4460f881117b)

![bfafade9-6b29-43ec-85f7-1e4d99b12aca](https://github.com/Manuel-Aragon/prediciting_housing_prices/assets/73243037/02a9029d-df6c-46c4-b68a-a3577abaed2e)

![image](https://github.com/Manuel-Aragon/prediciting_housing_prices/assets/73243037/b9360c6a-1f5a-4119-a7ab-6700b319baeb)

![image](https://github.com/Manuel-Aragon/prediciting_housing_prices/assets/73243037/628875dc-4607-4ae8-8c86-0357baec6b79)

![image](https://github.com/Manuel-Aragon/prediciting_housing_prices/assets/73243037/6e77b7d5-d692-4f3b-a2bd-1319fda85578)

![image](https://github.com/Manuel-Aragon/prediciting_housing_prices/assets/73243037/36f83af7-67e6-410f-9f7e-8998c56e9006)

![image](https://github.com/Manuel-Aragon/prediciting_housing_prices/assets/73243037/885a08b3-0057-45be-b5f5-b9a680f562d0)

![image](https://github.com/Manuel-Aragon/prediciting_housing_prices/assets/73243037/803289f8-00a8-4880-a905-e3070eecefb0)

![image](https://github.com/Manuel-Aragon/prediciting_housing_prices/assets/73243037/831f6200-83b9-45fe-b6b5-4895d0c0d262)

![image](https://github.com/Manuel-Aragon/prediciting_housing_prices/assets/73243037/cd50c199-dec5-4d85-ac1d-7ef334ad7a25)


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
![4585ea1b-bd46-4aaa-9311-cc88743e5a4e](https://github.com/Manuel-Aragon/prediciting_housing_prices/assets/73243037/89b4e4c4-cdee-4f0c-a63c-d84b7eee03c4)






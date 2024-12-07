# Houses-Project
## Basic Information
* Person or organization developing model: Robert Bhero, robert.bhero@gwu.edu , Shepherd Chikwawawa, shepherd.chikwawawa@gwu.edu, Pamela Chirwa, pchirwa@gwu.edu
* Model date: November 2024
* Model version: 1.0
* License: MIT
* Model implementation c
## Intended Use
* Primary intended uses:
* Primary intended users:
* Out of scope use cases: Any use beyond an educational example is out of scope
# Training Data
* Data dictionary

* Source of training data: Kaggle Houses Prices, email pchirwa@gwu.edu, shepherd.chikwawawa@gwu.edu and robert.bhero@gwu.edu for more information
* Number of rows in test data: 1,460
* State any differences in columns between training and test data: SalesPrice in test data is empty and is the one being predicted
# Model Details
* Columns used as inputs in the final model: ‘MSSubClass’,  ,MSZoning’ , ‘LotFrontage’, ‘ LotArea’ , ‘Street’,  ‘ Alley’,   ‘LotShape’ ,  ‘ LandContour’ , ‘Utilities’ , ‘LotConfig’, ‘LandSlope’,  ‘Neighborhood’,  ‘Condition1’ ,  ‘Condition2’, ‘BldgType’, ‘HouseStyle’, ‘OverallQual’ , ‘ OverallCond’ , ‘ YearBuilt’,  ‘ YearRemodAdd’, ‘RoofStyle’,  ‘RoofMatl’ ,  ‘Exterior1st’,  ‘Exterior2nd’ , ‘ MasVnrType’ , ‘MasVnrArea’ , ‘ExterQual’, ‘ExterCond’ ,  ‘ Foundation’ , ‘BsmtQual’,  ‘ BsmtCond ‘,  ‘BsmtExposure’ ,  ‘ BsmtFinType1’,  ‘BsmtFinSF1’ ,  ‘BsmtFinType2’ , ‘BsmtFinSF2’, ‘  BsmtUnfSF’,  ‘TotalBsmtSF’ ,  ‘Heating’,  ‘HeatingQC’ ,  ‘ CentralAir’ , ‘Electrical’,  ‘1stFlrSF’,  ‘2ndFlrSF’,  ‘LowQualFinSF’ ,  ‘GrLivArea’ ,  ‘BsmtFullBath’ , ‘ BsmtHalfBath’,  ‘FullBath’ , ‘HalfBath’,  ‘BedroomAbvGr’ ,  ‘ KitchenAbvGr’,  ‘ KitchenQual’ ,  ‘TotRmsAbvGrd’, ‘Functional’, ‘Fireplaces’,  ‘FireplaceQu’,  ‘GarageType’,  ‘GarageYrBlt’, ‘GarageFinish’ ,  ‘GarageCars’ ,  ‘GarageArea’,  ‘GarageQual’ , ‘ GarageCond’ , ‘PavedDrive’ ,  ‘ WoodDeckSF’,  ‘OpenPorchSF’,  ‘EnclosedPorch’,  ‘3SsnPorch’, ‘ ScreenPorch’, ‘PoolArea’, ‘  PoolQC ‘,  ‘ Fence’, ‘ MiscFeature ‘, ‘ MiscVal’,  ‘MoSold’,  ‘YrSold’,  ‘SaleType’ , ‘SaleCondition’ , ‘SalePrice’
* Column used as target in the final model: SalesPrice
* Model Type: Random Forest Regressor
* Software Used: Python with scikit-learn
* Version: scikit-learn 1.0.2
* Hyperparameters: n_estimators: 100, random_state: 42

## Ethical Considerations in Using Predictive Models in Real Estate

The use of predictive models in real estate introduces potential challenges and risks, encompassing both technical limitations and real-world consequences for stakeholders like homebuyers, sellers, and real estate agents. This summary explores these issues, focusing on possible adverse impacts related to data limitations, uncertainties in predictions, and unexpected results.

* Potential Negative Impacts of the Model

Predictive model accuracy is inherently limited by data quality. Errors, missing values, or biases in data collection can lead to inaccurate predictions, misleading users who rely on them. Additionally, an overly complex model may overfit the training data, performing well on past data but poorly with new data, reducing reliability. For homebuyers, sellers, and agents, inaccurate valuations can lead to financial consequences. For example, a seller may underprice their property, or a buyer may overpay due to the model’s valuation. Moreover, predictive models can perpetuate social biases, such as those seen in historical practices like redlining and biased house appraisals. These biases have long-term financial consequences, disproportionately affecting certain groups of people and exacerbating existing inequalities.

* Potential Uncertainties Relating to Model Impacts

Predictions from these models are probabilistic, not guarantees, and should be interpreted cautiously, considering other factors like economic conditions or market trends. Model reliability can also vary due to hyperparameter tuning, where minor setting adjustments may yield different outcomes. Real-world uncertainties further complicate predictions. Unexpected events like economic changes, natural disasters, or new regulations can alter property values. Additionally, biases in data, such as socioeconomic or location-based trends, may cause the model to favor certain property characteristics, potentially disadvantaging properties in less affluent areas.

* Unexpected Results

During evaluation, properties with unique features or few comparable sales may yield significant prediction errors. For example, homes with custom designs or near new amenities might differ from model predictions due to characteristics not captured in the data. These deviations highlight the model’s limitations, underscoring the need for cautious interpretation.

* Social Bias and Long-Term Consequences

The use of predictive models in real estate can also perpetuate social biases, such as those seen in historical practices like redlining and biased house appraisals. These biases have long-term financial consequences, disproportionately affecting certain groups of people. For instance, homes in minority neighborhoods have historically been undervalued, leading to significant wealth disparities. Ensuring that predictive models are free from such biases is crucial to prevent exacerbating existing inequalities.

In summary, while predictive models hold promise in real estate, their use must be balanced with awareness of technical limitations, probabilistic outputs, and ethical implications to protect stakeholders from potential risks.

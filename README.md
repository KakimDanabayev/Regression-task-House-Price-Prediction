# Regression-task-House-Price-Prediction
A simple yet challenging project, to predict the housing price based on certain factors like house area, bedrooms, furnishes, nearness to main road, etc. The dataset is small yet, it's complexity arises due to the fact that it has strong multicollinearity. 

![house-money3_2](https://github.com/KakimDanabayev/Regression-task-House-Price-Prediction/assets/127029668/c6a0dcd9-4541-4ad2-9388-d6375a729917)

## Acknowledgement

Harrison, D. and Rubinfeld, D.L. (1978) Hedonic prices and the demand for clean air. J. Environ. Economics and Management 5, 81–102.
Belsley D.A., Kuh, E. and Welsch, R.E. (1980) Regression Diagnostics. Identifying Influential Data and Sources of Collinearity. New York: Wiley.

## Objective
- Understand the Dataset & cleanup.
- Feature Engineering and Data Processing: the process of using raw data to create features that will be used for predictive modeling.
- Build Regression models to predict the sales w.r.t single & multiple features.
- Evaluate the models & compare thier respective scores like R2, RMSE.

## Research process
Worked 30 hours for 3 weeks as a data scientist and developed regression models and evaluated results. Data Analysis included using different analyzing techniques, fact-checking, extracting new data, patterns & data visualization, feature engineering, building pipelines, and final evaluation & reporting.

## Dataset Attribution 
- SalePrice - the property's sale price in dollars. This is the target variable that you're trying to predict.
- MSSubClass: The building class
- MSZoning: The general zoning classification
- LotFrontage: Linear feet of street connected to the property
- LotArea: Lot size in square feet
- Street: Type of road access
- Alley: Type of alley access
- LotShape: General shape of the property
- LandContour: Flatness of the property
- Utilities: Type of utilities available
- LotConfig: Lot configuration
- LandSlope: Slope of property
- Neighborhood: Physical locations within Ames city limits
- Condition1: Proximity to main road or railroad
- Condition2: Proximity to main road or railroad (if a second is present)
- BldgType: Type of dwelling
- HouseStyle: Style of dwelling
- OverallQual: Overall material and finish quality
- OverallCond: Overall condition rating
- YearBuilt: Original construction date
- YearRemodAdd: Remodel date
- RoofStyle: Type of roof
- RoofMatl: Roof material
- Exterior1st: Exterior covering on the house
- Exterior2nd: Exterior covering on house (if more than one material)
- MasVnrType: Masonry veneer type
- MasVnrArea: Masonry veneer area in square feet
- ExterQual: Exterior material quality
- ExterCond: Present condition of the material on the exterior
- Foundation: Type of foundation
- BsmtQual: Height of the basement
- BsmtCond: General condition of the basement
- BsmtExposure: Walkout or garden-level basement walls
- BsmtFinType1: Quality of basement finished area
- BsmtFinSF1: Type 1 finished square feet
- BsmtFinType2: Quality of second finished area (if present)
- BsmtFinSF2: Type 2 finished square feet
- BsmtUnfSF: Unfinished square feet of the basement area
- TotalBsmtSF: Total square feet of the basement area
- Heating: Type of heating
- HeatingQC: Heating quality and condition
- CentralAir: Central air conditioning
- Electrical: Electrical system
- 1stFlrSF: First Floor square feet
- 2ndFlrSF: Second-floor square feet
- LowQualFinSF: Low-quality finished square feet (all floors)
- GrLivArea: Above grade (ground) living area square feet
- BsmtFullBath: Basement full bathrooms
- BsmtHalfBath: Basement half bathrooms
- FullBath: Full bathrooms above grade
- HalfBath: Half baths above grade
- Bedroom: Number of bedrooms above basement level
- Kitchen: Number of kitchens
- KitchenQual: Kitchen Quality
- TotRmsAbvGrd: Total rooms above grade (does not include bathrooms)
- Functional: Home functionality rating
- Fireplaces: Number of fireplaces
- FireplaceQu: Fireplace quality
- GarageType: Garage location
- GarageYrBlt: Year garage was built
- GarageFinish: Interior finish of the garage
- GarageCars: Size of garage in car capacity
- GarageArea: Size of garage in square feet
- GarageQual: Garage quality
- GarageCond: Garage condition
- PavedDrive: Paved driveway
- WoodDeckSF: Wood deck area in square feet
- OpenPorchSF: Open porch area in square feet
- EnclosedPorch: Enclosed porch area in square feet
- 3SsnPorch: Three-season porch area in square feet
- ScreenPorch: Screen porch area in square feet
- PoolArea: Pool area in square feet
- PoolQC: Pool quality
- Fence: Fence Quality
- MiscFeature: Miscellaneous feature not covered in other categories
- MiscVal: $Value of miscellaneous feature
- MoSold: Month Sold
- YrSold: Year Sold
- SaleType: Type of sale
- SaleCondition: Condition of sale

## Conclusion
Worked 30 hours for 3 weeks as a data scientist and developed regression models and evaluated results. Data Analysis included using different analyzing techniques, fact-checking, extracting new data, patterns & data visualization, feature engineering, building pipelines, and final evaluation & reporting.
- First, I used different analyzing techniques to see the relationship between features to the target. 
- Second, I extracted new data to see some patterns in the feature engineering part by merging variables and creating new factors.
- Third, in this work, I put my efforts to visualize all of my findings in the 'EDA' and 'Feature Engineering' parts.
- Fourth, I used pipelines and grid search to tune models' hyperparameters and find the best estimators for them.
- Fifth, I added four different types of regression metrics and also used an MAE, R2. RMSE matrix to evaluate model performances.

In this regression task, I used XGBoost_Regressor, KNeighborsRegressor, RandomForestRegressor, and Lasso. XGBoost_Regressor (train 0.970, test 0.883) showed a better score in R2 compared with other models. In the pipeline, I added imputation methods, encoding methods, and scaling methods (for some) and additionally added functions to drop constant, duplicated, and correlated features (though eventually, I ended up keeping only a few factors, I decided not to delete and keep these functions).    

I hope that my work will help you and perhaps answer some of your questions. I tried to comment on each line of the code, describe all graphs, and even add some comments after each analytical and feature engineering part for your convenience. Please like and leave a comment if you liked my work. And I wish each and every one of you [Happy Coding]. 

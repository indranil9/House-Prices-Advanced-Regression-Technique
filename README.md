#House Prices

##Problem Description
Ask a home buyer to describe their dream house, and they probably won't begin with the height of the basement ceiling or the proximity to an east-west railroad. But this playground competition's dataset proves that much more influences price negotiations than the number of bedrooms or a white-picket fence.

With 79 explanatory variables describing (almost) every aspect of residential homes in Ames, Iowa, this competition challenges you to predict the final price of each home.


#Part 1:Exploratory Data Analysis
1.1 Get an overview of the features (numerical and categorical) and first look on the target variable SalePrice
shape, info, head and describe
Distribution of the target variable SalePrice
Numerical and Categorical features
List of features with missing values and Filling missing values
log transform
1.2 Relation of all features to target SalePrice
Seaborn regression plots for numerical features
List of numerical features and their correlation coefficient to target
Seaborn boxplots for categorical features
List of categorical features and their unique values
1.3 Determine the columns that show strong correlation to target
Correlation matrix 1 : all numerical features
Determine features with largest correlation to SalePrice_New

#Part 2: Data wrangling
Dropping all columns with weak correlation to SalePrice
Convert categorical columns to numerical
Checking correlation to SalePrice for the new numerical columns
use only features with strong correlation to target
Correlation Matrix 2 (including converted categorical columns)
create datasets for ML algorithms

#Part 3: Scikit-learn basic regression models and comparison of results
implement GridsearchCV for Hyperparameter tuning
for these models from sklearn:
Linear Regression
Lasso
Stochastic Gradient Descent
DecisionTreeRegressor
Random Forest Regresso
XgBoost
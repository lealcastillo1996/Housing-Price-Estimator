# Price sale for housing regressor

The **objective** of this project is to create an accurate sale price calculation tool for a Real State company, developing in the process a full Data Science Project

![alt text](https://www.investopedia.com/thmb/FsaVFaKYsbEVzCG1lrQ-MpwdUGY=/425x282/filters:fill(auto,1)/housecalculator-56a7dc723df78cf7729a0745.jpg)

## Overview
### - Exploratory Data Analysis of housing data (Insights):

- Missing values handling
- All numerical variables
- Distribution of numerical variables
- Categorical variables
- Cardinatily of categorical variables
- Outliers
- Relationships between dependent and independent features


### - Feature engineering framework:

- Splitting data into train and test set with stratified sampling tecnique to preserve distributions found in the housing data
- Creation of an advanced custom transformation pipeline with helpfull tools such as: median imputer, log normalization, custom column modifiers, rare category handler, NaN dropper, categoric variable encoder and variables scaler. (to clean and transform in a fast way future raw sets)

*Note: I could have used ScikitLearn tools such as imputer or Ordinal Encoder, however to add more value to the project and have more control I defined my own cleaning functions*

### - Feature selection framework:

-Use filter algorithms simple methods such as Chi square and Correlation matrix methods to have an initial visualization.

- Different regression embeded methods will be used to determine feature importance and select the best features to feed our models:
- Linear Regression
- Decision Tree Regression
- Random Forest Regression
- XgBoost Regression
- Permutation Regression

*I propose 2 ways of selecting best features, one is simply selecting the top occurrences total sum of the counts, the second one is selecting the the features that appeared as a top in at least 2 different models*

### - Model selection, training and tunning:
Diferent algorithms to find the one with the best metrics and results for this problem

Models proposed:
- Linear Regressor
- Decision Tree Regressor
- Random Forest Regressor
- Support vector machine regressor
- KG-Boost Regressor
- K-n Neighbor regressor
- Lasso Regressor

### - Results summary

A regressor tool for estimating housing sale price was developed from scrath with excelent results, reaching a 88% accuracy in test set. All steps and assumptions were important to reach this result


![real-estate-price-market-analysis-concept-house-models-under-magnifier-tool-calculator-214750730.jpeg](attachment:real-estate-price-market-analysis-concept-house-models-under-magnifier-tool-calculator-214750730.jpeg)



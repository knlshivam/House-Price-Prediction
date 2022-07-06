# Project Name
> Using Lasso and ridge Regression models, Finding the features which affect the pricing (target feature) of houses in Australia for the client entering into Australian market


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)


<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Using the given dataset, trying to analyze the features which affect the price of houses the most.
- The project is to work, using Rasso and ridge regression models on the given unclean dataset
- To find the features from the given set of features both quantitative and qualitative which afects the costing
- the dataset includes the data of Australia's House selling price with the features of the property ranging from date of manufacture to even small miscellaneous features

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- After the EDA, various features were very less diverse and had single value representing 80% dataset, thus removing those features
- Also, many features were highly correlated having more than absolute 0.8 of correlation, removed such columns
- Also, cleaned the data of the outliers using box plot only when necessary.
- After, Lasso and ridge regression, we got train and testing R2 score to be similar and more tha 0.85, thus confirming the robust and generalized trained model.
- Imfortant features found were - TotalBsmtSF, YearBuilt, GarageArea, TotRmsAbvGrd, KitchenQual_TA

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- pandas - v1.3.4
- numpy - 1.20.3
- matplotlib - v3.4.3
- seaborn - v0.11.2
- sklearn - v0.24.2

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->


## Contact
Created by [@knlshivam] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
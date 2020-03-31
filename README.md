# Mishmash-Online-Hackathon

One of Unilever’s brands is going through some major changes in Business Execution plans and will like to know:
What are the major drivers for sales(EQ)?
Knowing the drivers, how can they predict future sales for the next 6 periods?

## Tech Used
Python - Pandas, Numpy, Scikit-learn, Matplotlib and Seaborn
Google Cloud Platform to run the models - Compute and Storage

## Sales Drivers
The top five drivers for determining sales are:
* Median_Rainfall
* Social_Search_Impressions
* pct_PromoMarketDollars_Category
* Inflation
* EQ_Category

## Methods used to arrive to these features:
* Feature Importance of a model [model.feature_importances_]
* Seaborn’s(python library) Correlation matrix with heatmap 

## Models Used
The top five models used for determining sales are:
* RandomForestRegressor
* GradientBoostingRegressor
* LinearRegression
* Support Vector Regressor
*MLPRegressor

### RandomForestRegressor was the best performing and hence we applied it on the test data.

out.csv is the final output file.




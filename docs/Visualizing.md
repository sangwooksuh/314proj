# Visualizing
To properly utilize this module, you will want to have already cleaned your dataframe.



## 1. scatter(df, feature1, feature2)
Takes a dataframe, and 2 of its columns/features, and plots a scatterplot between the two variables.

| input    | description                                                       |
|----------|-------------------------------------------------------------------|
| df       | DataFrame - Cleaned dataframe you want to scatter the data from   |
| feature1 | String - column name of feature you want to scatter, x-axis       |
| feature2 | String - other column name of feature you want to scatter, y-axis |

*Example:* scatter(italy_df, "num_amenities", "price")



## 2. prices_violin_plot(df)
Takes a dataframe, generates a violinplot to visualize the distribution of nightly prices

| input    | description                                                     |
|----------|-----------------------------------------------------------------|
| df       | DataFrame - Cleaned dataframe you want visualize the price with |

*Example:* prices_violin_plot(italy_df)



## 3. predict_price(df, feature, feature_val)
Takes a dataframe, a feature to predict the price with, and the value of that feature.

| input   | description                                                                    |
|---------|--------------------------------------------------------------------------------|
| df      | DataFrame - Cleaned dataframe you want to scatter the data from                |
| feature | String - column name of feature you want to train Linear Regression model with |
| val     | int/float - value of feature that you want the price to be predicted for       |

*Example:* predict_price(italy_df, "description_wordcount", 200)
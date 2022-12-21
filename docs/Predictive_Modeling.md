# Predictive Modeling

Using functions from *Scraping* and *Cleaning* we provide a example analysis with KNN Regressor and Linear Regession Models, tuning different hyperparameters.

## 1. get_basic_XY(df)
Takes a cleaned dataframe, takes only numerical columns, converts pandas datetime to ordinal integer variables for model input, and returns a features DataFrame X and a target column (price) Series y.

| input    | description                                                       |
|----------|-------------------------------------------------------------------|
| df       | DataFrame - Cleaned dataframe you want to analyze                 |


*Example:* X, y = get_basic_Xy(cleaned_df)



## 2. var_filter(X, num_features=10)
Takes a dataframe of numerical features, and returns a dataframe containing the top num_features features with respect to variance. 
This is a Simple Quality Filter with the assumption that columns with more variance are likely to be more informative.

| input    | description                                                     |
|----------|-----------------------------------------------------------------|
| df       | DataFrame - DataFrame of numerical features to analyze          |
| num_features       | int - target number of features         |

*Example:* X_selected_features = var_filter(X, 10)



## 3. make_poly(X, y, degree)
Takes X, y values, then does a polynomial feature transformation with provided degree, fits a linear model, and returns the result.

| input   | description                                                                    |
|---------|--------------------------------------------------------------------------------|
| X       | DataFrame - Features              |
| y       | Series - Target |
| degree  | int - degree of desired polynomial transformation      |

*Example:* poly_model = make_poly(X, y, 2)

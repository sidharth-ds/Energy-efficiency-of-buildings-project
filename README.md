# Energy-efficiency-of-buildings-project

### Target variables:
   * The heating load (y1) is the amount of heat energy that would **need to be added** to a space to maintain the temperature in an acceptable range. 
   * The cooling load (y2) is the amount of heat energy that would **need to be removed** from a space (cooling) to maintain the temperature in an acceptable range.
    
### Features:
    * X1 - Relative Compactness
    * X2 - Surface Area
    * X3 - Wall Area
    * X4 - Roof Area
    * X5 - Overall Height
    * X6 - Orientation
    * X7 - Glazing Area
    * X8 - Glazing Area Distribution
    
### Feature correlations:
    * "overall_height" has the highest correlation with heating_load and cooling_load (which is a positive correlation),
    * "roof_area" for both outputs which is a negative correlation,
    * "orientation" has the least correlation.
### EDA:
    * Most of the dataset samples fall between 10 and 20 units of both 'heating_load' and 'cooling_load' regressional output classes.
    
### Feature importances:
    * top 4 selected features/feature combination for predicting heating_load using Recursive Feature Elimination:
        * relative_compactness
        * surface_area
        * roof_area
        * overall_height
    * top 4 selected features/feature combination for predicting cooling_load using Recursive Feature Elimination:
        * relative_compactness
        * surface_area
        * overall_height
        * glazing_area
        
### Modelling:
    * Linear regression, Ridge & Lasso regression
    * Decision tree, Random forest, KNN-regressor
 
### Metrics:
    * Decision tree & Random forest gives an accuracy of 97% in predicting the load using CROSS VALIDATION technique
    
  

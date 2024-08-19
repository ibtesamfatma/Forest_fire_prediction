Algerian Forest Fires Dataset
Dataset Description:

This dataset contains information about forest fires in two regions of Algeria: Bejaia (northeast) and Sidi Bel-Abbes (northwest). The data spans from June to September 2012 and includes 244 instances with 11 attributes and a target variable indicating whether a fire occurred.

Attributes:

Date: (DD/MM/YYYY) Day, month, and year.
Temp: Temperature at noon in Celsius (22-42).
RH: Relative humidity in percentage (21-90).
Ws: Wind speed in km/h (6-29).
Rain: Total rainfall for the day in mm (0-16.8).
FFMC: Fine Fuel Moisture Code from FWI system (28.6-92.5).
DMC: Duff Moisture Code from FWI system (1.1-65.9).
DC: Drought Code from FWI system (7-220.4).
ISI: Initial Spread Index from FWI system (0-18.5).
BUI: Buildup Index from FWI system (1.1-68).
FWI: Fire Weather Index (0-31.1).
Classes: Target variable indicating fire (1) or not fire (0).
EDA Findings:

Weather: Higher fire counts occur at temperatures between 30-37 degrees Celsius, low rainfall (0-0.3 mm), wind speeds of 13-19 km/h, and relative humidity between 50-80%.
FWI Components: Higher FFMC (>75) and DMC (10-30) indicate a higher likelihood of fire. Lower DC (0-25), ISI (0-3), and BUI (1.1-10) suggest a lower risk of fire. Higher FWI (3-25) indicates a higher fire risk.
Data Preprocessing:

Feature selection was performed.
Data was standardized.
Modeling:

Several regression models were applied:

Linear Regression: Mean Absolute Error (MAE) = 0.5468, R2 Score = 0.9848
Lasso Regression: MAE = 1.1332, R2 Score = 0.9492
Ridge Regression: MAE = 0.5642, R2 Score = 0.9843
Elasticnet Regression: MAE = 1.8822, R2 Score = 0.8753
Note: These results are preliminary and further analysis and model tuning are required.

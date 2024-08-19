Algerian Forest Fires Dataset 🔥



Dataset Overview 🗺️
This dataset provides insights into forest fires across two Algerian regions: Bejaia (northeast) and Sidi Bel-Abbes (northwest). It spans June to September 2012, encompassing 244 instances with 11 attributes and a target variable indicating fire occurrence.



Key Attributes 📊
Weather: ☀️ Temperature, 
💧 Relative Humidity, 
💨 Wind Speed, 
🌧️ Rainfall
FWI Components: 🌿 Fine Fuel Moisture Code (FFMC), 🌳 Duff Moisture Code (DMC), 🏜️ Drought Code (DC), 🔥 Initial Spread Index (ISI), 
🌲 Buildup Index (BUI), 🔥 Fire Weather Index (FWI)

Target: 🔥 Fire (1) or No Fire (0)


EDA Highlights 🔍
Weather Patterns: Fires are more likely under scorching temperatures (30-37°C), 
low rainfall, moderate winds (13-19 km/h), and moderate humidity (50-80%).
FWI Insights: High FFMC (>75) and DMC (10-30) signal increased fire risk. 
Conversely, low DC (0-25), ISI (0-3), and BUI (1.1-10) indicate lower fire potential. High FWI (3-25) correlates with elevated fire risk.

Data Preprocessing ⚙️
Feature Selection: Identifying the most impactful attributes.
Standardization: Ensuring data consistency for modelling.


Modelling Results 🤖
Multiple regression models were employed:

Linear Regression: Achieved an impressive R² score of 0.9848, demonstrating strong predictive power.
Lasso, Ridge, Elasticnet: While valuable, Linear Regression outperformed them in this case.
Note: These findings are preliminary and require further refinement.

Let's work together to unravel the complexities of forest fires and develop robust prevention strategies! 🌳🔥

## BikeSharingCaseStudy

A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.

A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state

They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:

1) Which variables are significant in predicting the demand for shared bikes?
2) How well those variables describe the bike demands?

The business goal is to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features


## Solution Approach

The approach involves the following steps

### Step 1. Reading, Understanding & Visualizing the Data
### Step 2. Data Preparation for Modeling
### Step 3. Building & Training the Model
### Step 4. Residual Analysis of the Train Data
### Step 5. Making Prediction using the Final Model


## Technology used

- Python 3.12.4
- Numpy 1.26.4
- Pandas 2.2.2
- Seaborn 0.13.2
- Matplotlib 3.8.4
- Scikit-Learn 1.4.2
- Statsmodels 0.14.2


## Final Result & Summary Report

- Train R^2 :0.796
- Train Adjusted R^2 :0.793
- Test R^2 :0.780
- Test Adjusted R^2 :0.772

As per our final Model, the top 3 predictor variables that influences the bike booking are:

#### Temperature (temp) - A coefficient value of ‘0.5772’ indicated that a unit increase in temp variable increases the bike hire numbers by 0.5772 units.
#### Weather Situation 3 (weathersit_3) - A coefficient value of ‘-0.2769’ indicated that (with respect to weathersit_1, a unit increase in weathersit_3 variable decreases the bike hire numbers by -0.2769 units.
#### Year (yr) - A coefficient value of ‘0.2334’ indicated that a unit increase in yr variable increases the bike hire numbers by 0.2334 units.
So, it's suggested to consider these variables while planning, to achive maximum Booking

The next set of features that can be considered are

#### season_4: - A coefficient value of ‘0.1227’ indicated that (with respect to) season_1), a unit increase in season_4 variable increases the bike hire numbers by 00.1227 units.
#### windspeed: - A coefficient value of ‘-0.1463’ indicated that, a unit increase in windspeed variable decreases the bike hire numbers by -0.1463 units.

#### Note:

##### weathersit_1 refers to: Clear, Few clouds, Partly cloudy, Partly cloudy
##### weathersit_3 refers to: Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds
##### season1 refers to: spring
##### season4 refers to: winter

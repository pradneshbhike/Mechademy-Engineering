# Mechademy Task
# Assignment 1: Used Cars Price Prediction and Evaluation

Index

1. Importing Libraries

2. Importing Dataset

3. Data Wrangling

4. Visualizing and Examining Data

Plots to compare predictor variable with target

4.1 Volume(Cm3) v/s PriceUSD

4.2 Year v/s PriceUSD

4.3 Fuel Type v/s PriceUSD

4.4 Make(Counts)

4.5 Transmission v/s PriceUSD

4.6 Condition v/s PriceUSD

4.7 Drive Unit v/s PriceUSD

4.8 Color v/s PriceUSD

4.9 Segment v/s PriceUSD

5. Working with Categorical Data - one hot encoding and label encoding

5.1 Drive Unit

5.2 Fuel Type

5.3 Condition

5.4 Segment

6. Preparation of Model Data

Train Test split

7. Model Building

7.1 Linear Regression

7.2 Random Forest

Error chart

# Assignment 2: Propulsion Plants Decay Evaluation

In this project, I have built a regression model using the deep learning Keras library, and then I experimented that with increasing the number of training epochs and changing number of hidden layers and I made observations of how changing these parameters impacted the performance of the model. A regression model using the Keras library to model the Propulsion Plant Decay Evaluation data.

The predictors in the Propulsion Plant Decay dataset includes:

1. Lever position. (lp)

2. Ship speed (v) [knots]

3. Gas Turbine shaft torque (GTT) [kN m]

4. Gas Turbine rate of revolutions (GTn) [rpm]

5. Gas Generator rate of revolutions (GGn) [rpm]

6. Starboard Propeller Torque (Ts) [kN]

7. Port Propeller Torque (Tp) [kN]

8. HP Turbine exit temperature (T48) [C]

9. GT Compressor inlet air temperature (T1) [C]

10. GT Compressor outlet air temperature (T2) [C]

11. HP Turbine exit pressure (P48) [bar]

12. GT Compressor inlet air pressure (P1) [bar]

13. GT Compressor outlet air pressure (P2) [bar]

14. Gas Turbine exhaust gas pressure (Pexh) [bar]

15. Turbine Injecton Control (TIC) [%]

16. Fuel flow (mf) [kg/s]

17. GT Turbine decay state coefficient.

The target is Gas Turbine Compressor decay state coefficient.

Project is divided in 3 sections (A, B and C as mentioned below).

Model is trained with 70% data and tested by 30% of data.

In section A, 1 hidden layer and 10 nodes each layer Neural Network is used and the model is trained with 50 epochs.

Average of the errors = 5.47

Standard Deviation of errors = 9.92

In section B, 1 hidden layer and 10 nodes each layer Neural Network is used and the model is trained with 100 epochs.

Average of the errors = 3.95

Standard Deviation of errors = 16.06

In section C, 3 hidden layers and 10 nodes each layer Neural Network is used and the model is trained with 50 epochs.

Average of the errors = 0.78

Standard Deviation of errors = 2.93

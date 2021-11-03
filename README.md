<p align="center"><a href="https://imgbb.com/"><img src="https://i.pinimg.com/originals/fc/44/58/fc445856e06f4f7c767efc090fd12f86.png" alt="DIAMOND" width="25%" border="0"></a><br /></p>
<h1 align="center">📈 Diamond Price Prediction| Linear Regression </h1>

## Project Status
:heavy_check_mark: Complete

## Table of Contents 
- [Objective](#objective)
- [Resources](#Resources)
- [Process](#Process)
- [Results](#Results)
- [Learning Process](#Learning-Process)
- [Authors](#Authors)

## Objective
The objective of this project is to create a model to predict prices of diamonds, practicing linear regression.<br>
To acess complete objective informations click <a href="https://drive.google.com/file/d/1SR_lkpSamfoPeFckpfvM4PskhPhkzA3l/view?usp=sharing">here</a>.

### Problem Statement
> Predicted price must be below 900 RMSE 

## Resources
Datasets was provided by IronHack. <br>
00-diamonds.csv<br>
00-rick_diamonds.csv<br>

## Process
- Import the dataframe;
- Create a first baseline predicting the price by the mean;
- Start to Explore and Clean the Data:
     - Check null values;
     - Search for outliers - comparing mean and median;
     - Calculate values to correct x,y and z;
     - Check correlations.
- Apply the linear regression to predict the prices of diamonds;
- Improve the model until RMSE (root mean squared error) < 900.

## Results
After a lot of attempts, we obtained:


 ### Image summary:
|    R²   |  RMSE  |
|  -----  | -------|
| 95.8%   |    660  |
     
     
And comparing to Rick's dataset we got:
<br>
<img src="https://user-images.githubusercontent.com/85833899/139990704-a1876369-1ef7-4be2-938e-6647a1e98fc4.png" alt="pawn" width="50%" border="0">

## Learning Process

### Theory Applied
- [x] Numpy
- [x] Pandas
- [x] MatplotLib and Seaborn
- [x] Linear Regression

### Challenges
- Apply the model for two non-linear variables;
- Decrease the RMSE for the amount requested.

 ### Improvements
 - Use target encoder on categorical variables;
 
## Authors
Lucas Angulski <br>

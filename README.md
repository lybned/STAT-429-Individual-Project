# Linear Regression Model on Life Expectancy of Countries 

## Dataset:
https://www.kaggle.com/datasets/kumarajarshi/life-expectancy-who
The dataset contains data from 2000 - 2015

## Data Cleaning:
Any rows with at least one empty cell is removed.

## Selected Predictors:
- Country Status (1 for developed and 0 for developing)
- Number of Infant Deaths per 1000 population
- Adult Mortality Rates of both sexes (probability of dying between 15 and 60 years per 1000 population)
- Number of reported cases per 1000 population
- Polio (Pol3) immunization coverage among 1-year-olds (%)
- Gross Domestic Product per capita (in USD)
- Number of years of Schooling (on average)

Life Expectancy is measured in age

## Model 1 (Model With All Predictors)
![alt text](https://github.com/lybned/STAT-429-Individual-Project/blob/main/Pictures/Model%201%20Summary.PNG)

## Model 2 (Model After Cox-Box Transformation)
![alt text](https://github.com/lybned/STAT-429-Individual-Project/blob/main/Pictures/Model%202.PNG)

## Model 3 (Model After All Subset Variable Selection)
![alt text](https://github.com/lybned/STAT-429-Individual-Project/blob/main/Pictures/Model%203.PNG)

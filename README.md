# CO2-predict
This project aims to build a machine learning algorithm based on multiple linear regression to predict CO2 Capture on carbonaceous biomass. 

## Legends

**Features**

BET: BET Surface area (m2/g).

Vol_micro: Micropore volume (cm3/g)

Temp: Temperature of CO2 Capture (°C)

**Target variable**

CO2_Uptake: CO2 capture (mmol/g).

### Normality tests

Shapiro-Wilk test (Small number of samples, n < 30)

Ho = Normal distribuition : p > 0.05

Ha = Non normal distribuition : p <= 0.05

Normal distribution: CO2 Uptake

Non normal distributionl: BET, Vol_micro, Temp

### Linear correlation

Pearson (normal distribution)

Spearman (non normal distribution)

Kendall (non normal distribution with small amount of samples)

Ho = There is no linear correlation: p > 0,05

Ha = There is a linear correlation: p <= 0,05

**MULTIPLE LINEAR REGRESSION:** R2 = 0,69/0,52; RMSE = 1.10; R2 Cross validation: 61.37%

#### Normality test of residues

Ho = normal distribution : p > 0.05

Ha = non normal distribution : p <= 0.05

Breusch-Pagan test (homoscedasticity or heteroscedasticity)

Ho = There is homocedasticity : p > 0.05

Ha = The is no homocedasticity : p <= 0.05

#### **Outliers in residues**

(Between -3 e 3)

#### **Ausence of multicolinearity**

Only between independents variables.

The is multicolinearity when r > 0.9.



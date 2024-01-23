# Carbon adsorption on waste biomass of passion fruit peel: A promising machine learning model for CO2 capture

# Abstract
The escalating concentration of carbon dioxide (CO2) in the atmosphere, primarily attributed to human activities, poses a substantial threat to the environment. To address this challenge, carbon capture and storage (CCS) technologies, including adsorption on carbonaceous materials, have emerged as promising solutions. Among these approaches, functionalized activated carbon by passion fruit peel biomass (FACPFP) stands out. This research aims to quantify the maximum CO2 capture at the laboratory scale using FACPFP and develop an improved machine learning model to predict CO2 capture efficiency.

# Introduction
The alarming increase in atmospheric CO2 levels necessitates innovative strategies for efficient carbon capture. FACPFP, prepared through chemical activation with K2C2O4 and doping with ethylenediamine (EDA), has demonstrated promising characteristics. This study focuses on characterizing FACPFP and implementing a predictive model to enhance CO2 capture precision.

# Problem Statement
The excessive release of CO2 into the atmosphere is a pressing environmental concern. Effective carbon capture methods are crucial to mitigate the impact of climate change. This study addresses the challenge by exploring the CO2 adsorption capacity of FACPFP.

# Assumptions
The chemical activation process with K2C2O4 and EDA significantly enhances FACPFP's CO2 adsorption capacity.
The predictive model's precision is improved with the selected machine learning approach.

# Solution Strategy
FACPFP was meticulously prepared and characterized using various techniques, including TGA, SEM with EDX, FTIR, and XPS. CO2 sorption was assessed using functional density theory (DFT). Additionally, a predictive model based on multiple linear regression with cross-validation was developed to improve CO2 adsorption prediction accuracy.

# Key Insights
- For this research, BET surface area, total pore volume, and micropore volume explain about 61% of CO2 Capture.
- Textural parameters suggest the probable presence of ultra-micropores in FACPFP.
- BET surface area, total pore volume, and micropore volume were determined as 105 m²/g, 0.03 cm³/g, and 0.06 cm³/g, respectively.
- The maximum CO2 adsorption capacity of FACPFP reached approximately 2.2 mmol/g at 0°C and 1 bar.

# Final Product
The study culminates in the successful publication at the Journal of CO2 Uilization. 

# Conclusion
The findings underscore the potential of FACPFP as an effective carbon capture material. The improved predictive model enhances our ability to forecast CO2 adsorption, opening avenues for further research in this critical area.

# Next Steps
It would be of great value to implement other more advanced machine learning models, such as Random Forest, and artificial neural networks to obtain a better R

# Tools used
- ![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
- ![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white)
- ![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
- ![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
- ![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)

# Legends

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


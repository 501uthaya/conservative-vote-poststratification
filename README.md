# Estimating Conservative Vote Share Using Poststratified Survey Data

## Overview
This project estimates the national popular vote share for the Conservative Party in the 2021 Canadian federal election using survey data adjusted to census demographics. A logistic regression model is trained on survey responses, and poststratification is applied using population distributions from the Canadian Census to correct for sampling bias.

## Data Sources
- 2021 Canadian Election Study (CES)
- 2021 Canadian Census (Microdata)

Note: Raw datasets are not included due to data use restrictions.

## Methodology
- Cleaned and recoded demographic variables (age, gender, education)
- Modeled probability of voting Conservative using logistic regression
- Applied poststratification using census population weights

## Results
- Identified demographic patterns in Conservative support
- Estimated poststratified national vote share: approximately 31.7%

## Tools
- R (glm, tidyverse, ggplot2)

## Files
- report.pdf – Full technical report

## Author
Sudar Uthayabalachandran


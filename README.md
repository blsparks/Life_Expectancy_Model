# Life Expectancy Prediction Using Multiple Linear Regression

## Project Overview
Analyzed country-level demographic and socioeconomic indicators to identify factors associated with differences in life expectancy. Applied statistical modeling and variable selection techniques in R to develop an interpretable regression model.

## Tools & Techniques
- **Language:** R
- **Modeling:** Multiple Linear Regression
- **Feature Selection:** Stepwise Regression, AIC, Adjusted R², Mallows' Cp
- **Diagnostics:** Residual Analysis, Multicollinearity Assessment, Box-Cox Transformation

## Key Findings
- Selected five predictors: birth rate, GDP per capita, internet access, cell phone subscriptions, and land area.
- Achieved an **adjusted R² of approximately 0.728**, indicating that the model explained roughly 73% of the variation in the transformed life expectancy outcome.
- Found that birth rate and land area had negative model coefficients, while GDP, internet access, and cell phone subscriptions had positive coefficients.

## Practical Takeaway
The analysis highlights how demographic and socioeconomic indicators can help explain differences in life expectancy across countries. These findings provide a starting point for identifying potential areas of public health research, although the observed relationships should not be interpreted as causal.


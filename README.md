# Overview

This project focuses on linear regression analysis to predict and understand the factors influencing restaurant revenue. Using data from the Kaggle Restaurant Revenue dataset, which contains information on 8,368 restaurants across 16 attributes, the goal was to identify key predictors of revenue and develop regression models that provide actionable insights for restaurant owners.

1. **Single Linear Regression (SLR)**:
   - Analyzed **average meal price** as the primary predictor.
   - Addressed heteroskedasticity through log transformations to improve model fit.
   - Achieved an adjusted \( R^2 \) of 0.465 for the SLR model.

2. **Multiple Linear Regression (MLR)**:
   - Selected predictors using **best subsets regression** based on BIC.
   - Final predictors: **Average meal price**, **Seating capacity**, and **Social media followers**.
   - Balanced simplicity and accuracy to optimize predictive performance.

3. **Model Diagnostics**:
   - Ensured assumptions of linear regression were met:
     - Checked for normality, homoscedasticity, multicollinearity (low VIF scores), and outliers.
     - Addressed influential points using Cook’s distance and leverage analysis.

# Contributors
1. Ricky Miura
2. Serigne Diaw
3. Lukas Amare
4. Katelyn Vuong
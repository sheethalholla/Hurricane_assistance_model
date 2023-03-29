# Hurricane_assistance_model
For my course on Linear Models and Design of Experiments, I developed an interpretive statistical model in R to discover the factors that determine the financial assistance and damage recovery support provided by FEMA to the citizens affected by Hurricane Harvey in Houston. 

To do this, I developed a multi-variate linear model that can reasonably predict the financial assistance amount using applicant-based factors, damage levels, and locality-related factors. I collected data from various sources such as FEMA, OCHA index website, and census data and fused them using geographic-keys. I followed a stepwise model building approach, including data preparation and exploration, model selection, model evaluation and diagnostics, and model validation and comparison. For model selection I compared the fitted linear model with non-parametric models based on their predictive ability.


I explored the impact of economic connectedness index and civic organization index on assistance levels. 

I analyzed the relationships between various predictors such as damage assessment, personal factors, income, market prices, locality factors, and assistance amount. 

I was able to conclude that damage assessment, household composition, and market prices of damaged dwellings have a significant impact on damage assessments. 

Expectedly, the model indicated that damage levels to real property are a significant predictor of overall damage assessment, while personal factors such as age and household composition are not significant predictors. Surprisingly, the model also showed that higher income may lead to lower assistance amount, and market list prices of damaged dwellings have no significant impact on assistance.

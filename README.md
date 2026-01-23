
## Research Question
Can we use BMI and Age to accurately predict the percentage of body fat in men?

# Overview
A statistical analysis using Linear and Logistic Regression to determine the efficacy of BMI and Age as predictors for Body Fat percentage. Includes data cleaning, outlier removal (IQR), and visualization.

## Key Features
- **Data Cleaning:** Automated outlier removal using the Interquartile Range (IQR) method.
- **Linear Regression:** Modeling the relationship between Age/BMI and Body Fat.
- **Logistic Regression:** Classifying "High Body Fat" (over 20%) based on BMI.
- **Visualizations:** Regression plots, Age-grouped scatter plots, and Heatmaps for confusion matrices.

## Key Insights
- **BMI** accounts for approximately **47.4%** of the variance in body fat.
- **Age** has a weak positive correlation, accounting for only **8.5%** of variance.
- **Conclusion:** While positive relationships exist, BMI and Age are insufficient as standalone predictors due to confounding variables.

## Data Source
Dataset provided by [fedesoriano on Kaggle](https://www.kaggle.com).
Limited to sample of 252 men.

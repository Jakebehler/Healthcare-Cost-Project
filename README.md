# Healthcare Risk Modeling Case Study: A $23.8k Insight Analysis

## Project Goal: 
- Accurate cost prediction is critical across the healthcare industry. I analyzed 1,338 records to identify which demographic and lifestyle factors drive medical cost differences to inform risk-based pricing decisions.

## Methodology: 
- **Data Integrity & Prep:** Conducted data validation and outlier analysis in Python (Pandas), ensuring statistical assumptions were met prior to modeling. Encoded categorical variables to enable regression-based modeling.
- **Statistical Modeling:** Built a Multiple Linear Regression (OLS) model to isolate and quantify each variable’s independent contribution to annual healthcare charges. Achieved an Adjusted R² of 0.75, indicating strong explanatory power.
- **Visual Storytelling:** Developed an interactive Tableau dashboard using parameterized filters and custom calculations to translate abstract statistical coefficients into actionable financial insights.

## Key Finding: 
- **The $23.8k Smoking Impact:** Smoker status is the dominant cost driver, driving an average increase of $23,848 in annual charges, holding age, BMI, and region constant.
- **BMI/Age Scale:** Each additional BMI unit and year of age increases annual charges by approximately $339 and $256, respectively, indicating a steady, linear growth in risk.
- **Conclusion:** Results indicate that lifestyle factors are significantly stronger predictors of cost than geographic variables, suggesting that targeted intervention programs would be more effective than region-based approaches.

## Strategic Business Application:
- **Cost Driver Prioritization:** Analysis suggests that lifestyle indicators such as smoking and BMI are significantly stronger predictors of healthcare costs than geographic variables, and should be weighted accordingly in cost modeling and resource allocation.
- **Targeted Wellness Programs:** Data identifies specific high-risk clusters where preventative wellness initiatives could have the greatest impact on reducing costs and improving outcomes.

## Links
- [Tableau Dashboard](https://drive.google.com/file/d/1s527oyVR_nnCizXhkYwKM997kcTdOcqH/view?usp=share_link)
- [Python Code](https://drive.google.com/file/d/1-PQQUgVOZrWsDapzQuLaMi-blloKJg1U/view?usp=sharing)

#  **Climate Change & Carbon Emissions Impact Analysis**

##  **Overview**

This repository presents a data-driven analysis of the impact of carbon emissions on global temperature anomalies. By exploring historical trends and the relationship between CO₂ concentrations and temperature changes, this project provides valuable insights for researchers, policymakers, and environmental advocates working to address climate change.


##  **Project Description**

Climate change is one of the most critical challenges of our time. This analysis investigates how rising carbon emissions correlate with global temperature increases. The project employs statistical methods, time-series analysis, and predictive modeling to:

- Identify historical trends in temperature anomalies and CO₂ concentrations.
- Quantify the relationship between CO₂ levels and temperature changes using correlation and regression techniques.
- Explore lagged effects to determine how past CO₂ levels impact current temperatures.
- Cluster climate patterns to reveal distinct periods of low, moderate, and high temperature changes.
- Simulate “what-if” scenarios to assess how modifications in CO₂ emissions might influence future temperatures.

##  **Datasets**

This study integrates two primary datasets:

- **Temperature Data:** Annual temperature anomalies (°C) measured across multiple countries and decades.
- **CO₂ Data:** Monthly global atmospheric CO₂ concentrations (ppm), representing the accumulation of greenhouse gases.

*Data can be downloaded from the provided source link in the repository.*

##  **Methodology**

The analysis follows a systematic approach:

1. **Descriptive Statistics:**  
   - **Temperature Anomalies:** Mean ~0.54°C, Median ~0.47°C, Variance ~0.43.
   - **CO₂ Concentrations:** Mean ~180.72 ppm, Median ~313.84 ppm, Variance ~32,600.
2. **Time-Series Analysis:**  
    ![trend](https://github.com/user-attachments/assets/73b4160f-c1bb-48c2-8bed-8d5090edd6dc)

   The time-series graph shows a consistent increase in CO₂ concentrations (measured in ppm) over the years, which indicates the accumulation of greenhouse gases in the atmosphere. Simultaneously, a slight upward trend in global temperature change suggests that rising CO₂ levels are associated with global warming. The temporal alignment supports the hypothesis of CO₂’s significant contribution to temperature increase.
![heatmap](https://github.com/user-attachments/assets/d7b26c69-e356-4838-92ac-e5ffa4e54d7e)
The heatmap reveals a strong positive correlation (0.96) between CO₂ concentrations and temperature changes.
  ![temp](https://github.com/user-attachments/assets/0f7cd650-3e77-44a4-95d8-7deb875b7c87)
The scatter plot shows a clear linear trend, where higher CO₂ concentrations correspond to greater temperature changes.
3. **Trends and Seasonal Variations Analysis:**
   ![slope](https://github.com/user-attachments/assets/8070bc97-92af-427e-9d4b-157a11fc1a66)
   The CO₂ trend has a much steeper slope (0.32) compared to temperature (0.03), which indicates a faster rate of increase in CO₂ emissions relative to temperature change. This suggests that while CO₂ levels are rising rapidly, the temperature impact, though slower, is accumulating steadily and may have long-term consequences.
   ![seasonal](https://github.com/user-attachments/assets/137ccdfe-a829-46f4-a7c3-f21a5897453f)
The above graph highlights the seasonal fluctuations in CO₂ concentrations, which peak during late spring and early summer (around May) and reach the lowest levels in fall (around September). These variations are likely due to natural processes such as plant photosynthesis, which absorbs CO₂ during the growing season, and respiration, which releases CO₂ in the off-season. This seasonal cycle underscores the role of natural carbon sinks in moderating atmospheric CO₂ levels.
4. **Correlation Analysis:**  
   - Pearson Correlation: ≈0.9554  
   - Spearman Correlation: ≈0.9379
 Pearson Correlation (0.9554) indicates a very strong linear relationship between CO₂ concentrations and temperature changes. Spearman Correlation (0.9379) indicates a very strong monotonic relationship between CO₂ concentrations and temperature changes.

5. **Lagged Effects Analysis:**  
we will fit an Ordinary Least Squares (OLS) regression model. This model will use current and lagged CO₂ levels as predictors to estimate their contribution to current temperature anomalies. By examining the regression results, we will determine:

    1.How strongly current CO₂ levels affect temperature changes?
    2.Whether CO₂ levels from previous years have a significant impact?

   Regression analysis (R² = 0.949) indicates that current CO₂ levels (coefficient ≈0.3245, p < 0.05) are the dominant factor in driving temperature changes.
7. **Clustering Analysis:**
   ![clustering](https://github.com/user-attachments/assets/397139de-c738-415b-a915-26560bb59343)

   K-Means clustering segments the data into distinct climate patterns, correlating different phases of temperature change with CO₂ levels.
8. **Predictive Modeling:**  
   What-if scenarios simulate the impact of adjusting CO₂ levels:
   - 10% increase → Predicted temperature anomaly: ~1.09°C
   - 10% decrease → Predicted temperature anomaly: ~-0.06°C
   - 20% increase → Predicted temperature anomaly: ~1.66°C
   - 20% decrease → Predicted temperature anomaly: ~-0.63°C

##  **Key Insights**

- **Strong Correlation:**  
  Both Pearson (≈0.9554) and Spearman (≈0.9379) correlations confirm a robust linear and monotonic relationship between CO₂ concentrations and temperature anomalies.

- **Moderate Temperature Increase:**  
  With a mean of ~0.54°C and a median of ~0.47°C, temperature anomalies have been increasing moderately but steadily over time.

- **Substantial CO₂ Variability:**  
  Despite a mean CO₂ concentration of ~180.72 ppm, the higher median (~313.84 ppm) and large variance (~32,600) reveal significant fluctuations and a rapid upward trend in atmospheric CO₂.

- **Divergent Trends:**  
  The temperature trend slope is ~0.03°C per year compared to a much steeper CO₂ trend slope of ~0.32 ppm per year. This divergence suggests that while temperature increases are gradual, the accumulation of greenhouse gases is accelerating.This sharp contrast suggests that greenhouse gas accumulation is outpacing temperature changes, with potential long-term climate implications.
  
- **Lagged Effects Dominated by Current CO₂ Levels:**  
 An Ordinary Least Squares regression incorporating current and lagged CO₂ values yields an R² of 0.949 and a statistically significant coefficient of approximately 0.3245 (p < 0.05) for current CO₂. This indicates that present-day CO₂ concentrations are the dominant factor influencing temperature changes, with limited impact from historical values.

- **Sensitivity Highlighted by What-If Scenarios:**  
 Predictive modeling shows that a 10% increase in CO₂ levels could raise temperature anomalies to around 1.09°C, whereas a 10% decrease might lower them to approximately -0.06°C. More aggressive scenarios (20% changes) predict temperature anomalies of ~1.66°C for increases and ~-0.63°C for decreases, illustrating the high sensitivity of global temperatures to changes in CO₂ emissions.

Together, these insights emphasize the urgent need for effective carbon emission reduction strategies, as even modest adjustments in atmospheric CO₂ levels can have profound effects on global temperature trends.
## **Conclusion**

This analysis underscores the critical need for timely and effective interventions to reduce carbon emissions. By leveraging historical data and predictive models, the project provides compelling evidence of the intertwined nature of CO₂ concentrations and global temperature changes. The insights gained here serve as a valuable resource for researchers, policymakers, and environmental advocates working towards sustainable solutions for our planet.



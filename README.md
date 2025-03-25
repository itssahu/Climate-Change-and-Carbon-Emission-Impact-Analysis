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
   Visualization of trends over time shows a steady rise in both temperature anomalies and CO₂ levels.
3. **Correlation Analysis:**  
   - Pearson Correlation: ≈0.9554  
   - Spearman Correlation: ≈0.9379  
   These values confirm a strong relationship between CO₂ concentrations and temperature anomalies.
4. **Lagged Effects Analysis:**  
   Regression analysis (R² = 0.949) indicates that current CO₂ levels (coefficient ≈0.3245, p < 0.05) are the dominant factor in driving temperature changes.
5. **Clustering Analysis:**  
   K-Means clustering segments the data into distinct climate patterns, correlating different phases of temperature change with CO₂ levels.
6. **Predictive Modeling:**  
   What-if scenarios simulate the impact of adjusting CO₂ levels:
   - 10% increase → Predicted temperature anomaly: ~1.09°C
   - 10% decrease → Predicted temperature anomaly: ~-0.06°C
   - 20% increase → Predicted temperature anomaly: ~1.66°C
   - 20% decrease → Predicted temperature anomaly: ~-0.63°C

## 🪝 **Key Insights**

- **Strong Correlation:**  
  Both Pearson (≈0.9554) and Spearman (≈0.9379) correlations confirm a robust linear and monotonic relationship between CO₂ concentrations and temperature anomalies.

- **Moderate Temperature Increase:**  
  With a mean of ~0.54°C and a median of ~0.47°C, temperature anomalies have been increasing moderately but steadily over time.

- **Substantial CO₂ Variability:**  
  Despite a mean CO₂ concentration of ~180.72 ppm, the higher median (~313.84 ppm) and large variance (~32,600) reveal significant fluctuations and a rapid upward trend in atmospheric CO₂.

- **Divergent Trends:**  
  The temperature trend slope is ~0.03°C per year compared to a much steeper CO₂ trend slope of ~0.32 ppm per year. This divergence suggests that while temperature increases are gradual, the accumulation of greenhouse gases is accelerating.

- **Lagged Effects Dominated by Current CO₂ Levels:**  
  Regression models indicate that current CO₂ levels (coefficient ≈0.3245, p < 0.05) predominantly drive temperature changes, with previous years' emissions playing a secondary role.

- **Sensitivity Highlighted by What-If Scenarios:**  
  Simulations reveal that even modest changes in CO₂ levels can have significant impacts on temperature anomalies. For instance, a 10% CO₂ increase raises the temperature anomaly to ~1.09°C, while a 20% increase pushes it to ~1.66°C.



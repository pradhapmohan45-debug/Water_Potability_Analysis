# Water_Potability_Analysis
Water Potability Analysis using Python – Exploratory Data Analysis (EDA) and visualizations to understand factors affecting water safety.
## Insights & Summary

1. **Target Analysis**  
   - 61% of water samples are non-potable, 39% are potable.  
   - Slight class imbalance observed.  

2. **Feature Analysis**  
   - Potable water tends to have slightly higher chloramines and pH closer to neutral.  
   - Most other features show small differences between classes.  

3. **Correlation Insights**  
   - Chloramines have a weak positive correlation with potability.  
   - Other features show very weak correlation, indicating multiple factors influence water safety.  

4. **Visual Insights**  
   - **Countplot:** Shows counts of potable vs. non-potable water.  
   - **Lineplot:** Trends of average feature values for potable vs. non-potable water.  
   - **Histplot:** Distribution of chloramines by potability.  
   - **Scatterplot:** Chloramines vs. pH by potability.  

5. **Conclusion**  
   - Water safety depends on a combination of features rather than a single parameter.  
   - Chloramines and pH are slightly more indicative of potability.  
   - Dataset insights can guide future predictive modeling for classifying potable water.

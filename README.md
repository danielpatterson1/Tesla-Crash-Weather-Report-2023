# 🚗 Tesla Crash Weather Analysis (2023)

### 📊 Overview

This project analyzes Tesla-involved fatal crashes using 2023 National Highway Traffic Safety Administration FARS data, focusing on how weather conditions impact crash involvement. The goal is to identify patterns in risk exposure and highlight where Tesla’s crash distribution diverges from national trends.

### 🎯 Objective

Evaluate Tesla’s involvement in fatal crashes across different weather conditions
Compare Tesla crash patterns to national averages
Identify potential environmental risk factors affecting performance

### 📁 Dataset

Source: National Highway Traffic Safety Administration Fatality Analysis Reporting System (FARS) 2023
Data includes:
Crash-level records
Vehicle identification (including Tesla)
Weather conditions
Geographic information

### 🛠️ Methodology

Identified Tesla vehicles using VIN decoding + manufacturer fields
Aggregated crashes at the event level
Standardized weather categories (Clear, Rain, Snow, etc.)
Compared Tesla vs national crash shares
Conducted statistical testing (Chi-square, Fisher’s Exact, Odds Ratio)
Built visualizations using R (ggplot2, plotly)

### 🔍 Key Insights

- Rain is the only condition where Tesla is overrepresented
- Tesla involvement in clear weather aligns with national averages
- Lower involvement in snow, fog, and cloudy conditions
- Crashes are heavily concentrated in high-adoption states (especially California)
- Rain vs Clear odds ratio: 1.28, indicating higher relative involvement in rain
- Important Context:
This analysis does not measure fault or causation
Results reflect proportional involvement, not risk per mile driven
Findings highlight patterns, not definitive conclusions

### 📌 Key Takeaway

While Tesla crash patterns generally mirror national trends, rainy conditions stand out as a potential risk environment, suggesting an area for further monitoring and technical improvement in perception systems.

### 🚀 Future Improvements
Incorporate newer datasets (2024+)
Normalize by vehicle miles traveled
Expand comparison to other EV manufacturers
Deeper modeling on environmental + geographic interaction effects

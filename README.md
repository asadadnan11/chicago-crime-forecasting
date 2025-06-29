# Chicago Crime Forecasting Project

This project develops a comprehensive crime forecasting framework for Chicago using advanced time series methodologies applied to 23 years of historical data (2001–2023) from the [Chicago Data Portal](https://catalog.data.gov/dataset/crimes-2001-to-present).

---

## Project Overview
- **Objective:** Develop and evaluate multiple time series forecasting models using ensemble techniques to improve crime prediction accuracy and inform strategic planning.
- **Dataset:** Comprehensive analysis of 7M+ crime incidents from Chicago (2001–2023), with deep-dive focus on 1.75M theft and 1.51M battery cases representing Chicago's highest-volume offenses
- **Methodological Focus:** Multi-model ensemble approach combining traditional time series analysis with advanced neural network architectures
- **Strategic Goal:** Deliver actionable predictive intelligence to law enforcement leadership, municipal policymakers, and community safety stakeholders for evidence-based decision making.

---

## Advanced Modeling Framework
1. **Regression Model** - Quadratic trend with seasonal decomposition for long-term pattern detection
2. **Exponential Smoothing (ETS)** - Adaptive weighting for recent trend prioritization
3. **Auto ARIMA** - Automated parameter selection with seasonal differencing
4. **Neural Network (NNAR)** - Non-linear pattern recognition with 11-lag architecture
5. **Seasonal Naïve Baseline** - Benchmark model for performance validation
6. **Ensemble Methods** - Multi-model combination strategies:
   - Simple averaging for stability
   - Trimmed mean for outlier robustness  
   - **Regression-based weighting** for optimal model combination

---

## Key Findings
- **Dramatic 50% decline** in theft and battery arrests over 23-year period, indicating significant long-term crime reduction trends
- **COVID-19 anomaly detection** - Models successfully identified and quantified pandemic-related crime pattern disruptions
- **Robust seasonal intelligence** - Consistent 15-20% crime spikes during summer months across all model validations
- **Strong individual model performance**: ETS achieved 12.59% MAPE, demonstrating reliable short-term forecasting capability
- **Superior ensemble methodology**: Trimmed mean approach reached 12.79% MAPE with enhanced stability
- **Strong predictive performance**: **Regression combination model achieved 5.72% MAPE** - substantially improving upon individual model results

---

## Policy Implications & Recommendations
- **Tactical Resource Deployment:** Implement data-driven 25% patrol increase during identified peak periods (June–August), with targeted allocation to high-probability zones
- **Predictive Budget Optimization:** Integrate ETS/ARIMA forecasting models into quarterly resource allocation for community policing and intervention programs
- **Adaptive Crime Prevention:** Deploy monthly regression-combination forecasts for real-time strategy pivots and proactive crime prevention initiatives
- **Community Intelligence Integration:** Synchronize predictive analytics with neighborhood watch programs and community engagement efforts for comprehensive crime prevention
- **Cross-Agency Coordination:** Enable police departments, social services, and municipal planning to align strategies based on forecasted crime patterns

---

## File Structure

```
/chicago-crime-forecasting 
├── chicago-crime.html # Final report with visualizations 
├── chicago-crime.Rmd # R Markdown file with code 
├── final_presentation.pdf # Presentation of key findings 
└── final_report.pdf # Comprehensive report with methodology
```


---

## Limitations
- **Arrest-only focus** may underrepresent total crime incidents (not all crimes result in arrests)
- **Excluded external factors** such as socioeconomic shifts, weather conditions, and policy changes that influence crime patterns
- **Geospatial elements** were excluded in favor of pure time-series approach
- **Model sensitivity** to irregular shocks (e.g., pandemic, economic downturns, policy shifts)

---

## Future Research Directions
- **Spatial Analysis:** Incorporate geographic variables for neighborhood-level forecasting and targeted resource allocation
- **External Variables:** Include socioeconomic indicators, weather data, and demographic factors to enhance model performance  
- **Advanced Methods:** Explore deep learning approaches and additional ensemble techniques for improved pattern detection
- **Model Validation:** Test methodology on other cities to assess generalizability and transferability of findings
- **Real-time Applications:** Investigate implementation of continuous forecasting systems for operational planning

---

## Authors
- **Asad Adnan**
- **Muhammad Ahmad** 
- **Brian Murphy**

---

# 📊 Chicago Crime Forecasting Project

This project analyzes and forecasts crime rates in Chicago using historical data (2001–2023) from the [Chicago Data Portal](https://catalog.data.gov/dataset/crimes-2001-to-present).

---

## 📚 Project Overview
- **Objective:** Forecast monthly arrests for theft and battery using multiple time series models.
- **Dataset:** 7M+ crime records (2001–2023)
- **Focus Crimes:** THEFT and BATTERY
- **Goal:** Improve law enforcement resource allocation and enhance public safety.

---

## 📈 Models Used
1. **Regression Model (Quadratic Trend + Seasonality)**
2. **Exponential Smoothing (ETS)**
3. **Auto ARIMA**
4. **Neural Network (NNAR)**
5. **Seasonal Naïve Model**
6. **Ensemble Models (Simple Average, Trimmed Mean, Regression-Based Combination)**

---

## ⚡️ Key Findings
- **ETS and Trimmed Mean Models** performed best with MAPE of 12.79%.
- **Regression Combination Model** was the most accurate with MAPE of 5.72%.
- **Seasonal Peaks** observed during summer months with notable drops during winter.

---

## 🎯 Policy Implications
- **Increase patrols by 25%** during peak crime months (June–August).
- Use **ETS/ARIMA models** for quarterly budgeting and resource planning.
- Continuously refine models with updated socio-economic data.

---

## 📂 File Structure

```
/chicago-crime-forecasting 
├── chicago-crime.html # Final report with visualizations 
├── chicago-crime.Rmd # R Markdown file with code 
├── final_presentation.pdf # Presentation of key findings 
└── final_report.pdf # Comprehensive report with methodology
```


---

## 🔍 Future Enhancements
- Incorporate geospatial analysis to target high-crime zones.
- Add socioeconomic and weather variables for better predictive performance.
- Explore deep learning models for capturing complex trends.

---

## 👨‍💻 Authors
- **Asad Adnan**

---

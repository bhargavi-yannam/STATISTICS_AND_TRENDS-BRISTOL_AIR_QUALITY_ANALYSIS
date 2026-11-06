# Bristol Air Quality Data Analysis

An analysis of hourly air quality monitoring data from Bristol, UK, exploring pollutant trends and correlation patterns.

##  Features & Workflow

- **Data Processing:** Cleaned multi-year continuous monitoring data (CSV format) from Kaggle.
- **Pollutant Distribution:** Histogram and statistical summary of Nitrogen Dioxide ($\text{NO}_2$) concentrations.
- **Time-Series Analysis:** Daily mean concentration trends at key monitoring stations (e.g., Parson Street School).
- **Correlation Analysis:** Pearson correlation matrix and heatmaps comparing $\text{NO}_x$, $\text{NO}_2$, $\text{NO}$, $\text{PM}_{10}$, $\text{PM}_{2.5}$, and $\text{O}_3$.

---

## 📊 Key Insights

- **$\text{NO}_2$ Skewness:** Distribution shows a right-skewed pattern with frequent episodic pollution spikes.
- **Nitrogen Oxides:** High linear correlation between $\text{NO}_x$ and $\text{NO}$ ($r = 0.99$), and $\text{NO}_x$ and $\text{NO}_2$ ($r = 0.88$).
- **Particulates:** Strong co-occurrence between $\text{PM}_{10}$ and $\text{PM}_{2.5}$ ($r = 0.96$).
- **Ozone Titration:** Negative correlation between Ozone ($\text{O}_3$) and Nitrogen oxides ($\text{NO}_x$).


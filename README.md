# DATA_MANAGEMENT
# World Bank GDP & Inflation Analysis (2000–2023)

This project analyzes global and regional economic indicators using World Bank data, focusing on GDP per capita and inflation across countries, with a detailed spotlight on Malaysia.

---

## 📁 Project Structure

```
📁 data/
📁 output/
    └── charts/ (all PNG images)
📄 README.md
```

---

##  Tools & Libraries

- Python 3.10+
- Google Colab
- Pandas, Matplotlib, Seaborn, Plotly

---

##  Visualization Summary

This repository includes:
- Global scatter plots comparing GDP per capita and inflation
- ASEAN-10 regional comparison of economic indicators
- Heatmaps showing time-based performance
- Detailed trend and distribution plots for Malaysia

---

##  Chart Previews

### Chart 1 – Global Scatter Plot: GDP vs Inflation (2000–2023)
![Chart 1](output/charts/Global_Scatter_Plot_2000-2023.png)

 This chart shows a moderate negative correlation (**Spearman ρ ≈ –0.40**) between GDP per capita and inflation across countries. The trend is visible but weakened by large inflation volatility in low-income economies.

 
### Chart 2– World Map: GDP per Capita in 2023
![Chart 2](output/charts/GDP_per_Capita_in_2023.png)

 This choropleth map visualizes GDP per capita in 2023. North America, Western Europe, and parts of East Asia show high income levels, while Sub-Saharan Africa and South Asia remain in the low-income range.  

*Map note: The world map is generated using Plotly's built-in geographic base (based on the [Natural Earth](https://www.naturalearthdata.com/) dataset) and visualized with 2023 GDP per capita data from the World Bank. The map is for data visualization purposes only and does not imply any political stance.*

 ***Note: This map is interactive. The image shown here is a static screenshot. To explore the zoomable and draggable version, please run the corresponding cell in the Notebook.***


### Chart 3– ASEAN-10: GDP per Capita (2000–2023)
![Chart 3](output/charts/ASEAN-10_GDP_per_Capita_2000–2023.png)
 This chart illustrates the per capita income growth of ASEAN-10 countries over two decades. Singapore and Brunei remain clear leaders, while Malaysia shows steady mid-to-high income progression.

### Chart 4– ASEAN-10: Inflation Rate (2000–2023)
![Chart 4](output/charts/ASEAN-10_Inflation_Rate_2000–2023.png)
 This chart shows inflation trends across ASEAN-10 countries. Singapore and Malaysia maintain low and stable rates, while Myanmar and Laos experience significant volatility.
 
### Chart 5– ASEAN-10 GDP per Capita Heatmap (2000–2023)
![Chart 5](output/charts/GDP_Heatmap.png)
This heatmap illustrates GDP per capita growth across ASEAN-10. Darker cells indicate higher income levels. Vietnam and the Philippines show visible upward trajectories.

### Chart 6– ASEAN-10 Inflation Rate Heatmap (2000–2023)
![Chart 6](output/charts/Inflation_Heatmap.png)
This heatmap shows inflation rate fluctuations in ASEAN-10. Myanmar and Laos faced multiple high-inflation periods, while Malaysia and Singapore remained relatively stable.

### Chart 7
![Chart 7](output/charts/Malaysia_GDP_vs_Inflation.png)


### Chart 8
![Chart 8](output/charts/Malaysia_Year-on-Year_GDP_per_Capita_Growth_Rate.png)


### Chart 9
![Chart 9](output/charts/Malaysia_GDP_vs_Inflation_(Scaled_Area_Difference).png)


### Chart 10
![Chart 10](output/charts/Inflation_Rate_Distribution_by_Decade.png)



---

##  Summary Insights

- No strong global correlation exists between GDP per capita and inflation levels.
- ASEAN countries are economically diverse, with Malaysia showing strong middle-income performance and controlled inflation.
- Malaysia demonstrates steady growth except during global crises (2009, 2020), with a quick recovery and moderate inflationary trends.

---

##  Data Sources

- [World Bank GDP per capita](https://data.worldbank.org/indicator/NY.GDP.PCAP.CD)
- [World Bank Inflation rate](https://data.worldbank.org/indicator/FP.CPI.TOTL.ZG)

---

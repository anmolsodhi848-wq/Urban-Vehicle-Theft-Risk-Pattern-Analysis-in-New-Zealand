# Urban-Vehicle-Theft-Risk-Pattern-Analysis-in-New-Zealand

## Project Objective

To analyze urban vehicle theft patterns in New Zealand and identify high-risk regions, vulnerable vehicle categories, and seasonal trends to support data-driven decision-making.

## Dataset Source

https://github.com/anmolsodhi848-wq/Urban-Vehicle-Theft-Risk-Pattern-Analysis-in-New-Zealand/blob/main/stolen_vehicles.xlsx


## Key Performance Indicators (KPIs)

1. **Total Vehicles Stolen:** 4,520
2. **Most Affected Region:** Auckland (1,624 thefts)
3. **Most Stolen Brand:** Toyota (716 thefts)
4. **Most Targeted Vehicle Type:** Stationwagon (944 thefts)
5. **Average Vehicle Model Year:** 2005
6. **Most Stolen Color:** Silver (1,252 thefts)
7. **Peak Theft Month:** March (789 thefts)
8. **Lowest Theft Period:** June–September


## Process

**1️. Data Cleaning (Excel)**

  1.1. Removed duplicates and inconsistencies
  1.2. Standardized categorical fields (Region, Vehicle Type, Make, Color)
  1.3. Handled missing/null values
  1.4. Extracted Month and Year from Date
  1.5. Created Model Year bins
  1.6. Ensured proper formatting and data types

**2. Data Visualization & Modeling (Tableau)**

  2.1. Created calculated fields (COUNT, AVG, Model Year Bins)
  2.2. Designed KPI Cards
  2.3. Built Monthly Trend Line (Time-Series Analysis)
  2.4. Developed Geographic Map (Regional Risk Analysis)
  2.5. Created Vehicle Type vs Make Type Bar Chart
  2.6. Built Vehicle Color Distribution Pie Chart
  2.7. Developed Model Year Distribution Histogram
  2.8. Implemented interactive filters (Region, Make, Month, Model Year, Vehicle Type, Color)

**3. Dashboard Design**
  
  3.1. Executive-style layout
  3.3. KPI summary at top
  3.3. Trend and geographic analysis in the middle
  3.4. Detailed breakdown visuals at the bottom
  3.5. Clean, minimal, and decision-focused design


## Dashboard

<img width="1911" height="980" alt="image" src="https://github.com/user-attachments/assets/62ca8022-d4a3-4608-a072-a1ffc085c975" />


## Project Insights

1. **Regional Concentration-** Auckland accounts for the highest theft volume, indicating strong urban-density influence.
2. **Seasonal Trend-** Theft peaks in March and rises again toward year-end, with a noticeable decline during mid-year months.
3. **Vehicle Type Vulnerability-** Stationwagons and saloons dominate theft cases. Luxury vehicles are significantly less targeted.
4. **Brand Exposure-** Toyota vehicles are most frequently stolen, likely due to high market share and resale demand.
5. **Model Year Risk-** Vehicles manufactured between 1995–2010 show higher theft frequency, suggesting weaker security systems in older models.
6. **Color Distribution-** Silver and black vehicles account for a large proportion of thefts, reflecting common vehicle ownership patterns.


## Conclusions
1. Vehicle theft is geographically concentrated in high-density urban regions.
2. Theft patterns show strong seasonal variation.
3. Criminal activity appears volume-driven rather than luxury-driven.
4. Older, standard-model vehicles face higher theft risk.
5. High-availability brands and vehicle types are disproportionately affected.


## Recommendations
 
1. For Law Enforcement
   1.1. Increase patrol deployment in Auckland during peak months.
   1.2. Focus monitoring on high-risk vehicle categories (older Toyota station wagons).
   1.3. Use historical trend data for predictive deployment strategies.

2. For Insurance Companies
   2.1. Implement risk-adjusted premiums based on region, model year, and vehicle type.
   2.2. Offer incentives for anti-theft technology installations.

3. For Vehicle Owners
   3.1. Install immobilizers and GPS tracking systems.
   3.2. Prioritize secure parking in high-risk regions and months.
   3.3. Take additional precautions for pre-2010 vehicles.


## Future Scope
1. Develop predictive theft risk models using machine learning.
2. Integrate population density data for risk scoring.
3. Apply clustering techniques to identify theft behavior patterns.
4. Build time-series forecasting models for future trend prediction.
5. Incorporate external factors such as weather, economic indicators, and public holidays.

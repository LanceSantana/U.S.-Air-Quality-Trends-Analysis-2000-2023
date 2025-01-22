# US Air Pollution Report

## About

This project investigates air pollution trends in the United States from 2000 to 2023, focusing on key pollutants: **ozone (O₃)**, **carbon monoxide (CO)**, **sulfur dioxide (SO₂)**, and **nitrogen dioxide (NO₂)**. By analyzing historical data, we identify the best and worst air quality trends across various regions and explore how these pollutants have changed over time. The findings provide insights into the effectiveness of environmental policies and suggest areas for further improvement.

---

## Key Question/Objective

**"Which areas in the United States have shown the best and worst air quality trends for ozone, carbon monoxide, sulfur dioxide, and nitrogen dioxide, and how have these pollutants changed over time in these regions?"**

---

## Team

- **Ivan Avila**
- **Lance Santana**
- **Gustavo Perez**
- **Cole Hammes**

---

## Summary

This project analyzes the **U.S. Pollution Data (2000–2023)** dataset by Gassan Yacteen (available on Kaggle). Each team member investigated a specific pollutant, conducting a detailed analysis to uncover trends, outliers, and patterns. We highlight the most and least polluted regions for each pollutant and evaluate how air quality has evolved across the country. This collaborative effort demonstrates the power of data-driven approaches to tackling environmental challenges.

### Findings:

- **Population Density and Economic Activity:**  
  States with higher population densities and economies reliant on fossil fuel production exhibited worse air quality trends.
  
- **Overall Improvement in Air Quality:**  
  All pollutants showed significant decreases over time, reflecting the impact of stricter environmental regulations and a shift toward cleaner energy sources.

- **Urban vs. Rural Areas:**  
  Urban areas consistently showed higher pollutant concentrations, but targeted initiatives have led to notable improvements in air quality.

---

## Analyses

### **Lance Santana: Ozone Analysis**
- Investigated extreme ozone pollution levels in California and identified potential data collection issues (e.g., high frequency of zero ozone samples).
- Highlighted areas with the highest and lowest recorded ozone levels.
- Examined trends in ozone distribution and state averages, comparing California, Tennessee, and Alaska.

### **Cole Hammes: Sulfur Dioxide Analysis**
- Mapped states with the highest average sulfur dioxide levels over the entire dataset and the last 5 years.
- Observed a significant shift in sulfur dioxide levels due to stricter climate regulations and a move away from coal-burning.
- Analyzed top cities contributing to sulfur pollution within the most affected states.

### **Gustavo Perez: Carbon Monoxide Analysis**
- Identified cities with the highest and lowest carbon monoxide levels in 2023.
- Analyzed trends in CO levels over time in major cities like Los Angeles, Phoenix, and Lompoc.
- Compared carbon monoxide trends to other pollutants in these cities.

### **Ivan Avila: Nitrogen Dioxide Analysis**
- Provided summary statistics for nitrogen dioxide levels and examined trends across the U.S.
- Highlighted the role of environmental policies, such as the Clean Air Act, in reducing NO₂ levels.
- Identified outliers in NO₂ data and their implications for specific states like California.

---

## Project Conclusion

### Key Insights:
1. **Best Areas for Air Quality:**  
   - Rural, low-population states like Alaska consistently showed the lowest pollution levels.  

2. **Worst Areas for Air Quality:**  
   - Highly urbanized states with significant industrial activity, such as California, New York, and Pennsylvania, experienced the highest pollution levels historically.

3. **Progress Over Time:**  
   - Stricter regulations, clean energy adoption, and advancements in emission control technologies have significantly improved air quality nationwide.  

### Recommendations:
- For individuals seeking to minimize exposure to air pollution, moving to regions with low population densities and strong clean energy policies may be beneficial.
- Continued investment in renewable energy and enforcement of emission standards are crucial to sustaining and accelerating these improvements.

---

## Required Libraries/Packages

To run the analysis, ensure the following R libraries are installed:
- **ggplot2**  
- **maps**  
- **tidyverse**

Install these libraries using the following command:
```r
install.packages(c("ggplot2", "maps", "tidyverse"))

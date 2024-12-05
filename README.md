# Wildfire Analysis: New Haven

## Overview
This Jupyter Notebook analyzes the impact of wildfire activity on New Haven, Connecticut, focusing on:
1. Air quality trends using PM2.5 data.
2. Economic disruptions across industries, with a particular emphasis on manufacturing and state government interventions.
3. Statistical modeling to quantify relationships between wildfire activity, air quality, and economic outcomes.

The analysis integrates data from multiple sources to produce actionable insights for policymakers and stakeholders in New Haven.

---

## Key Features
- **Wildfire Impact Score Calculation**: Combines PM2.5 levels, wildfire size, and proximity to quantify the effects of wildfire activity on New Haven.
- **Air Quality Analysis**: Visualizations and metrics to explore PM2.5 trends during high wildfire activity periods.
- **Economic Impact Assessment**: Linear regression models to assess disruptions in industry facilities ("Units") and total wages across sectors.
- **Actionable Insights**: Recommendations for fire-resistant infrastructure and proactive state measures based on findings.

---

## Data Sources
The notebook integrates datasets from the following sources:
1. **Wildfire Data** ([ScienceBase](https://www.sciencebase.gov/catalog/item/61aa537dd34eb622f699df81)):
   - Covers wildfire incidents within 650 miles of New Haven, including size and proximity data.
2. **Air Index Data** ([EPA AQS API](https://www.epa.gov/aqs)):
   - PM2.5 concentration data to assess smoke exposure and air quality trends.
3. **Economic Data** ([Connecticut Department of Labor](https://www1.ctdol.state.ct.us/lmi/202/202_annualaverage.asp)):
   - Annual average employment, wages, and facility counts by industry.

---

## Notebook Structure

### 1. **Introduction**
- Objectives of the analysis.
- Motivation for studying the impact of wildfire activity on New Haven.

### 2. **Data Loading and Preprocessing**
- Loading datasets (`fire_data`, `air_index`, `TownEmp`).
- Cleaning and preparing data for analysis.

### 3. **Wildfire Impact Score**
- Calculation of a composite metric combining PM2.5 levels, wildfire size, and proximity.

### 4. **Air Quality Analysis**
- Visualizations and statistics for PM2.5 trends over time.

### 5. **Economic Analysis**
- Regression models assessing:
  - Changes in facility counts ("Units") by industry.
  - Impact on total wages in key sectors like manufacturing and wholesale trade.

### 6. **Findings**
- Correlation between wildfire activity and air quality.
- Sector-specific economic disruptions identified through statistical significance tests.

### 7. **Recommendations**
- Infrastructure improvements for manufacturing facilities.
- State-level measures to proactively manage wildfire risks and reduce economic impacts.

---

## How to Use This Notebook

### Requirements
- **Python 3.8+**
- Jupyter Notebook or Jupyter Lab
- Required libraries: `pandas`, `matplotlib`, `statsmodels`, `tabulate`

### Setup
1. Clone this repository or download the notebook file.
2. Ensure the required datasets are available in the appropriate directory:
   - `fire_data.csv`
   - `air_index.csv`
   - `TownEmp` files (2000–2023)
3. Install dependencies:
   ```bash
   pip install pandas matplotlib statsmodels tabulate```

### Running the Notebook
Open the notebook in Jupyter and execute cells sequentially to:
1. Recreate the wildfire impact score.
2. Visualize air quality trends.
3. Conduct regression analysis on economic indicators.
4. Generate recommendations based on findings.

---

## Results Summary
### Key Findings:
- **Air Quality:** PM2.5 levels correlate strongly with wildfire proximity, peaking during summer months.
- **Economic Impact:** Manufacturing experienced significant disruptions, with a reduction of 8.5 facilities during high-impact years.
- **State Government Spending:** Increased by $51 million in response to wildfire-related challenges.

### Recommendations:
1. **Enhance Fire Protection:** Equip manufacturing facilities with fire-resistant infrastructure.
2. **Proactive State Measures:** Invest in wildfire prevention and emergency management.
3. **Monitoring Systems:** Deploy real-time air quality alerts for residents and industries.

---

## Future Directions
1. Incorporate daily resolution data for finer trend analysis.
2. Extend the analysis to explore additional sectors or geographic regions.
3. Integrate predictive models for estimating future economic impacts.

---

## License
This project is licensed under the MIT License.

---

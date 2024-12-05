# Dataset Descriptions

## 1. **TownEmp Dataset**
**Source:** [Connecticut Department of Labor - Economy at a Glance](https://www1.ctdol.state.ct.us/lmi/202/202_annualaverage.asp)

### Description
The TownEmp dataset provides annual economic data for towns in Connecticut, focusing on industry-specific metrics. It is available for the years **2000 to 2023**, with each file representing data for a specific year.

### Structure
- **Town:** Name of the town (e.g., New Haven).
- **NAICS Code:** Industry classification code based on the North American Industry Classification System.
- **Industry Name:** Descriptive name of the industry (e.g., Manufacturing, Construction).
- **Units:** Number of facilities, sites, or establishments in the industry.
- **Annual Average Employment:** Average number of people employed in the industry for the year.
- **Total Annual Wages:** Total wages paid by the industry in the year, often formatted as currency (e.g., `$1,000,000`).

### Notes
- Files are available in `.xls` format.
- Annual data from **2000 to 2023** are consistent in structure, allowing for longitudinal analysis.
- Primary focus is on employment and wage trends in industries across Connecticut towns.

---

## 2. **Fire Data**
**Source:** [ScienceBase - Wildfires Dataset](https://www.sciencebase.gov/catalog/item/61aa537dd34eb622f699df81)

### Description
The fire data provides detailed information on wildfire incidents within **650 miles of New Haven**. This dataset captures key metrics about wildfires, enabling analyses of their size, proximity, and potential impact on New Haven's air quality.

### Structure
- **Fire Name:** Name of the wildfire.
- **Year:** The year the wildfire occurred.
- **Date:** The start date of the wildfire.
- **Latitude:** Geographic latitude of the wildfire location.
- **Longitude:** Geographic longitude of the wildfire location.
- **Size (Acres):** Total area affected by the wildfire in acres.
- **Distance (Miles):** Distance of the wildfire from New Haven, calculated in miles.

### Notes
- Data is filtered to include wildfires within a 650-mile radius of New Haven.
- Useful for correlating wildfire activity with air quality metrics in New Haven.

---

## 3. **Air Index Data**
**Source:** [EPA - Air Quality System (AQS)](https://www.epa.gov/aqs)

### Description
This dataset contains air quality data specific to New Haven, focusing on particulate matter (PM2.5), which is a key indicator of smoke from wildfires.

### Structure
- **Date:** Date of the air quality measurement.
- **Year:** Year of the air quality measurement.
- **Mean PM2.5:** Average PM2.5 concentration measured in micrograms per cubic meter.
- **Max PM2.5:** Maximum PM2.5 concentration recorded for the day.
- **Min PM2.5:** Minimum PM2.5 concentration recorded for the day.

### Notes
- Data was sourced from New Haven's EPA monitoring station, ensuring accurate local air quality measurements.
- The dataset is particularly relevant for correlating wildfire proximity and air quality deterioration.

---

## Combined Dataset Potential
By integrating these datasets, the analysis links wildfire activity (fire data) with its environmental consequences (air index data) and subsequent economic impacts (TownEmp dataset). The consistent structure and high data quality across these sources enable comprehensive longitudinal and cross-sectional analyses.

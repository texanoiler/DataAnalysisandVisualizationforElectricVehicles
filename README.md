# DataAnalysisandVisualizationforElectricVehicles

## 1. Project Overview
This project analyzes the Washington State Electric Vehicle Population dataset to explore trends in EV adoption, popular makes and models, geographic distribution, and policy-related factors such as CAFV eligibility. Using Python for data cleaning, visualization, and mapping, the project provides insights into the growth and distribution of electric vehicles across the state.

---

## 2. Dataset
- **Source:** Washington State Department of Licensing - Electric Vehicle Population Data
- **Link:** *https://catalog.data.gov/dataset/electric-vehicle-population-data*
- **Link to Download GeoJSON:** *https://geo.wa.gov/datasets/12712f465fc44fb58328c6e0255ca27e_11/explore?location=47.200759%2C-120.817600%2C7.08*
- **Key Features:**
  - Vehicle make, model, and model year
  - Electric range
  - Geographicl location (city, county, census tract)
  - Clean Alternative Fuel Vehicle (CAFV) eligibility
  - Electric utility provider

 ---

 ## 3. Tools & Libraries Used
 - **Data and Numberical Operations:** Pandas, NumPy
 - **Visualization:** Matplotlib, Seaborn
 - **Geospatial Analysis:** Geopandas, Folium
 - **Environment:** Jupyter Notebook

---

## 4. Analysis & Methodology
1. **Data Collection & Description:** Imported the dataset and examined the basic data structure.
2. **Data Cleaning & Preprocessing:** Handled missing values. and extracted coordinates from geometry fields.
3. **Exploratory Data Analysis:** Generated summary statistics, trends, and distribution plots.
4. **Geographic Visualization:** Created choropleth maps and heat maps to illustrate spatial adoption patterns.
5. **CAFV Eligibility Analysis:** Investigated the distribution and possible reasons behind "Eligibility Unknown" cases.
6. **Key Insights & Conclusions:** Summarized major findings and their implications.

---

## 5. Key Findings
- 2023 EV models dominate registrations in Washington.
- Tesla, particularly the Model Y, is the most popular make/model.
- King County and Seattle lead in EV adoption.
- Majority of CAFV eligibility is "unknown" due to newer models and incomplete data.
- Choropleth maps and heatmaps reveal adoption concentration in urban areas.

---

## 6. How to Run the Project
Follow these steps to run the analysis on your local machine:

1. **Clone the repository**
   ```bash
   git clone https://github.com/texanoiler/DataAnalysisandVisualizationforElectricVehicles.git
   cd 

2. 

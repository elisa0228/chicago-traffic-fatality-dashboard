# Chicago Traffic Fatality Dashboard

### Overview

This project presents an interactive data visualisation dashboard developed using Streamlit to analyse traffic fatality data from the City of Chicago.

The dashboard enables users to explore traffic crash patterns, identify high-risk locations, investigate trends over time, and understand factors associated with fatal road incidents.

The project demonstrates the application of data science techniques to real-world traffic safety data, combining exploratory analysis, interactive visualisation, and dashboard development.


### Live Demo

View the deployed Streamlit application here:

https://elisa0228-final-individual-app-project-final-app-88zc7a.streamlit.app


### Dashboard Preview
**Overview and Crash Location Map**

The main dashboard page provides an overview of traffic fatalities across Chicago, including interactive filters, summary statistics, and a geographic visualisation of fatal crash locations. Users can dynamically explore fatality patterns by year and month.

<p align="center">
  <img src="dashboard preview/dashboard overview.png" width="1200">
</p>

<p align="center">
  <em>Figure 1: Interactive dashboard overview displaying crash locations, filtering controls, and key fatality statistics.</em>
</p>

---

**Interactive Fatality Analysis**

A range of interactive visualisations were developed to explore traffic fatality trends over time. Users can investigate yearly patterns, monthly distributions, and victim categories through dynamic charts and graphical summaries.

<p align="center">
  <img src="dashboard preview/dashboard charts.png" width="1200">
</p>

<p align="center">
  <em>Figure 2: Interactive visualisations showing fatality trends, victim distributions, and temporal patterns across Chicago.</em>
</p>

---

**Spatial and Victim Analysis**

This section combines spatial and demographic analysis to explore how traffic fatalities vary across Chicago. Users can investigate crash locations geographically while also examining trends across different victim categories.

<p align="center">
  <img src="dashboard preview/dashboard charts .png" width="1200">
</p>

<p align="center">
  <em>Figure 3: Spatial distribution of fatal crash locations alongside victim-type analysis across Chicago.</em>
</p>

---

**Key Insights and Recommendations**

The dashboard concludes with a summary page that consolidates major findings from the analysis, including victim demographics, temporal trends, spatial patterns, and recommendations that may support future road safety initiatives and decision-making.

<p align="center">
  <img src="dashboard preview/dashboard key recap.png" width="1200">
</p>

<p align="center">
  <em>Figure 4: Key insights page summarising major findings, observed trends, and potential road safety recommendations.</em>
</p>

<br>


### Project Objectives

The main objectives of this project were to:

- Analyse traffic fatality trends across Chicago
- Identify geographical crash hotspots
- Investigate temporal patterns by year and month
- Explore different road user categories
- Examine environmental and contextual crash factors
- Support data-driven decision making for road safety improvements
- Create an accessible and user-friendly dashboard


### Dataset

Dataset: Vision Zero Chicago Traffic Fatalities

Source: Chicago Department of Transportation (CDOT)

The dataset contains fatal traffic crash records from 2019–2025 and includes:

- Crash location coordinates
- Date and time of incident
- Victim classification
- Road user type
- Geographic distribution of fatalities

The data was cleaned, transformed, and validated before analysis and dashboard development.


### Key Features

- Interactive geospatial map displaying fatal crash locations across Chicago
- Dynamic filtering by year and month for customised analysis
- Multiple visualisations including bar charts, line charts, pie charts, area charts, and scatter plots
- Victim-type analysis covering pedestrians, drivers, passengers, cyclists, motorcyclists, and scooter users
- Crash hotspot identification through geographic mapping
- Interactive data tables summarising fatality statistics
- Automated insight generation and key findings summary
- Responsive dashboard developed using Streamlit
- Dark-themed user interface designed for accessibility and readability
- Real-time visual updates based on user-selected filters

### Dashboard Workflow

Dataset Acquisition

↓

Data Cleaning & Preprocessing

↓

Exploratory Data Analysis

↓

Feature Engineering

↓

Dashboard Development

↓

Testing & Validation

↓

Deployment


### Technologies Used

- Python
- Streamlit
- Pandas
- Plotly
- NumPy
- Visual Studio Code
- Git & GitHub


### Key Findings

- A total of 846 traffic fatalities were recorded between 2019 and 2025.
- Pedestrians represented the largest proportion of fatalities, closely followed by drivers.
- Fatalities peaked during July and September, indicating seasonal variation in crash occurrences.
- Fatal crashes were heavily concentrated within central and high-traffic areas of Chicago.
- The highest number of fatalities occurred during evening and early morning hours.
- Significant year-to-year variation was observed, with 2021 and 2022 recording the highest fatality counts.
- Geographic analysis identified several recurring crash hotspots, suggesting locations that may benefit from targeted road safety interventions.
- Temporal analysis revealed consistent monthly patterns that can support future traffic safety planning and policy decisions.


### Skills Demonstrated

- Python
- Pandas
- NumPy
- Plotly
- Streamlit
- Data Cleaning
- Exploratory Data Analysis (EDA)
- Geospatial Analysis
- Dashboard Development
- Data Visualisation
- Statistical Analysis
- Git & GitHub


### Testing

The application was tested using a structured testing process covering:

- Data filtering functionality
- Chart rendering
- Interactive visualisations
- Export features
- Geographic map navigation

All core test cases passed successfully.


### Project Impact

This dashboard transforms raw traffic fatality records into an interactive decision-support tool, enabling users to identify trends, explore crash hotspots, and understand factors associated with fatal road incidents. The project demonstrates how data science and visual analytics can support evidence-based road safety initiatives.

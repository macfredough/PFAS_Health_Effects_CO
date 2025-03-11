PFAS Health Effects in Colorado

Overview

This project explores the environmental and public health impacts related to Per- and Polyfluoroalkyl Substances (PFAS) contamination in Colorado. The analysis integrates environmental data on PFAS contamination levels with comprehensive public health data to assess potential health risks associated with water quality.

Project Goals

Identify contamination hotspots: Pinpoint areas with notably elevated PFAS contamination.

Analyze contamination trends: Examine changes in PFAS contamination over recent years.

Assess health impacts: Investigate correlations between PFAS exposure and public health outcomes.

Data Sources (*Note some sources had to be zipped to upload to GitHub)

PFAS Contamination Data

Data obtained from the Colorado Department of Public Health and Environment (CDPHE) - PFAS Data includes comprehensive water testing results from public water systems, covering 2021 to the present -

PFAS_Dataset1: [Click here](https://drive.google.com/file/d/1bbtjOixYKWTonkgO-2zEAQI6Tgf41Q8T/view)

PFAS_Dataset2: [Click here](https://cohealthviz.dphe.state.co.us/t/EnvironmentalEpidemiologyPublic/views/PFAS_results_DRAFT/SamplingSummary?%3AshowAppBanner=false&%3Adisplay_count=n&%3AshowVizHome=n&%3Aorigin=viz_share_link&%3AisGuestRedirectFromVizportal=y&%3Aembed=y)

Health Outcome Data

Colorado Mortality Data (1980-2023) sourced from the Colorado Center for Health & Environmental Data, providing mortality rates by cause across counties.

Colorado Chronic Disease Data (2018-2022) from the CDC's PLACES dataset, capturing prevalence rates of various chronic conditions. Data source: CDC PLACES - 500 Cities & Places - [Click here](https://data.cdc.gov/browse?category=500+Cities+%26+Places&q=places&sortBy=relevance&tags=places&pageSize=20)

US Counnty shape file for Geographic mapping can be found at [Click here](https://www.census.gov/cgi-bin/geo/shapefiles/index.php?year=2024&layergroup=Counties+%28and+equivalent%29)

Methods

Data Cleaning and Preparation

Removal of duplicates and irrelevant data

Handling missing values by imputation or exclusion

Standardization and consistency checks on data formatting

Exploratory Data Analysis (EDA)

Generation of descriptive statistics and visualization for PFAS levels

Geospatial analysis to detect contamination hotspots

Temporal trend analysis of PFAS levels

Health Risk Score Calculation

Computed health risk scores based on chronic disease prevalence across counties

Correlated health risk scores with PFAS contamination levels to identify potential associations

Correlation Analysis

Pearson correlation used to assess relationships between PFAS contamination and health risk scores

Visual analysis via scatter plots and box plots to illustrate health disparities related to PFAS exposure

Key Findings

Higher average health risk scores observed in counties with high PFAS contamination levels (mean: 0.98) versus low-PFAS counties (mean: 0.76).

Pearson correlation indicated a statistically significant (p = 0.032) weak-to-moderate positive correlation (r=0.331) between PFAS levels and health risks, necessitating further longitudinal and detailed analysis to determine causality.

Chronic disease incidence such as diabetes and hypertension, along with population density, significantly influenced health risk scores, whereas direct contributions from PFAS levels were minimal in predictive modeling.

Conclusion and Recommendations

Current data suggests a moderate positive correlation between PFAS contamination and elevated health risks. However, a definitive causal relationship requires additional longitudinal studies with detailed exposure histories, socioeconomic context, and health tracking.

Recommended Next Steps:

Longitudinal analysis including individual-level health outcomes.

Consideration of socioeconomic factors and chronic health conditions.

Increased frequency and granularity of PFAS testing and data collection.

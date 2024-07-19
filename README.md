## EV Charging Station Analysis and Visualization
This repository contains a Jupyter Notebook that performs an analysis of electric vehicle (EV) ownership and charging station data. The analysis identifies potential areas for new EV charging stations in Ireland, focusing on factors such as high concentration of electric vehicles, areas with limited existing charging infrastructure, and high population density. The notebook also includes visualizations to present the findings.

All of the data was sourced from data.gov.ie

Contents
* SSE_ABHISHEK_ANGNE.ipynb: The main Jupyter Notebook containing the data extraction, transformation, analysis, and visualization.
* EV_Ownership_sex.csv: Dataset containing EV ownership information broken down by sex and age group.
* EV_ownership_county.csv: Dataset containing EV ownership information by county.
* Population_IRL.csv: Dataset containing population data for Ireland.
* Cork_EV_chargers.csv: Dataset containing information about EV chargers in Cork.
* FingalCounty_EV_chargers.csv: Dataset containing information about EV chargers in Fingal County.
* SouthDublin_EV_chargers.csv: Dataset containing information about EV chargers in South Dublin.

* Getting Started
* Prerequisites
To run the notebook, you need to have the following installed:

Python 3.x, Jupyter Notebook on Colab/local, Pandas, Matplotlib

* Run the cells in the notebook to perform the analysis and visualize the results.

Data Sources
* EV_Ownership_sex.csv: Contains EV ownership data by sex and age group.
* EV_ownership_county.csv: Contains EV ownership data by county.
* Population_IRL.csv: Contains population data for Ireland.
* Cork_EV_chargers.csv, FingalCounty_EV_chargers.csv, SouthDublin_EV_chargers.csv: Contain information about existing EV chargers in Cork, Fingal County, and South Dublin respectively.
* Analysis

The notebook performs the following steps:

* Data Extraction and Loading:
* Load datasets from CSV files.
* Data Cleaning and Preparation:
* Standardize column names.
* Handle duplicates and missing values.
* Data Transformation and Analysis:
* Identify potential locations for new EV charging stations based on:
* High concentration of electric vehicles.
* Areas with limited existing charging infrastructure.
* High population density.
* Visualization:
* Create visualizations to present the findings

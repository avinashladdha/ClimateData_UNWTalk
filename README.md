# Data for Climate Analytics: Companion Repository

This repository contains code examples, tutorials, and a mini-project supporting the "Data for Climate Analytics" presentation. It is designed for a semi-technical audience to get hands-on experience with climate data retrieval, cleaning, and analysis.

## Overview

The repository is structured as follows:

- `notebooks/`: Step-by-step tutorials on fetching and cleaning climate data.
  - `01_data_retrieval_worldclim.ipynb`: How to fetch and visualize GeoTIFF data from WorldClim.
  - `02_data_retrieval_netcdf.ipynb`: Working with multidimensional NetCDF data (e.g., from NOAA).
  - `03_data_cleaning_methods.ipynb`: Techniques for handling missing values (imputation) and detecting outliers.
- `mini_project/`: A self-contained machine learning analysis.
  - `temperature_forecast.ipynb`: A time-series forecasting project using ARIMA to predict global temperature anomalies using NASA GISTEMP data.
- `requirements.txt`: List of Python dependencies.

## Prerequisites

To run these notebooks, you need Python installed. We recommend using Anaconda or a virtual environment.

### Installation

1. Clone this repository.
2. Install the required packages:

```bash
pip install -r requirements.txt
```

## Getting Started

Start Jupyter Lab or Jupyter Notebook:

```bash
jupyter lab
```

Then navigate to the `notebooks/` directory to start the tutorials.

## Themes Covered

This code aligns with the presentation topics:
- **Data Formats**: GeoTIFF, NetCDF.
- **Data Cleaning**: Imputation (Linear, Seasonal), Outlier Detection (Z-Score), Stationarity checks (ADF).
- **Analysis**: Time-series forecasting.

## Data Sources

- **WorldClim**: Global climate layers (GeoTIFF).
- **NASA GISTEMP**: Global Surface Temperature Analysis.
- **NOAA**: Sample NetCDF datasets.

---
*Created by Avinash Laddha*

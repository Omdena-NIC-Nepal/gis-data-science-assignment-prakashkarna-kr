# Climate Data Analysis for Nepal

## Overview

This project analyzes climate data for Nepal, focusing on temperature projections for the years 2020 and 2050. The analysis includes data processing, exploratory data analysis (EDA), and visualization using Python and GIS tools. The primary objective is to understand climate trends and their potential impact on Nepal’s environment and society.

## Objectives

- Process and analyze climate projection data.
- Perform exploratory data analysis (EDA) to identify patterns and trends.
- Visualize spatial and temporal variations in temperature.
- Derive insights into climate change impacts on Nepal.

## Data Sources

The project uses raster datasets containing climate projections. Link to the data: https://github.com/Desmondonam/Nepal_Climate_change. These datasets include:

- Temperature and precipitations projections for 2020 and 2050.
- GIS shapefiles to represent Nepal’s geographical boundaries.

## Environment Setup

To set up the Python environment, follow these steps:

1. Clone the repository:

   ```bash
   git clone <repository_url>
   cd <repository_folder>
   ```

2. Create a virtual environment (optional but recommended):
```bash
   # For macOS and Linux
   python3 -m venv venv
   source venv/bin/activate

   # For Windows
   python -m venv venv
   venv\Scripts\activate
```

3. Install required dependencies:

   ```bash
   !pip install -r requirements.txt
   ```


## Data Preprocessing

- Loaded GIS shapefiles for Nepal’s boundary.
- Processed raster data for climate projections.
- Extracted temperature data for different time periods.
- Cleaned and structured data for visualization.

## Visualizations and Interpretations

### 1. Temperature Distribution Maps

- Generated heatmaps of temperature distributions for 2020 and 2050.
- Show differences in spatial temperature variations over time.

### 2. Time Series Analysis

- Created plots showing temperature trends across Nepal.
- Identified regions experiencing significant changes.

### 3. Comparative Analysis

- Compared temperature variations between the two time periods.
- Highlighted key areas of concern.

## Key Findings

- The analysis indicates a rise in temperature across Nepal by 2050.
- Certain regions are more vulnerable to temperature increases.
- The spatial distribution of temperature changes suggests potential environmental impacts, such as glacial melting and agricultural shifts.

## Dependencies (requirements.txt)

```
numpy
pandas
geopandas
matplotlib
seaborn
rasterio
jupyter
notebook
folium
fiona
```

## Conclusion

This project provides insights into Nepal’s climate projections.

---
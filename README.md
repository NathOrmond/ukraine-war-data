# Ukraine War Data Analysis Project

## Overview
This project analyzes data from the Ukraine Support Tracker, which monitors and quantifies international aid to Ukraine following Russia's invasion. The analysis focuses on understanding patterns, trends, and distributions of military, financial, and humanitarian aid provided by various countries and organizations.

## Data Source
The data used in this project comes from the Kiel Institute for the World Economy's Ukraine Support Tracker:
- Source: [https://www.ifw-kiel.de/publications/ukraine-support-tracker-data-20758/](https://www.ifw-kiel.de/publications/ukraine-support-tracker-data-20758/)
- Authors: Antezza, A., Bushnell, K., Dyussimbinov, Y., Frank, A., Frank, P., Franz, L., Kharitonov, I., Kumar, B., Rebinskaya, E., Trebesch, C., Schramm, S., Weiser, L., Schade, C.
- Publication Date: 02/2025

**Note:** This dataset tracks government-to-government commitments of military, financial, and humanitarian aid to Ukraine since January 24, 2022. The dataset primarily covers G7 and European Union member countries, with some additional data on non-bilateral aid.

⚠️ **Important:** The data may be out of date. This README was created on March 2, 2025, and the dataset may not reflect developments after its publication date of February 2025.

## Project Structure
```
ukraine-war-data/
│
├── data/
│   ├── raw/             # Original xlsx files from the Ukraine Support Tracker
│   └── processed/       # Cleaned and transformed data
│
├── scripts/
│   ├── 01_import.Rmd    # Data import and cleaning
│   ├── 02_explore.Rmd   # Exploratory data analysis
│   └── 03_analyze.Rmd   # In-depth analysis
│
├── output/
│   ├── figures/         # Generated visualizations
│   └── tables/          # Summary tables and results
│
└── docs/                # Documentation and notes
```

## Getting Started
1. Clone this repository
2. Download the Ukraine Support Tracker data from the URL above and place it in the `data/raw/` directory
3. Open the R project and run the notebooks in sequence

## Dependencies
- R (version 4.1.0 or higher)
- Key packages: tidyverse, readxl, ggplot2, dplyr, here

## License
Please note that the original dataset has its own terms of use. Refer to the Kiel Institute's website for details on citing and using their data in publications.

## Citation
When using results from this analysis, please cite both this project and the original data source:

```
Antezza, A., Bushnell, K., Dyussimbinov, Y., Frank, A., Frank, P., Franz, L., Kharitonov, I., Kumar, B., Rebinskaya, E., Trebesch, C., Schramm, S., Weiser, L., Schade, C. (2025). Ukraine Support Tracker Data. Kiel Institute for the World Economy. https://www.ifw-kiel.de/publications/ukraine-support-tracker-data-20758/
```

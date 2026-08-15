# Caritas Westminster Dissertation Project

## Research Question

To what extent are social action initiatives aligned with patterns of socioeconomic deprivation across the Diocese of Westminster?

## Project Overview

This repository contains the Python/Jupyter analytical code developed for my MSc Business Analytics dissertation project with Caritas Westminster.

The project examines the geographical relationship between recorded social-action activity and socioeconomic deprivation across the Diocese of Westminster.

Recorded APFR social-action activity is used as the observable measure of provision. Missing or unmatched records are not treated as zero activity, and the analysis is interpreted as exploratory evidence rather than a definitive measure of total social-action provision.

## Repository Contents

### 01_business_analysis.ipynb

The main analytical notebook for the dissertation.

It contains the primary data preparation, exploratory and descriptive analysis, annual comparison, statistical analysis and deanery-level alignment analysis used to investigate the research question.

### 02_spatial_maps_dashboard.ipynb

The supporting spatial-analysis and output-generation notebook.

It contains the geographical matching and spatial workflow used to generate the interactive deprivation maps, analytical dashboard and connected homepage.

The spatial workflow uses successfully matched named APFR project records and therefore represents a narrower analytical population than the main Business Analysis notebook.

## Data Availability

No datasets are included in this public repository.

The datasets required to reproduce the analysis are supplied separately to authorised users where appropriate and are subject to the relevant data-access arrangements.

To run the notebooks, place the supplied datasets in a folder named:

`Data`

within the project directory.

Example structure:

caritas-westminster-dissertation/
│
├── 01_business_analysis.ipynb
├── 02_spatial_maps_dashboard.ipynb
├── README.md
│
└── Data/
    └── [supplied datasets]

## Interactive Outputs

The spatial notebook generates eight interactive deprivation maps, an analytical dashboard and a connected HTML homepage.

The completed interactive-output package is not included in this public repository. It is shared separately with authorised reviewers where appropriate.

When the interactive-output package is supplied, the complete ZIP folder should be extracted and `index_2025.html` opened in a web browser to access the maps and dashboard.

## Reproducibility

The notebooks contain the data-processing, cleaning, matching, analytical and spatial workflow used in the dissertation.

The analysis distinguishes between the full APFR dataset, named project records and the narrower subset of named records successfully matched to mapped parish geography.

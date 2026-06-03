# Who in the EU feels less social support?

## Overview

This project visualizes differences in the share of respondents reporting “Poor” social support across EU countries using interactive choropleth maps in Plotly.

The visualization:

- compares three datasets interactively,
- uses a shared color scale for meaningful comparison,
- displays additional indicators (Strong, Intermediate) on hover,
- focuses exclusively on EU countries,
- includes custom styling and annotations for presentation-quality output.

## Notebooks

- **perception_analysis.ipynb** — exploratory notebook: data loading, cleaning, and initial wrangling across the three datasets.
- **perception_viz.ipynb** — final visualization: interactive choropleth map with toggle buttons, shared color scale, and hover details.

## Technologies
* Python
* Pandas
* Plotly (`plotly.graph_objects`, `plotly.express`)
* NumPy
* openpyxl (Excel file reading)

## Data
Source: Eurostat 2019, 'Overall perceived social support by sex, age and country of birth'.

## Setup

```bash
pip install -r requirements.txt
```

Then open either notebook in Jupyter:

```bash
jupyter notebook
```

## Structure
```
project_perception/
├── data/
│   ├── citizens_by_birth.xlsx
│   ├── eu_migrants_2019.xlsx
│   └── non_eu_countries_2019.xlsx
├── perception.ipynb
├── perception3.ipynb
├── .gitignore
├── requirements.txt
└── README.md
```
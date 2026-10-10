# Dual Dependency Gap

## Analyzing Geopolitical Trade Risks and Forecasting Egypt's Strategic Sectors

### Project Overview

This graduation project explores Egypt's trade exposure to geopolitical disruptions, focusing on three strategic sectors: food grains, fertilizers, and iron and steel.

The project combines trade data analysis, data preparation, Power BI reporting, and machine learning forecasting to support a better understanding of import dependency and potential future scenarios.

### Project Objectives

* Analyze trade patterns across the selected strategic sectors.
* Prepare and organize data for analysis.
* Explore potential import and domestic production scenarios through 2030.
* Present insights that can support strategic planning and risk assessment.

### Machine Learning Component

The forecasting notebook uses historical production and import data to estimate future outcomes through 2030 for agriculture, fertilizers, and iron and steel.

It evaluates candidate forecasting models and compares a baseline scenario with a hypothetical scenario involving a 10% increase in production.

These outputs are scenario estimates, not proof of future outcomes or a causal measurement of the war's impact.

### Tools & Technologies

* Python
* Pandas and NumPy
* Scikit-learn
* Matplotlib
* Excel
* Power BI, Power Query, and DAX

### Repository Contents

* `Machine Model.ipynb` — forecasting and scenario analysis notebook.
* `requirements.txt` — Python library dependencies.
* `data/` — information about the expected input data.

### Data Requirements

The forecasting notebook expects an Excel workbook named `EGYPT_2030_FINAL_ALL_YEARS_MODEL.xlsx`. This input file must be available in the notebook's execution environment before running the model.

### Important Notes

Forecasts depend on historical data, modeling assumptions, and the amount of available information. Results should be interpreted as estimates rather than guarantees.

### Project Context

Graduation project developed as part of the Data Analytics track.

### Data Source

Trade data for the broader project was collected from UN Comtrade:
https://comtradeplus.un.org/

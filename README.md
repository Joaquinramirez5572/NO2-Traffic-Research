# NO2 Traffic Research

A research-focused analysis project examining the relationship between NO2 emissions and traffic patterns in New York City. This work used multi-year EPA air quality data and FHWA traffic sensor data to evaluate environmental trends and support a statistical research narrative.

## Overview

- Analyzed EPA NO2 measurements and FHWA traffic sensor data
- Investigated how traffic trends relate to regional air quality patterns
- Developed the research methodology and data-processing workflow
- Contributed to the introduction, findings, and conclusion sections

This project centered on research design and analytical interpretation. I led the development of the research methodology, designed the data analysis approach, and authored the introduction, findings, and conclusions. Full credit is given to Sujan Neupane (University of Maryland at Baltimore) for software development and implementation of the analytical pipeline.

## Why This Project Matters

Air pollution and transportation are closely connected, and understanding how traffic conditions influence NO2 levels is important for environmental policy and public health. This project used real-world datasets to study how vehicle activity and emissions change over time across a major urban area, contributing to the body of work on urban air quality and transportation impact.

## Features

- Multi-year environmental and traffic dataset analysis
- Time alignment and processing of EPA and FHWA measurements
- Statistical correlation analysis across large data sources
- Research methodology development and trend interpretation
- Comprehensive written contributions to findings and conclusions

## Technical Stack

- Language: Python
- Environment: Jupyter Notebook
- Libraries: pandas, numpy, matplotlib, seaborn
- Analysis Methods: statistical correlation, time-series comparison, exploratory data analysis
- Tools: Excel and CSV processing, notebook-based workflow

## Application Design

- Data Collection: EPA air quality and FHWA traffic sensor data sourced and integrated
- Data Preparation: cleaning, alignment, and standardization across multi-year measurements
- Analysis Pipeline: correlation and trend evaluation between NO2 and traffic indicators
- Research Documentation: methodology development, introduction, findings, and conclusion authoring

This structure supported a reproducible analytical workflow and translated data insights into a rigorous research narrative.

## Project Structure

```text
NO2-Traffic-Research/
├── README.md
├── notebooks/
│   └── analysis.ipynb
├── data/
│   ├── epa/
│   └── fhwa/
├── figures/
│   ├── trend_plots/
│   └── correlation_visuals/
├── report/
│   └── findings_summary.pdf
└── notes/
    └── methodology.txt
```

## How to Run

1. Clone the repository.
2. Open the project in Jupyter Notebook.
3. Install the required Python libraries (pandas, numpy, matplotlib, seaborn).
4. Run the analysis notebook to process the datasets.
5. Review the generated figures and research summary findings.

## Example Workflow

- Load and align EPA and FHWA datasets by time period
- Clean and process time-based measurements for consistency
- Run correlation analysis on NO2 and traffic indicators
- Visualize trends and compare findings across regions
- Summarize results and interpret patterns in the final research narrative

## Testing and Validation

The project used rigorous data validation steps to confirm accurate time alignment, reduce inconsistencies, and ensure that trends remained reliable across the full dataset. Validation included reviewing missing values, comparing time ranges, and verifying that analytical results matched the intended research narrative and supported the conclusions drawn.

## Contributors

- Joaquin Ramirez: Research methodology, data analysis design, introduction, findings, and conclusions
- Mina Pham: Research methodology, data analysis design, introduction, findings, and conclusions
- Matthew Nguyen Research methodology, data analysis design, introduction, findings, and conclusions
- Sujan Neupane (University of Maryland at Baltimore): Software development (full program functionality credit) and analytical pipeline implementation

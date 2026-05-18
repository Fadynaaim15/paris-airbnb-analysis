# Historical Weather Data Pipeline & Analysis
A Data Engineering &amp; Analytics project focused on building a Python (Pandas) pipeline to profile, clean, type-cast, and transform large-scale AirBnB listing data, optimizing it for downstream market trend analysis.
# Paris AirBnB Data Pipeline & Analytics 📊⚙️

A Data Engineering & Analytics project focused on building a robust data processing pipeline to profile, clean, and transform large-scale AirBnB listing data. The project ensures high data quality standards before running analytical queries regarding market trends and regulatory impacts.

##  Data Engineering & Pipeline Objectives
* **Data Profiling & Quality Assurance (QA):** Investigated dataset schema, identified missing values, and handled data anomalies.
* **Schema Enforcement & Type Casting:** Converted currency strings and inconsistent date formats into optimized data types for structured querying.
* **Data Filtering & Transformation:** Built functional logic to filter massive global or multi-city records down strictly to high-quality Paris listings.

##  Analytics & Insights
* **Regulatory Impact Pipeline:** Processed host registration timelines to measure the exact structural impact of the 2015 hospitality regulations.
* **High-Value Aggregations:** Grouped transformed data by neighborhood to pinpoint valuation spikes, identifying **Élysée** as the premium district.

##  Tech Stack
* **Language:** Python
* **Data Libraries:** Pandas (DataFrames, Aggregations, Lambda functions)
* **Environment:** Jupyter Notebook

##  Repository Structure
```text
├── analysis.ipynb      # Core ETL and transformation script
├── README.md           # Engineering documentation
└── .gitignore          # Prevents raw large CSVs and cache leaks

# Fuel Efficiency Analysis for Mining Transportation Operations

## Project Overview

This project analyzes fuel consumption and operational efficiency for a fleet of bulk mineral transportation trucks. The objective was to evaluate fuel performance, compare actual versus expected fuel efficiency, identify high-performing vehicles, and generate actionable operational insights.

The analysis was developed using Python and focuses on real-world transportation data collected over a full year of operations.

---

## Business Problem

Fuel is one of the largest operating expenses in transportation and logistics. Small variations in fuel efficiency can have a significant impact on operating costs.

This project aims to answer the following questions:

* How does fuel consumption vary throughout the year?
* Is fuel consumption aligned with operational activity?
* How does actual fuel efficiency compare to expected performance?
* Which vehicles consistently achieve the best fuel efficiency?

---

## Dataset

The dataset contains operational records from a transportation fleet, including:

* Fuel loaded (liters)
* Distance traveled (kilometers)
* Expected fuel efficiency
* Actual fuel efficiency
* Route information
* Monthly operating records

Data from twelve monthly worksheets were consolidated into a single analytical dataset.

---

## Tools Used

* Python
* Pandas
* Matplotlib
* Jupyter Notebook
* Excel

---

## Data Preparation

The following data preparation steps were performed:

1. Consolidation of monthly worksheets into a single dataset.
2. Standardization of column names.
3. Removal of incomplete records.
4. Exclusion of partial fuel loads.
5. Detection and correction of anomalous values.
6. Conversion of numeric fields and date formatting.
7. Validation of fuel efficiency calculations.

---

## Key Performance Indicators (KPIs)

### Fuel Consumption

Total fuel consumed across the analyzed period.

### Distance Traveled

Total operational distance traveled by the fleet.

### Expected Fuel Efficiency

Target fuel performance established for operations.

### Actual Fuel Efficiency

Observed fuel performance calculated from operational records.

### Fuel Efficiency Gap

Difference between expected and actual performance.

---

## Visualizations

### 1. Monthly Fuel Consumption

Analyzes fuel consumption trends throughout the year.

![Monthly Fuel Consumption](images/monthly_fuel_consumption.png)

---

### 2. Fuel Consumption vs Distance Traveled

Compares fuel usage against operational activity levels.

![Fuel Consumption vs Distance Traveled](images/fuel_consumption_vs_distance.png)

---

### 3. Expected vs Actual Fuel Efficiency

Evaluates operational performance against expected efficiency targets.

![Expected vs Actual Fuel Efficiency](images/expected_vs_actual_fuel_efficiency.png)

---

### 4. Top 10 Vehicles by Fuel Efficiency

Identifies the highest-performing vehicles in the fleet.

![Top 10 Vehicles](images/top10_vehicle_efficiency.png)

---

## Key Findings

* Fuel consumption closely follows operational activity throughout the year.
* Actual fuel efficiency remained consistently below expected performance.
* The average efficiency gap suggests opportunities for operational improvement.
* Certain vehicles consistently outperformed the fleet average.
* Data quality validation was essential to identify and correct anomalous records before analysis.

---

## Business Impact

This analysis provides a framework for:

* Monitoring fleet fuel performance.
* Detecting efficiency losses.
* Supporting maintenance and operational decisions.
* Identifying best-performing vehicles and practices.
* Reducing transportation operating costs.

---

## Future Improvements

Potential extensions of this project include:

* Vehicle-level efficiency dashboards.
* Route-based efficiency analysis.
* Driver performance evaluation.
* Predictive fuel consumption modeling.
* Interactive dashboards using Power BI or Tableau.

---

## Author

**Carlos Rodríguez**

Operations Manager | Data Analytics Student

GitHub: https://github.com/lcrf0428

LinkedIn: https://www.linkedin.com/in/luis-carlos-rodriguez-data

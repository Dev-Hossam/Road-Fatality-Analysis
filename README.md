# Road Fatality Analysis 2016 (U.S) 

This project performs an in-depth **exploratory data analysis (EDA)** and **predictive modeling** on traffic fatalities across the United States. The goal is to uncover patterns, influential factors, and potential correlations using data from multiple government and open sources.

---

## Project Objectives

- Analyze traffic fatality trends by state, population, and road conditions.
- Explore correlations with holidays, distracted driving laws, and road infrastructure.
- Identify high-risk states and factors contributing to fatal accidents.
- Build simple predictive models to estimate fatalities based on state-level features.

---

## Data Sources

The project combines multiple public datasets from 2016:

| Source | Description |
|--------|-------------|
| [FHWA - DL22](https://www.fhwa.dot.gov/policyinformation/statistics/2016/dl22.cfm) | Driver license stats per state |
| [FHWA - FA10](https://www.fhwa.dot.gov/policyinformation/statistics/2016/fa10.cfm) | Road expenditures and fatalities |
| [FHWA - HM220](https://www.fhwa.dot.gov/policyinformation/statistics/2016/hm220.cfm) | Road mileage by type (urban/rural) |
| [TimeAndDate.com](https://www.timeanddate.com/holidays/us/2016) | National and state-specific holidays |
| [GHSA.org](https://www.ghsa.org/state-laws-issues/distracted-driving) | Distracted driving laws per state |

---

## Features Extracted

- Number of licensed drivers
- Total road miles (urban/rural)
- Traffic fatalities per 100,000 people
- State holiday counts
- Presence of distracted driving bans (yes/no)
- Road expenditures per capita
- Seasonal fatality variations

---

## Analysis & Methods

- **Pandas & Seaborn/Matplotlib** for cleaning and visualization
- **State-by-state comparisons** using bar plots and heatmaps
- **Correlation matrix** between infrastructure and fatalities
- **Holiday-based filtering** to test fatality spikes
- **Simple Linear Regression** and **Random Forest** for prediction

---

## Sample Insights

- States with **hands-free laws** show lower fatality rates on average.
- **Holiday weekends** (July 4th, Labor Day) consistently show spikes in accidents.
- **Rural road miles** have a stronger correlation with fatalities than urban roads.
- Road spending **per capita** is not always indicative of safety improvements.

---

## Tools & Libraries

- Python 3.10+
- Pandas
- NumPy
- Matplotlib / Seaborn
- Scikit-learn
- Jupyter Notebook

---

## How to Run

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Dev-Hossam/Data-Science-Road-Fatality-Analysis.git
   cd Data-Science-Road-Fatality-Analysis

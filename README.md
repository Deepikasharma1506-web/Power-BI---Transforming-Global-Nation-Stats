# World Happiness & Country Insights — Power BI

A data analysis and visualisation project exploring happiness scores across countries and years, using a World Happiness-style dataset and a country-capitals reference table. The project is packaged for GitHub with the Power BI report, source CSVs, and preview charts.

## Project at a glance

- **Primary tool:** Microsoft Power BI Desktop
- **Analysis focus:** Happiness score, country comparisons, year-wise patterns, and related social and economic indicators
- **Main dataset:** `world_happiness_report (1).csv`
- **Reference dataset:** `country_capitals.csv`
- **Power BI file:** `diy_power_bi_(1).pbix`

## Business / analysis questions

This project is organised around questions such as:

1. How does the average happiness score compare across countries?
2. How does the average happiness score change over time?
3. How are happiness scores associated with indicators such as GDP per capita, social support, healthy life expectancy, freedom, education, and work-life balance?
4. How can a country-capitals reference table support country-level reporting and geographic context?

These questions describe the analysis focus. Please make sure the visuals and measures in the PBIX match the questions you want to present in your final portfolio.

## Data used

### 1. World happiness report

The supplied CSV contains **4,000 rows** and **24 columns**, covering **10 countries** and years **2005–2024**.

Important fields include:

| Field | Description |
|---|---|
| `Country` | Country name used for comparisons |
| `Year` | Year associated with the observation |
| `Happiness_Score` | Happiness score recorded in the dataset |
| `GDP_per_Capita` | GDP-per-capita indicator |
| `Social_Support` | Social-support indicator |
| `Healthy_Life_Expectancy` | Healthy-life-expectancy indicator |
| `Freedom` | Freedom indicator |
| `Generosity` | Generosity indicator |
| `Corruption_Perception` | Perception-of-corruption indicator |
| `Education_Index` | Education indicator |
| `Life_Satisfaction` | Life-satisfaction indicator |
| `Work_Life_Balance` | Work-life-balance indicator |
| `Mental_Health_Index` | Mental-health indicator |
| `Political_Stability` | Political-stability indicator |

The CSV includes additional demographic, employment, health, internet access, crime, climate, and inequality fields. Refer to the source file for the complete list.

### 2. Country capitals

`country_capitals.csv` is a small reference table containing country names and their capital cities. It can be used to add geographic context or to support a country-level lookup/relationship in Power BI. Confirm the country labels match between the two tables before creating a relationship.

## Dataset findings (calculated from the supplied CSV)

The following are descriptive statistics from the provided CSV, not claims about official national rankings:

- The highest **average `Happiness_Score` in this dataset** is for **Australia** at approximately **5.56** across 400 records.
- The lowest **average `Happiness_Score` in this dataset** is for **UK** at approximately **5.39** across 395 records.
- The highest year-level average in the supplied data occurs in **2008**, at approximately **5.62**.
- In this dataset, the indicators with the strongest positive correlations with `Happiness_Score` among the selected fields are **Freedom** (0.03) and **Political_Stability** (0.02). Correlation describes association and does not establish causation.

Because this appears to be a supplied learning dataset, treat these results as dataset-specific rather than official global happiness rankings.

## Preview visuals

The following charts were generated from the supplied CSV to provide a quick GitHub preview. They are **dataset preview charts**, not screenshots captured from Power BI Desktop. Add screenshots exported from your actual PBIX report if you want visitors to see the precise dashboard layout.

### Average happiness score by country

![Average Happiness Score by Country](screenshots/average-happiness-by-country.png)

### Average happiness score by year

![Average Happiness Score by Year](screenshots/happiness-trend-by-year.png)

### Correlation between selected wellbeing indicators

![Wellbeing Correlation Matrix](screenshots/wellbeing-correlation-matrix.png)

## Tools and techniques

- Microsoft Power BI Desktop for report creation
- CSV data sources
- Country-level comparison and year-based analysis
- Aggregation of happiness scores by country and year
- Correlation analysis for selected numeric indicators (preview analysis)
- Country-capital reference data for geographic context

Only list Power Query transformations, DAX measures, relationships, slicers, or visual types as implemented if they are present in your report. Add the names of your own measures here if you created them.

## Repository structure

```text
World-Happiness-PowerBI-Project/
├── README.md
├── diy_power_bi_(1).pbix
├── world_happiness_report (1).csv
├── country_capitals.csv
├── .gitignore
├── docs/
│   └── DATA_DICTIONARY.md
└── screenshots/
    ├── average-happiness-by-country.png
    ├── happiness-trend-by-year.png
    └── wellbeing-correlation-matrix.png
```

## How to open the report

1. Download or clone this repository.
2. Open `diy_power_bi_(1).pbix` using Microsoft Power BI Desktop.
3. If Power BI requests a data source, point it to the CSV file included in this repository.
4. Refresh the data and verify that visuals, relationships, and filters work correctly.

GitHub does not render `.pbix` files as interactive reports directly on the repository page. The preview charts above help visitors understand the dataset, while the PBIX file is available to download and open in Power BI Desktop.

## Limitations and responsible interpretation

- The results are based on the supplied CSV and may not match official published rankings or methodology.
- Country labels and year coverage should be checked before combining tables or making comparisons.
- Correlation is not causation.
- Averages can hide variation within countries and years.
- Do not upload confidential information or datasets you do not have permission to share.

## Author

Add your preferred name and portfolio links before publishing:

- **Name:** Your Name
- **LinkedIn:** Your LinkedIn profile URL
- **GitHub:** Your GitHub profile URL

## Conclusion

This project uses country- and year-level comparisons to explore how happiness scores vary across the supplied dataset and how they relate to selected social and economic indicators. It demonstrates a practical workflow for turning structured CSV data into clear, reviewable insights with Power BI and supporting visual analysis.

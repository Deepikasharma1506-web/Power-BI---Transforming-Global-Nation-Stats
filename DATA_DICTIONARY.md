# Data Dictionary

## `world_happiness_report (1).csv`

The dataset contains 4,000 observations and 24 fields.

| Field | Description |
|---|---|
| `Country` | Country associated with the observation |
| `Year` | Observation year |
| `Happiness_Score` | Happiness score in the supplied dataset |
| `GDP_per_Capita` | GDP per capita indicator |
| `Social_Support` | Social support indicator |
| `Healthy_Life_Expectancy` | Healthy life expectancy indicator |
| `Freedom` | Freedom indicator |
| `Generosity` | Generosity indicator |
| `Corruption_Perception` | Perception of corruption indicator |
| `Unemployment_Rate` | Unemployment rate |
| `Education_Index` | Education index |
| `Population` | Population value |
| `Urbanization_Rate` | Urbanization rate |
| `Life_Satisfaction` | Life satisfaction indicator |
| `Public_Trust` | Public trust indicator |
| `Mental_Health_Index` | Mental health index |
| `Income_Inequality` | Income inequality indicator |
| `Public_Health_Expenditure` | Public health expenditure indicator |
| `Climate_Index` | Climate index |
| `Work_Life_Balance` | Work-life balance indicator |
| `Internet_Access` | Internet access indicator |
| `Crime_Rate` | Crime rate indicator |
| `Political_Stability` | Political stability indicator |
| `Employment_Rate` | Employment rate |

Check the original dataset's documentation for precise units, definitions, and collection methodology; the CSV alone does not define every metric's scale.

## `country_capitals.csv`

A single-row, wide-format reference table with country names as column headers and capital cities in the row. If you want to join it to the main dataset in Power BI, reshape it into a two-column table (`Country`, `Capital`) first, and standardise country names.

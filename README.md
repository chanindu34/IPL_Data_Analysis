# IPL Historical Data Analysis (2008-2020)

**Tech Stack:** Python, Pandas, Matplotlib, Seaborn

## Objective
Conducted Exploratory Data Analysis (EDA) on a 13-year enterprise dataset containing match outcomes and ball-by-ball delivery data to uncover statistical trends in franchise success and player performance.

## Key Insights
* **The Toss Myth:** Calculated the historical toss-to-win ratio, mathematically proving that winning the toss provides zero statistical advantage (Match win rate hovers at ~51%).
* **Franchise Dynasties:** Aggregated historical win data and generated Seaborn visualizations to identify Mumbai Indians and Chennai Super Kings as the most dominant franchises by total win volume.
* **Player Aggregation:** Parsed through ~200,000 rows of ball-by-ball data using complex `.groupby()` pipelines to extract the Top 5 all-time highest run-scorers in league history.

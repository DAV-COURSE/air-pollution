# Delhi Air Pollution — Visualizations

## Files
- `01_top_10_highest_aqi_days.png` — substitute for top 10 polluted cities; this dataset contains only Delhi.
- `02_aqi_month_hour_heatmap.png` — average AQI by month and hour.
- `03_pollutant_boxplots.png` — pollutant distributions and outliers.
- `04_aqi_category_share_pie.png` — share of recorded AQI observations by AQI category.
- `05_wind_speed_vs_aqi_scatter.png` — scatter plot of wind speed and AQI.
- `06_monthly_pollutant_trend_index.png` — monthly pollutant trends normalized to each pollutant's own average.
- `air_pollution_visualization.ipynb` — notebook with reproducible analysis and code.

## Dataset limitations
The supplied `combined_delhi.csv` contains 36,456 rows and 16 columns, but only one city (`Delhi`) and one region (`North`). There are no latitude/longitude columns. Thus, city rankings, state-versus-pollutant comparisons, and a geographic map cannot be created honestly from this CSV. The charts above use explicit substitutes where needed. Add multi-city/state data and station coordinates if the project requires those exact comparisons.

## Run the notebook
Place `combined_delhi.csv` beside the notebook, install `pandas`, `numpy`, and `matplotlib`, then open the notebook in Jupyter or VS Code.

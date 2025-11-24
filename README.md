# Zomato-India-Restaurant-EDA

This repository contains an exploratory data analysis of Zomato restaurant listings in India and a data-driven marketing campaign proposal based on those insights.

The analysis and visualizations are provided in the Jupyter Notebook `Indian_Restaurants_Market_Analysis.ipynb`. Visual assets used in the notebook are stored in the `Images/` folder.

## Contents

- `Indian_Restaurants_Market_Analysis.ipynb` — main analysis notebook (data cleaning, EDA, regional analysis, competitive analysis, market-gap analysis and visualizations).
- `Images/` — folder with figures referenced in the notebook and README.
- `zomato_restaurants_in_India.csv` — dataset used by the notebook (place the CSV next to the notebook before running).

## Quick Start

1. Place the dataset `zomato_restaurants_in_India.csv` in the repository root (next to the notebook).
2. Create and activate a Python environment (recommended) and install dependencies.

For Windows PowerShell:

```powershell
python -m venv .venv; .\.venv\Scripts\Activate.ps1
pip install --upgrade pip
pip install pandas numpy matplotlib seaborn plotly wordcloud
```

3. Open and run the notebook using JupyterLab or Jupyter Notebook:

```powershell
jupyter lab
# or
jupyter notebook
```

Open `Indian_Restaurants_Market_Analysis.ipynb` and run the cells in order. The notebook starts by loading `zomato_restaurants_in_India.csv` with `encoding='latin1'`.

## Dependencies

- Python 3.8+ (recommended)
- pandas
- numpy
- matplotlib
- seaborn
- plotly
- wordcloud

Install them with `pip install pandas numpy matplotlib seaborn plotly wordcloud`.

## What to expect

- Data cleaning and preparation steps (duplicates, missing values, basic type correction).
- Feature engineering such as `total_cuisines` and handling of `establishment`, `cuisines`, and other text fields.
- Descriptive and distribution analyses, correlation heatmaps, maps of highly rated restaurants, and city-level summaries.
- Visualizations saved in `Images/` and displayed inline in the notebook.

## Visualizations

The project includes various visualizations such as histograms, scatter plots, and heatmaps to illustrate distribution, correlations, regional trends and dashboards. These visualizations help stakeholders understand the data and derive meaningful insights.

**Image Gallery (thumbnails)**

<div style="display:flex; flex-wrap:wrap; gap:8px; align-items:flex-start;">
	<img src="Images/des1.png" alt="Descriptive statistics" width="220" />
	<img src="Images/pr.png" alt="Price Range" width="220" />
	<img src="Images/rat_dist.png" alt="Rating Distribution" width="220" />
	<img src="Images/cc.png" alt="Most Popular Cuisines" width="220" />
	<img src="Images/CorrMatrix.png" alt="Correlation Matrix" width="220" />
	<img src="Images/best_by_city.png" alt="Best Restaurants by City" width="220" />
	<img src="Images/top10byrating.png" alt="Top10 by Rating" width="220" />
	<img src="Images/no.png" alt="Top10 by Outlets" width="220" />
	<img src="Images/ratings.png" alt="High Rated Restaurants" width="220" />
	<img src="Images/newplot.png" alt="High Rated Distribution map" width="220" />
	<img src="Images/a1.png" alt="Market Analysis 1" width="220" />
	<img src="Images/a2.png" alt="Market Analysis 2" width="220" />
</div>

## Notes

- The notebook references `zomato_restaurants_in_India.csv` — if you don't have it, the notebook will fail to load the data. Place the CSV in the repository root or update the path in the first code cell.
- Some notebook cells convert columns to nullable integer types and coerce numeric parsing; review these transformations if you adapt the dataset.

## Author

Project notebook prepared by Saba Gul.

## License

This repository does not include a license file. Add one if you intend to reuse or redistribute the work.


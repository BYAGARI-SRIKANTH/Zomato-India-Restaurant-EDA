# Indian Restaurants Market Analysis (Zomato)

This repository contains an exploratory data analysis of Zomato restaurant listings in India and a data-driven marketing campaign proposal based on those insights.

The analysis and visualizations are provided in the Jupyter Notebook `Indian_Restaurants_Market_Analysis.ipynb`. Visual assets used in the notebook are stored in the `Images/` folder.

## Contents

- `Indian_Restaurants_Market_Analysis.ipynb` — main analysis notebook (data cleaning, EDA, regional analysis, competitive analysis, market-gap analysis and visualizations).
- `Images/` — folder with figures referenced in the notebook and README.
- `zomato_restaurants_in_India.csv` — dataset used by the notebook (not checked into this repo; place the CSV next to the notebook before running).

## Quick Start

1. Make sure the dataset `zomato_restaurants_in_India.csv` is in the same folder as the notebook.
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

## Notes

- The notebook references `zomato_restaurants_in_India.csv` — if you don't have it, the notebook will fail to load the data. Place the CSV in the repository root or update the path in the first code cell.
- Some notebook cells convert columns to nullable integer types and coerce numeric parsing; review these transformations if you adapt the dataset.

## Author

Project notebook prepared by Saba Gul.

## License

This repository does not include a license file. Add one if you intend to reuse or redistribute the work.

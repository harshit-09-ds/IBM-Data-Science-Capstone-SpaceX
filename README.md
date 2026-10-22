# IBM Data Science Capstone — SpaceX Falcon 9 Landing Prediction

This repository contains my IBM Data Science Professional Certificate capstone project, focused on exploring SpaceX Falcon 9 launches and building a machine-learning model to predict first-stage landing success.

## Project objectives

- Collect SpaceX launch data through an API and web scraping.
- Clean and prepare the data for analysis.
- Explore launch records with Python visualizations and SQL.
- Investigate launch-site locations and patterns.
- Build and evaluate machine-learning models for first-stage landing prediction.
- Present launch data in an interactive Plotly Dash dashboard.

## Repository structure

```text
IBM-Data-Science-Capstone-SpaceX/
├── README.md
├── requirements.txt
├── .gitignore
├── notebooks/
│   ├── 01_data_collection_api.ipynb
│   ├── 02_web_scraping.ipynb
│   ├── 03_data_wrangling.ipynb
│   ├── 04_eda_sql_analysis.ipynb
│   ├── 05_eda_data_visualization.ipynb
│   ├── 06_launch_site_location_analysis.ipynb
│   └── 07_machine_learning_prediction.ipynb
├── data/
│   └── raw/
│       ├── dataset_part_1.csv
│       ├── dataset_part_2.csv
│       ├── dataset_part_3.csv
│       ├── spacex_web_scraped.csv
│       └── spacex_analysis.sqlite
└── dashboard/
    ├── spacex_dash_app.py
    └── spacex_launch_dash.csv
```

## Tools and technologies

- Python
- Jupyter Notebook
- pandas and NumPy
- Matplotlib, Seaborn and Plotly
- SQL and SQLite
- Folium
- scikit-learn
- Dash

## Project workflow

1. **Data collection:** Retrieve launch information from the SpaceX API.
2. **Web scraping:** Gather historical launch records from Wikipedia.
3. **Data wrangling:** Clean, transform and prepare launch data.
4. **Exploratory data analysis:** Analyze launch records using SQL and visualizations.
5. **Geospatial analysis:** Explore launch sites and their locations.
6. **Machine learning:** Train and evaluate models to predict landing outcomes.
7. **Dashboard:** Explore launch success and payload patterns interactively.

## Run the notebooks

1. Clone or download this repository.
2. Create and activate a Python virtual environment (recommended).
3. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

4. Open Jupyter Notebook or JupyterLab from the repository folder:

   ```bash
   jupyter lab
   ```

5. Open the notebooks in `notebooks/` in numerical order.

Some notebooks may rely on internet access for API calls or web scraping. Historical outputs may already be saved in the notebooks.

## Run the dashboard

From the repository root:

```bash
pip install -r requirements.txt
cd dashboard
python spacex_dash_app.py
```

Then open the local address printed by Dash in your browser. The app reads `spacex_launch_dash.csv` from the same folder.

## Notes

- The dashboard CSV is a derived, dashboard-ready version of the supplied launch dataset.
- Dataset fields and results reflect the source data included in this repository.
- This is a learning/portfolio project completed as part of the IBM Data Science Professional Certificate. Review the notebooks for the detailed analysis, charts, model evaluation and conclusions.
- If you reuse third-party data or course materials, retain relevant source attribution and follow the applicable terms.

## Author

Add your name and links here before publishing:

- **GitHub:** [Your GitHub profile](https://github.com/harshit-09-ds)
- **LinkedIn:** [Your LinkedIn profile](https://www.linkedin.com/in/harshit-singh-240529407)

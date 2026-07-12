# IBM Applied Data Science Capstone Project

## Overview

This repository contains the final capstone project for the IBM Data Science Professional Certificate. The project focuses on the end-to-end data science workflow, including data collection, wrangling, exploratory data analysis, visualization, machine learning, and dashboard development. The main use case is predicting the success of SpaceX Falcon 9 first stage landings.

## Table of Contents

- [Project Structure](#project-structure)
- [Key Notebooks & Modules](#key-notebooks--modules)
- [Dashboard App](#dashboard-app)
- [Setup & Installation](#setup--installation)
- [Usage](#usage)
- [Data Sources](#data-sources)
- [Results](#results)
- [License](#license)

## Project Structure

```
.
├── API SpaceX/
│   └── Data collection via SpaceX API
├── Data wrangling/
│   └── Data wrangling notebooks and datasets
├── EDA SQL/
│   └── SQL-based exploratory data analysis
├── EDA visualisation/
│   └── Visualization notebooks (Matplotlib, Seaborn, Plotly)
├── Folium/
│   └── Geospatial analysis with Folium
├── Machine Learning/
│   └── ML pipeline to predict first stage landing success
├── Web scraping/
│   └── Data collection via web scraping (Wikipedia)
├── Dash/
│   ├── app.py                # Dash dashboard app
│   ├── requirements.txt      # Dashboard dependencies
│   └── spacex_launch_dash.csv
├── Data Science Capstone Project Report.pdf
├── Data Science Capstone Project Report.pptx
└── README.md
```

## Key Notebooks & Modules

- **API SpaceX:** Collecting launch data via the SpaceX API.
- **Web scraping:** Collecting Falcon 9 launch records from Wikipedia.
- **Data wrangling:** Cleaning and preparing the SpaceX datasets.
- **EDA SQL:** SQL queries for data exploration.
- **EDA visualisation:** Data visualization using Matplotlib, Seaborn, and Plotly.
- **Folium:** Mapping launch sites and geospatial analysis.
- **Machine Learning:** ML pipeline (Logistic Regression, SVM, Decision Tree, KNN) to predict first stage landing success.

## Dashboard App

An interactive dashboard is built using Plotly Dash (`Dash/app.py`). It visualizes SpaceX launch records, success rates, and payload analysis.

## Setup & Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/Anass422/IBM-Applied-Data-Science-Capstone-Project.git
   cd IBM-Applied-Data-Science-Capstone-Project
   ```

2. **Install dependencies:**

   - For notebooks, install requirements as needed (see notebook cells).
   - For the dashboard:

     ```bash
     cd Dash
     pip install -r requirements.txt
     ```

## Usage

- **Run Notebooks:** Open any `.ipynb` file in JupyterLab or VS Code and run cells sequentially.
- **Start Dashboard:**

  ```bash
  cd Dash
  python app.py
  ```

  The dashboard will be available at `http://127.0.0.1:8050/`.

## Data Sources

- SpaceX launch data (CSV files)
- SpaceX API
- Datasets provided by IBM Skills Network

## Results

- **Data Wrangling:** Cleaned and merged datasets for analysis.
- **EDA:** Insights into launch patterns, site performance, and payload effects.
- **Machine Learning:** Built and evaluated models (Logistic Regression, SVM, Decision Tree, KNN) to predict landing success.
- **Dashboard:** Interactive visualization of launch outcomes and payload analysis.

## License

This project is for educational purposes as part of the IBM Data Science Professional Certificate.

**Anass Elghazoui** — IBM Data Science Professional Certificate Capstone

# Sales Forecasting & Insights Using Regression

[![CI Status](https://github.com/Janhvi-Pandya/sales-forecasting-powerb/actions/workflows/run-notebook.yml/badge.svg)](https://github.com/Janhvi-Pandya/sales-forecasting-powerb/actions/workflows/run-notebook.yml)

This project demonstrates an end-to-end **Sales Forecasting solution** using Python for data analysis and regression modeling, and Power BI for business insights and storytelling.

---

## Key Components

- **Exploratory Data Analysis (EDA)**: Understanding sales trends and patterns in the Superstore dataset.
- **Feature Engineering**: Creating meaningful variables like profit margins and discount interactions.
- **Regression Modeling**: Implemented Linear, Ridge, and Lasso regressions to forecast future sales.
- **Feature Importance**: Identified key drivers impacting performance.
- **Power BI Dashboard**: Interactive visualization to communicate insights.
- **CI Pipeline with GitHub Actions**: Auto-runs notebook to ensure reproducibility.

---

##  Project Structure

```text
sales-forecasting-powerb/
├── data/                         # Raw and predicted CSVs
│   └── superstore_with_predictions.csv
├── dashboard/                    # Power BI visualization
│   └── SuperstoreDashboard.pbix
├── notebooks/                    # Analysis and forecasting in Python
│   └── sales_forecasting.ipynb
    ├── Sample-Superstore.csv
├── .github/workflows/            # CI pipeline
│   └── run-notebook.yml
├── requirements.txt
└── README.md
```

---

## GitHub Actions: CI Pipeline

This project uses a GitHub Actions workflow to automatically:

1. Set up a Python environment
2. Install dependencies from `requirements.txt`
3. Execute the Jupyter notebook and generate the output

You can find the workflow [here](https://github.com/Janhvi-Pandya/sales-forecasting-powerb/blob/main/.github/workflows/run-notebook.yml).

---

## Power BI Dashboard

- The `.pbix` file under the `dashboard/` folder contains an interactive report built on predictions and business segments.
- Insights include: regional sales trends, product category performance, and forecast accuracy visuals.

---

## Setup Instructions

To run this project locally:

```bash
# Clone the repo
git clone https://github.com/Janhvi-Pandya/sales-forecasting-powerb.git
cd sales-forecasting-powerb

# Create virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Run the notebook
jupyter notebook notebooks/sales_forecasting.ipynb
```

---

## Author

**Janhvi Pandya**  
GitHub: [@Janhvi-Pandya](https://github.com/Janhvi-Pandya)  
Python • Data Science • MLOps • Power BI  

---

## Status

Project complete and automated with CI. 

---

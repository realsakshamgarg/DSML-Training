# Exploratory Data Analysis on India's COVID-19 Data

**Project owner:** Saksham Garg  
**GitHub:** [@realsakshamgarg](https://github.com/realsakshamgarg)

## Project overview
This project explores India's historical COVID-19 case trends, state-wise differences,
recovery/death rates, and later vaccination progress using Python data-analysis libraries.

## Project files
- `India_COVID19_EDA.ipynb` — notebook for data loading, cleaning, exploratory analysis,
  visualizations, and written findings.
- `India_COVID19_EDA_Report.pdf` — accompanying project report.
- `cleaned_covid_india.csv` — cleaned dataset included with this submission.
- `requirements.txt` — Python dependencies.

## Data sources
The notebook's original workflow reads case and vaccination data from these public sources:
- COVID-19 case data: https://github.com/imdevskp/covid-19-india-data
- Vaccination data: https://github.com/owid/covid-19-data

The report describes the case-data window as 30 January 2020 to 6 August 2020, and the
vaccination data as a later period beginning in 2021.

**Important:** The notebook loads its case and vaccination data directly from the URLs above.
The included `cleaned_covid_india.csv` is supplied as a project artifact; the current notebook
does not automatically read this local CSV unless its data-loading code is changed. Internet
access is therefore required to run the notebook as currently written.

## How to run
1. Use Python 3.10+ with Jupyter Notebook, or open the notebook in Google Colab.
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Open `India_COVID19_EDA.ipynb`.
4. Run the cells from top to bottom with internet access enabled.

## Tools and methods
- Python, Pandas, NumPy, Matplotlib, Seaborn
- Data inspection and cleaning
- Grouping and pivot tables
- Time-series summaries and state-wise comparisons
- Data visualization and written interpretation

## Scope and limitations
This is a historical exploratory data analysis project, not a current COVID-19 dashboard
or a clinical prediction model. Recovery and death ratios are simple calculations from
reported cumulative totals and can be affected by reporting differences and delays.

## Author
**Saksham Garg** — [GitHub profile](https://github.com/realsakshamgarg)

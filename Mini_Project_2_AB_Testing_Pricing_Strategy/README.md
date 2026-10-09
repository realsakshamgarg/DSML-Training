# A/B Test Analysis for an E-Commerce Pricing Strategy

**Author:** Saksham Garg  
**GitHub:** [@realsakshamgarg](https://github.com/realsakshamgarg)  
**Profile:** https://github.com/realsakshamgarg

## Project overview
This project evaluates whether a new e-commerce landing/pricing page improves conversion compared with the existing page. It uses A/B testing concepts and statistical hypothesis tests to compare the control and treatment groups.

## Repository contents
- `AB_Testing_Pricing_Strategy.ipynb` — Jupyter Notebook with data loading, cleaning, exploratory analysis, and statistical testing.
- `AB_Test_Pricing_Report.pdf` — supplied written report with methodology, results, charts, and recommendation.
- `data/ab_data.csv` — original A/B test event/session dataset.
- `data/countries.csv` — user-to-country mapping dataset.
- `requirements.txt` — Python dependencies.

## Data files
The notebook expects these relative paths:
- `data/ab_data.csv`
- `data/countries.csv`

Keep the `data` folder alongside the notebook when running it.

## How to run
1. Download or clone this repository.
2. Install Python 3.10+ and Jupyter Notebook, or open the notebook in Google Colab (upload the notebook and both CSVs, preserving the `data/` paths if running locally).
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Open `AB_Testing_Pricing_Strategy.ipynb`.
5. Run all cells from top to bottom.

## Methods and tools
- Python, Pandas, NumPy
- Matplotlib
- SciPy and Statsmodels
- Data cleaning and deduplication
- Conversion-rate comparison
- Hypothesis testing: t-test, chi-square, and ANOVA (as implemented in the notebook)

## Summary from the supplied report
The supplied report analyzes 290,584 cleaned sessions and reports conversion rates of 12.04% for control and 11.88% for treatment. It reports no statistically significant difference at the 0.05 level and recommends retaining the existing page unless further testing provides evidence of improvement.

## Interpretation note
A non-significant result does not prove that the two pages are identical; it means this analysis did not find sufficient evidence of a difference under the tests and assumptions used. Review the notebook outputs after running the cells to confirm results in your environment.

## Attribution and data provenance
Project packaging and documentation prepared for Saksham Garg's GitHub repository. The dataset files and supplied report are included as provided, with filenames normalized for this project package.

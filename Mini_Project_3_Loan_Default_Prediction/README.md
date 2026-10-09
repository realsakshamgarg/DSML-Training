# Loan Default Prediction System

**Author:** Saksham Garg  
**GitHub:** [@realsakshamgarg](https://github.com/realsakshamgarg)  
**Profile:** https://github.com/realsakshamgarg

## Project overview
This supervised-learning mini project predicts whether a customer may default on a loan using employment status, bank balance, and annual salary. It compares four classification algorithms and evaluates them using metrics suited to an imbalanced target.

## Project files
- `Loan_Default_Prediction.ipynb` — notebook with preprocessing, exploratory analysis, model training, evaluation, and feature-importance analysis.
- `Loan_Default_Prediction_Report.pdf` — project report with methodology, model comparisons, charts, and conclusions.
- `data/Default_Fin.csv` — dataset used by the notebook.
- `requirements.txt` — Python dependencies.

## Dataset
The dataset contains 10,000 customer records. The target column `Defaulted?` indicates whether a customer defaulted (1) or did not default (0). The notebook drops the non-predictive `Index` column and renames columns for easier analysis.

## Models and evaluation
The notebook compares:
- Logistic Regression
- Random Forest
- Support Vector Machine (RBF kernel)
- XGBoost

Evaluation metrics include accuracy, precision, recall, F1-score, and ROC-AUC. Since defaults are a minority class, accuracy alone can be misleading; recall and ROC-AUC are also considered.

## How to run
1. Download or clone this repository.
2. Install Python 3.10+ and Jupyter Notebook.
3. From this folder, install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Open `Loan_Default_Prediction.ipynb`.
5. Run all cells from top to bottom. Keep the `data` folder alongside the notebook.

## Tools
Python, pandas, NumPy, Matplotlib, Seaborn, scikit-learn, and XGBoost.

## Interpretation and limitations
This is an educational machine-learning project, not a production-ready credit decision system. Loan decisions can have serious consequences and should not rely on this model alone. The data uses only three customer attributes and may not represent real-world lending populations or fairness requirements. Review the notebook outputs and assumptions before using any results.

## Attribution
Project documentation and repository packaging prepared for Saksham Garg. Dataset and original project report were supplied with the project materials.

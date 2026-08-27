# Credit Card Fraud Detection — Phase 1 Data Engineering Project

## Overview
This project applies a data engineering and exploratory data analysis pipeline to the
Credit Card Fraud Detection dataset, with the goal of supporting a future binary
classification task: predicting whether a transaction is fraudulent or legitimate.

## Dataset
- **Source:** Kaggle — Machine Learning Group, Université Libre de Bruxelles (ULB)
- **URL:** https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud
- **Access date:** [insert the date you downloaded the dataset]
- **Licence:** [insert exact licence text/tag as shown on the Kaggle dataset page]
- **Records:** 284,807 transactions (raw), 283,726 after cleaning
- **Features:** 30 at the initial modelling stage (`Time`, `V1`–`V28`, `Amount`), plus the
  binary target `Class`

## Reproduction Instructions
1. Download `creditcard.csv` from the Kaggle link above (requires a free Kaggle account).
2. Place the file in the same directory as the notebook, or update the file path in the
   first code cell to point to its location.
3. Open `[your notebook filename].ipynb` in Jupyter or VS Code.
4. Run all cells from top to bottom (Run All / Restart Kernel and Run All). No manual
   steps are required beyond loading the raw CSV — all cleaning and transformation is
   handled by the `clean_data()` function defined in the notebook.
5. Required Python packages: `pandas`, `numpy`, `scikit-learn`, `scipy`, `matplotlib`,
   `seaborn`. Install with:
   ```
   pip install pandas numpy scikit-learn scipy matplotlib seaborn
   ```

## Project Structure (Notebook)
1. **Task 1 — Problem Definition and Dataset Selection:** problem statement, motivation,
   stakeholders, practical relevance, dataset justification.
2. **Task 2 — Data Acquisition, Inspection, and Documentation:** loading, structure,
   data quality checks, documented assumptions.
3. **Task 3 — Data Cleansing and Transformation:** duplicate removal, outlier
   investigation, log transformation, scaling, reusable `clean_data()` pipeline.
4. **Task 4 — Exploratory Data Analysis and Visualisation:** class distribution, feature
   distributions, correlation analysis, key data insights.
5. **Inferential Statistics:** independent-samples t-test and chi-square test of
   independence on transaction amount vs. fraud class.

## Deliverables
- Jupyter Notebook (`.ipynb`) — full source code, outputs, and written interpretation
- Cleaned dataset (`creditcard_cleaned.csv`) — output of `clean_data()`, or reproducible
  via the steps above
- Data Pipeline Diagram — visual summary of the cleaning/transformation pipeline
- Progress Report (Word document) — consolidated written report covering all tasks

## Notes
- All code, analysis, and written interpretation were completed individually in
  accordance with the group project's individual-work requirements. The dataset and
  problem definition were agreed upon collaboratively with the group and approved by
  course lecturers prior to detailed implementation.

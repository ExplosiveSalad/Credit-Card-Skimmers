# Credit Card Fraud Detection — Phase 2: Applied LCS-Based Machine Learning

## Overview
This project continues directly from Phase 1, using a Learning Classifier System
(LCS)-based solution to the credit card fraud detection problem of predicting whether an
individual transaction is fraudulent or legitimate. Phase 2 covers an original LCS
baseline, data preprocessing and feature engineering for LCS performance, an improved
LCS-based system, experimental validation, comparison against conventional machine
learning models, and interpretation of LCS-evolved rules.

## Dataset
- **Source:** Kaggle — Machine Learning Group, Université Libre de Bruxelles (ULB)
- **URL:** https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud
- **Records:** 284,807 transactions (raw)
- **Features:** 30 at the initial stage (`Time`, `V1`–`V28`, `Amount`), plus the binary
  target `Class`

## Reproduction Instructions
Due to the computational cost of training and evaluating an eLCS model (single training
runs on subsampled data took 35–77 seconds; generating predictions on the full
56,746-row test set took approximately 25 minutes per model), the cleaned and
feature-engineered data is not distributed as a static file. Instead, the full pipeline
below reproduces every dataset variant used in this project exactly.

1. Make sure you are in the main branch.
2. Go to code in the top left of the repository
3. Press download ZIP
4. When it downloads, make sure to extract the zip into another folder.
5. All of our work should be there, ready to go. Double click on either
'Yaacoub_LCS_Phase2_Final' or 'MattyLuriz_LCS_Phase2_Final' and to set
your Kernel Environment. Make sure to install the required packages in
your Visual Studio Code Terminal.

These are the packages commands.

```
   pip install pandas numpy scikit-learn 
   scipy matplotlib seaborn scikit-eLCS 
   imbalanced-learn statsmodels
```

6. Run all celss from top to bottom 
(Run all is recommended since this guarantees no stales variables.)

7. The Final Report is under 'DataEngineeringAndAI_ProjectPhase2_Final'.

Mohammed Yaacoub Abou Chlih 21138726
Matty Luriz 23206450
04/10/2026
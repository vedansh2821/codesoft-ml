# codesoft-ml

Machine learning coursework from a CodeSoft ML internship (March 2024): four Jupyter notebooks covering common introductory ML tasks.

## Contents

| Notebook | Task |
| --- | --- |
| `Credit Card Fraud Detection.ipynb` | Fraud detection on transaction data |
| `Customer Churn Prediction.ipynb` | Predicting customer churn |
| `Movie Genre Classification.ipynb` | Classifying movie genres from text (TF-IDF + Naive Bayes) |
| `Spam Sms Detection.ipynb` | SMS spam classification |

## Setup

```bash
pip install -r requirements.txt
jupyter notebook
```

Dependencies: pandas, numpy, matplotlib, seaborn, scikit-learn.

## Notes

- The datasets the notebooks read are not included in this repo, so some notebooks will not run as-is without their data files.
- `Movie Genre Classification.ipynb` reads its data from hard-coded local Windows paths (e.g. `C:/Users/binod/...`), which need to be changed to point at your own data files before running it.
- No results or accuracy figures are claimed here; run the notebooks to see their outputs.

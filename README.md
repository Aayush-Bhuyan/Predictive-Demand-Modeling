# Adidas US Sales Forecasting Dashboard

Retail demand forecasting across the US market using 2020–2021 Adidas sales data.

## What's Inside
- **notebook.ipynb** — Full EDA, time-series decomposition, and model comparison
- **app.py** — Interactive Streamlit dashboard with regional filters

## Models Compared
| Model | MAE | MAPE |
|-------|-----|------|
| Naive Baseline | $X | X% |
| Linear Regression | $X | X% |
| SARIMA(1,1,1)(1,1,1,12) | $X | X% |

## Key Findings
- SARIMA reduced forecast error by X% vs baseline
- [Region] leads revenue; strongest YoY growth in [Month]
- Online channel share grew from X% (2020) to X% (2021)

## Run Locally
pip install -r requirements.txt
streamlit run app.py

# 📈 Time-Series Analysis & Forecasting

[![Python](https://img.shields.io/badge/Python-3.10+-3776AB?logo=python&logoColor=white)](https://www.python.org)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?logo=jupyter&logoColor=white)](https://jupyter.org)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

Hands-on notebooks working through the foundations of time-series modelling —
from decomposition and stationarity testing to fitting and evaluating
ARIMA-family forecasting models.

## Contents

| Notebook | Covers |
|----------|--------|
| [`Time_Series_Models_Part1.ipynb`](Time%20Series%20Analysis/Time_Series_Models_Part1.ipynb) | Trend/seasonality decomposition, stationarity (ADF test), differencing, ACF/PACF analysis, AR / MA / ARMA / ARIMA model fitting and forecast evaluation |

## Key concepts demonstrated

- **Decomposition** — separating trend, seasonal, and residual components
- **Stationarity** — why it matters, Augmented Dickey–Fuller testing, and transforming non-stationary series
- **Model identification** — reading ACF/PACF plots to choose AR and MA orders
- **Forecasting & evaluation** — out-of-sample forecasts with error metrics

## Running the notebooks

```bash
git clone https://github.com/Antonini28/time-series-forecasting.git
cd time-series-forecasting
pip install pandas numpy matplotlib statsmodels jupyter
jupyter notebook
```

## Tech stack

`Python` · `pandas` · `NumPy` · `statsmodels` · `Matplotlib` · `Jupyter`

## License

[MIT](LICENSE) © 2026 Anthony Olisa

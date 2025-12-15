
<h1 align="center">📈 Exploration and Innovation of Quality Factor_Driven Investment Strategies----Analyzing Factor Performance, Backtesting Results, Parameter Optimization, and Factor Combinations (14527131)</h1>

<p align="center">
  <b>Multi-factor equity research & backtesting notebook</b><br/>
  Quality factor decomposition (Growth / Profitability / Safety), IC/IR analysis, long-short backtests, macro regime tests + an IC-weighted alternative composite factor.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.9%2B-blue" />
  <img src="https://img.shields.io/badge/Jupyter-Notebook-orange" />
  <img src="https://img.shields.io/badge/pandas-dataframe-brightgreen" />
  <img src="https://img.shields.io/badge/numpy-numerical-informational" />
  <img src="https://img.shields.io/badge/matplotlib-plots-yellow" />
  <img src="https://img.shields.io/badge/scipy-stats-red" />
</p>

---

🔗 **Open Notebook**
- `A_14527131.ipynb`

---

## ✨ Features

- 🧮 **IC / IR Statistics** — Spearman rank IC by month, mean/std/IR & p-values summary
- 📉 **IC Time-Series Diagnostics** — cumulative IC curves + yearly IC performance breakdown
- ⚖️ **Long–Short Backtesting** — backtest (incl. transaction costs) vs benchmark & LS-active sleeve
- 🧪 **Parameter Sweep** — compare performance across `active` levels and top-`N` universe sizes
- 🌍 **Macro Regime Analysis** — correlation heatmap + t-test of macro indicators under “Good vs Poor” factor IC regimes
- 🧠 **Alternative Composite Factor** — rolling-IC weighted (dynamic) quality factor, rank-normalized and standardized
- 📊 **Visualization Ready** — portfolio value curves, yearly returns bars, correlation matrix heatmap

---

## 🚀 Quick Start

### Prerequisites
- Python **3.9+**
- Jupyter Notebook / JupyterLab

### Install
```bash
# (recommended) create a virtual environment
python -m venv .venv
# macOS/Linux
source .venv/bin/activate
# Windows
# .venv\Scripts\activate

pip install -U pip
pip install pandas numpy matplotlib seaborn scipy

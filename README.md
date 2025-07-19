# Geopolitical-Risk-Impact-on-Bitcoin-Volatility

This project analyzes how major geopolitical events influence the short-term volatility of Bitcoin (BTC), with a focus on Bitcoin's behavior as a risk asset during times of global crisis.

---

## 🧠 Objective

To understand and visualize how **major geopolitical shocks**—such as wars, international tensions, or political conflicts—affect the **volatility of Bitcoin**, specifically around the time of each event.

---

## ⚙️ Tools & Libraries

- **Python 3**
- [yfinance](https://pypi.org/project/yfinance/) – for historical crypto price data
- **Pandas** – data manipulation
- **Matplotlib** & **Seaborn** – data visualization

---

## 🗂️ Dataset

- **BTC-USD** daily data from Yahoo Finance (2021–2024)
- Manually defined event dates for major geopolitical incidents

---

## 🗓️ Events Analyzed

| Event                             | Date       |
|----------------------------------|------------|
| Russia-Ukraine War Start         | 2022-02-24 |
| Israel-Gaza Conflict Spike       | 2023-10-07 |
| Iran–US Tensions Escalate        | 2024-01-01 |

---

## 🔍 Methodology

1. Fetch historical Bitcoin data from Yahoo Finance using `yfinance`
2. Calculate:
   - **Daily return (%)**
   - **7-day rolling standard deviation** as a proxy for short-term volatility
3. Define geopolitical events manually
4. Plot volatility **30 days before and after** each event
5. Observe and interpret volatility behavior

---

## 📈 Sample Visual Output

Each plot highlights a geopolitical event with a red dashed line and shows how Bitcoin's volatility behaved around it.

---

## 📌 Key Insights

- Bitcoin often reacts to **global crises with a spike in volatility**, similar to traditional risk assets.
- The **Russia-Ukraine war** showed a dramatic rise in BTC volatility immediately after the invasion began.
- These patterns challenge the idea of Bitcoin as a consistent "safe-haven" asset during geopolitical uncertainty.

---

## 🧾 Files

- `btc_volatility_analysis.ipynb` – Jupyter Notebook with full code and plots
- `README.md` – Project overview and explanation
- `plots/` – Folder containing exported charts

---

## 🚀 How to Run

1. Open the notebook in Google Colab or Jupyter.
2. Install dependencies (only `yfinance` if needed).
3. Run all cells in sequence.
4. Review the plots and insights.

```bash
pip install yfinance

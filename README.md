
---

# PrimeTrade Junior Data Scientist Assignment: Analyzing Trader Behavior & Market Sentiment

This project presents my completed assessment for the Junior Data Scientist position at PrimeTrade. It investigates how Bitcoin market sentiment aligns with historical trading results on the Hyperliquid platform.

**Goal:** Identify trends in trader decision-making and PnL patterns under varying sentiment conditions, with the aim of producing insights that could guide better trading strategies.

## Repository Contents

* **`Notebook.ipynb`** – The main Google Colab Notebook containing Python scripts, step-by-step analysis, data visualizations, interpretations, and conclusions.
* **`fear_greed_index.csv`** – Dataset tracking Bitcoin market sentiment via the Fear & Greed Index.
* **`historical_data.csv`** – Dataset containing past trader activity and results from Hyperliquid.
* **`README.md`** – This documentation file.

## Instructions to View & Run the Project

1. **View Directly on GitHub** – Open the Google Colab Notebook file `Notebook.ipynb` from the repository interface.
2. **Run on Your Local Machine**

   * Download or clone the repository.
   * Make sure Python 3 is installed along with:

     * `pandas`
     * `numpy`
     * `matplotlib`
     * `seaborn`
     * `jupyter`
   * Install dependencies with:

     ```bash
     pip install pandas numpy matplotlib seaborn notebook
     ```
   * Navigate to the project directory in your terminal.
   * Launch the Colab  environment:

     ```bash
    Google Colab notebook
     ```
   * Open `Notebook.ipynb` and ensure both CSV files (`fear_greed_index.csv`, `historical_data.csv`) are stored in the same directory for smooth execution.

## Key Insights from the Analysis

The findings indicate a notable connection between sentiment scores and trader profitability:

* Trading in **"Extreme Greed"** phases often led to losses, even though many traders positioned themselves against the trend (shorting).
* Sentiment states such as **"Fear"** , **"Neutral"**, and **"Greed"** generally saw profitable outcomes, with traders tending toward bullish positions.
* Shifts in position sizing and directional bias were apparent when sentiment levels changed.

The Google Colab Notebook contains the complete breakdown, visual evidence, and suggested strategies based on these observations.

---

**Prepared by:** Ranjit Gupta


---





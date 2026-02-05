# 📊 Beating the House  
### How Underdogs Broke the Betting Market in the 2005/06 Premier League

**Live Storytelling Blog:**  
👉 https://smathurgrid.github.io/Football-Data/

---

## 🧠 Project Overview

Betting odds are designed to predict match outcomes with high accuracy.  
Yet during the **2005/06 Premier League season**, betting favorites failed to win in nearly **42% of matches**.

This project investigates **why** that happened.

Using match-level data and betting odds, the analysis uncovers a clear **efficiency gap** in the betting market—where underdogs systematically outperform expectations due to structural factors that odds models tend to undervalue.

The final output is an interactive, section-based storytelling blog supported by a reproducible Jupyter notebook.

---

## ❓ Core Question

**Can betting odds alone be trusted to predict football match outcomes,  
or do underdogs exploit repeatable advantages that the market underestimates?**

---

## 🔍 Key Insights

- **Favorites failed to win in 41.8% of matches** (159 out of 380)
- Underdog success is **not random**
- Two structural factors drive underdog outperformance:
  - **Disproportionate home advantage**
  - **Defensive resilience through draws**
- A small set of teams (e.g., West Ham) repeatedly exploit these inefficiencies

---

## 📈 Methodology

1. Cleaned and prepared match-level Premier League data using **Python (Pandas)**
2. Classified teams as **favorites or underdogs** based on pre-match betting odds
3. Aggregated results to team and season level
4. Built interactive visualizations using **Plotly**
5. Translated findings into a **story-driven web narrative**

All results are fully reproducible using the provided notebook.

---

## 🧪 Analysis Outputs

- Interactive web-based storytelling report (`index.html`)
- Reproducible Jupyter Notebook (`main.ipynb`)
- Cleaned and intermediate datasets (CSV files)
- Visual explanations of:
  - Market failure rate
  - Underdog point accumulation
  - Home vs away performance
  - Outcome distributions (wins vs draws)

---

## 📁 Repository Structure

```
Football-Data/
|-- index.html
|   |-- Interactive storytelling blog (final visual output)
|
|-- main.ipynb
|   |-- Reproducible Jupyter Notebook containing:
|       - Data cleaning
|       - Exploratory analysis
|       - Feature aggregation
|       - Insight generation
|
|-- Clean_Data.csv
|   |-- Cleaned match-level dataset used for analysis
|
|-- Team_Overachiever_Summary.csv
|   |-- Aggregated team-level performance metrics
|
|-- example.csv
|   |-- Supporting / intermediate dataset
|
|-- README.md
    |-- Project overview, methodology, setup instructions, and insights
```

## ▶️ How to Run the Project Locally

### 1. Clone the repository
```bash
git clone https://github.com/smathurgrid/Football-Data.git
cd Football-Data






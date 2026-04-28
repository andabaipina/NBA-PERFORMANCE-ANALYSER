# 🏀 NBA Performance Analyser — 2024-25 Season

A data analytics project that pulls live NBA statistics directly from the official NBA database, analyses player and team performance, and presents findings through interactive visualisations.

Built by **Andabai Pina** as part of a Python for Data Work learning journey.

---

## What this project does

- Fetches live 2024-25 NBA season data using the `nba_api` library
- Cleans and filters player statistics to remove small sample sizes
- Converts season totals to true per game averages (PPG, RPG, APG, SPG, BPG)
- Ranks the top 15 scorers in the league
- Builds a composite performance score to identify the most well-rounded players
- Analyses all 30 teams by win percentage and offensive output
- Identifies which stats correlate most strongly with winning
- Produces an MVP candidate comparison across all key statistical categories

---

## Key findings

- **Nikola Jokić** ranked first in composite score (58.1) despite not leading in any single category — his combination of 27.7 PPG, 12.9 RPG and 10.7 APG makes him the most complete player in the league
- **Plus/Minus** had the strongest correlation with winning among all team stats, suggesting roster depth and team cohesion matter more than raw offensive output
- **Luka Dončić** led all players in scoring at 33.5 PPG but ranked second in composite score due to lower defensive contributions

---

## Tools and libraries

| Tool | Purpose |
|------|---------|
| `nba_api` | Fetching live NBA data |
| `pandas` | Data cleaning and transformation |
| `plotly` | Interactive charts and visualisations |
| `seaborn` | Correlation heatmap |
| `matplotlib` | Supporting visualisations |
| `scikit-learn` | Statistical analysis |

---

## Project structure

```
nba-performance-analyser/
│
├── NBA_Performance_Analyser.ipynb   # Main notebook
└── README.md                        # This file
```

---

## How to run it

**Option 1 — Google Colab (recommended)**

Click the badge below to open the notebook directly in Colab — no installation needed:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/andabaipina/nba-performance-analyser/blob/main/NBA_Performance_Analyser.ipynb)

**Option 2 — Run locally**

```bash
pip install nba_api pandas plotly seaborn matplotlib scikit-learn
jupyter notebook NBA_Performance_Analyser.ipynb
```

---

## Visualisations included

- Top 15 scorers bar chart
- Player efficiency scatter plot (points vs assists, sized by rebounds)
- Team win percentage bar chart
- Offence vs dominance scatter plot
- Correlation heatmap — what stats relate most to winning
- MVP candidate grouped bar chart with composite score breakdown

---

## About

This project was built as part of a structured Python for Data Work learning path, covering data ingestion, cleaning, feature engineering, statistical analysis and data storytelling.

**Andabai Pina** — Python Data Analyst in training  
GitHub: [github.com/andabaipina](https://github.com/andabaipina)

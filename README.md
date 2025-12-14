# IPL 2022 Capstone Project

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)](https://jupyter.org/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

## 📊 Overview

This capstone project analyzes IPL 2022 match-level data to derive meaningful insights and understand match outcomes, player performances, and team dynamics. The Indian Premier League (IPL) is a professional T20 cricket league in India, featuring franchises representing cities.

**Dataset**: 74 IPL 2022 matches with 20 detailed columns

## 📁 Project Structure

```
IPL-CAPSTONE-PROJECT/
├── ipl_capstone.ipynb          # Main Jupyter notebook with analysis
├── IPLcsv                      # IPL 2022 dataset (CSV)
├── anaconda_projects/db/       # Additional database files
├── .ipynb_checkpoints/         # Notebook checkpoints
└── README.md                   # This file
```

## 🔧 Technologies Used

- **Python** - Data analysis and processing
- **Pandas** - Data manipulation
- **NumPy** - Numerical computing
- **Matplotlib** - Data visualization
- **Seaborn** - Statistical visualizations
- **Jupyter Notebook** - Interactive analysis environment

## 📊 Dataset Features (20 columns)

- match_id, date, venue
- team1, team2
- stage (Group/Playoff)
- toss_winner, toss_decision (Field/Bat)
- first_ings_score, first_ings_wkts
- second_ings_score, second_ings_wkts
- match_winner, won_by (Runs/Wickets), margin
- player_of_the_match
- top_scorer, highscore
- best_bowling, best_bowling_figure

**Data Quality**: No null values across all columns

## 🔍 Key Analysis & Findings

### 1. **Most Matches Won by Team**
   - **Gujarat** leads with 12 wins
   - **Rajasthan** 11 wins
   - **Bangalore & Lucknow** 10 wins each
   - **Punjab & Delhi** 7 wins each
   - Other teams: Kolkata (6), Hyderabad (6), Chennai (4), Mumbai (4)

### 2. **Toss Decision Trends**
   - **Field** decisions dominate (~59 out of 74 matches)
   - **Bat** decisions much less common (~16 matches)

### 3. **Match Outcomes**
   - **Toss winner vs Match winner correlation**: 48.65%
   - Teams that win the toss have roughly 50% chance of winning the match
   - **Wins by Runs**: ~37 matches
   - **Wins by Wickets**: ~37 matches (balanced)

### 4. **Key Player Performances**

#### Most Man of the Match Awards
   - **Kuldeep Yadav**: 4 awards
   - **Jos Buttler**: 3 awards
   - Multiple players: 2 awards each

#### Top Run Scorers
   - **Jos Buttler**: 651 runs
   - **Quinton de Kock**: 377 runs

#### Best Bowling Figures (Most Wickets)
   - **Yuzvendra Chahal**: 17 wickets
   - **Jasprit Bumrah**: 11 wickets
   - **Kuldeep Yadav**: 11 wickets
   - **Rashid Khan**: 11 wickets

## 📈 Visualizations Included

✓ Bar chart: Most matches won by team
✓ Count plot: Toss decision trends
✓ Count plot: Match outcomes (Runs vs Wickets)
✓ Bar chart: Top 10 Man of the Match award winners
✓ Bar chart: Top run scorers
✓ Rankings of best bowling figures

## 🎯 Key Insights

1. **Gujarat was the dominant team** in IPL 2022 with 12 match wins
2. **Toss decision plays a role** but doesn't guarantee match victory
3. **Most matches decided by runs** and wickets equally
4. **Pace bowlers (Kuldeep Yadav, Jasprit Bumrah)** were among the standout performers
5. **Foreign players (Jos Buttler, Quinton de Kock)** were key contributors in batting

## 🚀 Getting Started

### Prerequisites
- Python 3.8+
- Jupyter Notebook
- pandas, numpy, matplotlib, seaborn

### Installation

```bash
# Clone the repository
git clone https://github.com/surag29/IPL-CAPSTONE-PROJECT.git
cd IPL-CAPSTONE-PROJECT

# Install dependencies
pip install pandas numpy matplotlib seaborn jupyter

# Launch Jupyter
jupyter notebook

# Open ipl_capstone.ipynb
```

## 📖 How to Run

1. Open `ipl_capstone.ipynb` in Jupyter Notebook
2. Run cells sequentially to see the analysis
3. Each section has comments explaining the analysis

## 💡 What This Project Demonstrates

✅ Data loading and exploration with pandas
✅ Data quality checks (null values, shape, info)
✅ Exploratory data analysis (EDA)
✅ Statistical analysis (value counts, groupby)
✅ Data visualization with matplotlib and seaborn
✅ Deriving actionable insights from data
✅ Professional Jupyter notebook structure

## 🤝 Contributing

Contributions welcome! Feel free to:
- Suggest new analysis questions
- Improve visualizations
- Add more statistical analysis
- Fix any issues

## 📞 Contact

**Surag Devadiga** - [@surag29](https://github.com/surag29)

- 📧 Email: [surudev29@gmail.com](mailto:surudev29@gmail.com)
- 💼 LinkedIn: [surag-devadiga-233477329](https://www.linkedin.com/in/surag-devadiga-233477329)
- 🐙 GitHub: [@surag29](https://github.com/surag29)

## 📄 License

MIT License - See LICENSE file for details

---

**Last Updated**: December 2025

*A capstone project analyzing IPL 2022 cricket data to uncover match insights and player performance patterns.*

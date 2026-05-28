# IPL Data Analysis — Decoding Match-Winning Patterns 🏏

An end-to-end IPL data analytics project built using Python, Pandas, and Matplotlib to uncover hidden match-winning trends from real IPL ball-by-ball data.

## 📌 Project Objectives
This project answers three major IPL questions:

- Does winning the toss actually increase chances of winning?
- Which phase impacts victory the most — Powerplay, Middle Overs, or Death Overs?
- Who were the top 5 batters and bowlers across five IPL seasons?

---

## 📊 Key Insights

- Toss advantage was surprisingly minimal, with toss winners winning only slightly more matches than toss losers.
- Death overs (16–20) showed the strongest connection with victory, having the largest scoring gap between winning and losing teams.
- Elite batters and strike bowlers consistently dominated performance charts across multiple seasons.

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

---

## 📂 Dataset

- Link: https://wooble.org/hackathon/crunch-26
- Records Analyzed: 289,000+ deliveries
- Format: CSV / JSON converted to CSV

Each row represents:
- one ball bowled
- batter and bowler information
- runs scored
- wicket details
- match outcome

---

## 📈 Analysis Performed

### 1️⃣ Toss Impact Analysis
- Compared toss winners vs toss losers
- Calculated winning percentages
- Created comparative bar charts

### 2️⃣ Match Phase Analysis
Divided innings into:
- Powerplay (1–6)
- Middle Overs (7–15)
- Death Overs (16–20)

Compared scoring patterns of winning and losing teams across phases.

### 3️⃣ Player Performance Analysis
- Top 5 batters by runs
- Top 5 bowlers by wickets
- Styled analytical tables
- Performance visualizations

---

## 📷 Visualizations Included

- Toss Impact Bar Chart
- Match Phase Comparison Line Chart
- Top Batters Bar Chart
- Top Bowlers Bar Chart
- Styled Performance Tables

---

## 🚀 How to Run

```bash
git clone https://github.com/YOUR_USERNAME/ipl-data-analysis.git
cd ipl-data-analysis

pip install pandas numpy matplotlib

jupyter notebook
```

---

IPL_ANALYSIS/
│
├── ipldatasetanalysis.ipynb      # Main Jupyter notebook containing complete analysis
├── ipldata.csv                   # IPL ball-by-ball dataset
├── README.md                     # Project documentation
│
├── charts/                       # Optional folder for saved visualizations
│   ├── toss_impact_chart.png
│   ├── phase_analysis_chart.png
│   ├── top_batters_chart.png
│   └── top_bowlers_chart.png
│
├── outputs/                      # Optional folder for exported outputs
│   ├── final_table.csv
│   └── insights.txt
│
└── .gitignore                    # Ignore unnecessary files

---

## 🎯 Final Conclusion

The most surprising insight was how little toss advantage mattered compared to the massive scoring gap during death overs.

---

## 👨‍💻 Author

Sushant Singh  
Data Science & Machine Learning Enthusiast

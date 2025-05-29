

# ⚽ Tactical Football Analysis Visualizations

This project explores tactical trends and match outcomes using real football match data. It includes two key visualizations that analyze team strategies over time and the impact of press intensity on match performance.

---

## 📈 KPI Trend (3-Month Rolling)

A stacked area chart showing how a team’s tactical identity evolves across quarters. The following KPIs are extracted from `Team_Attributes.csv` and normalized:

- **BuildUp Play Speed**: Speed of transition from defense to attack.
- **Defensive Pressure**: Aggressiveness in pressing opponents.
- **Defensive Line Height**: How high the defensive line holds its shape.

This chart helps reveal whether a team is becoming more aggressive, structured, or defensive over time.



![Screenshot 2025-05-09 163836](https://github.com/user-attachments/assets/bbc365e6-35a5-48cd-9151-6d74caae80b7)
---

## ⚽ Press-Intensity Δ vs Goal Δ (Bubble Chart)

A scatter plot analyzing how tactical pressing relates to match results. Each match is represented by:

- **X-axis**: Press intensity difference between home and away teams.
- **Y-axis**: Goal difference (home team perspective).
- **Bubble Color**: Match result (Win/Draw/Loss).
- **Bubble Size**: xG conceded (currently simulated).
![Screenshot 2025-05-09 163936](https://github.com/user-attachments/assets/19424cbf-55d2-46cf-a099-85f4217171ac)







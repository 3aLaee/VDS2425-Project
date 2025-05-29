
![image](https://github.com/user-attachments/assets/6af64163-3c3a-4849-b544-bca165c412b7)
***Description***: 
The “Gold-Mine Scout” chart uses simple, intuitive visual mappings to help you spot promising young talent at a glance. First, each player appears as a single circular mark positioned in two dimensions: age on the horizontal axis and potential rating on the vertical axis. This immediately lets you see which players are both young (further left) and have high upside (further up). Beyond position, the circles vary in two more ways. Their area encodes each player’s current overall rating—larger bubbles mean a higher current ability—so you can distinguish raw potential from demonstrated quality. At the same time, the fill color of each bubble comes from a continuous blue colormap: darker, richer blues indicate a higher simulated goals-plus-assists-per-90 metric. This hue/luminance channel highlights which up-and-coming players are already delivering on the pitch. To reduce visual clutter and help overlapping points stand out, every bubble is drawn semi-opaque (α≈0.8) and given a thin white border. The player’s name is also printed just above each bubble, so you don’t have to cross-reference a legend to know who’s who. Axes are kept minimal—light gray bottom spines with zero-length ticks and no gridlines—to focus attention on the data rather than chart decorations. Finally, two legends explain the encodings: a vertical colorbar at right for the goals+assists scale, and a small cluster of sample gray circles in the lower-right corner illustrating how bubble size translates to current rating values. Taken together, these marks and channels make


![image](https://github.com/user-attachments/assets/b807f12d-7814-453d-bf21-f258a676ddd5)
***C-3 Volatility Scout – Year-over-Year Rating Stability***

**Description**:  In this faceted sparkline chart, each player’s panel traces the trajectory of their annual mean overall rating as a bold steel-blue line. Surrounding that line is a semi-transparent lightsky-blue ribbon that extends one standard deviation above and below the mean, encoding year-to-year volatility in their performance. Because both panels share the same horizontal axis of calendar years and a common vertical scale, you can immediately see not only how each player’s quality changed over time but also whether their form was steady or prone to fluctuation. Design choices reinforce clarity and comparability: each player’s name sits flush against the left margin of its panel, eliminating the need for a separate legend entry; the top, right, and left spines are removed and only a light gray baseline remains to anchor the year ticks; and y-axis ticks are hidden to focus attention on the shape and width of the lines and bands. A single patch legend in the lower panel reminds viewers that the shaded band represents “±1 σ rating volatility,” tying the visual encoding back to the notion of durability and consistency in a player’s performance.


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







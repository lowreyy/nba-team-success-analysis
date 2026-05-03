# nba-team-success-analysis
Analyzed NBA team statistics from 2010–2024 to identify which performance metrics most strongly predict winning using Python, SQL, and data visualization.

## Project Overview
This project explores the evolution of winning strategies in the NBA over the last 15 seasons. By analyzing team-level statistics, the project identifies which metrics—such as 3-point volume, offensive efficiency, and pace—have become the strongest predictors of team success in the modern era.

## The Data Workflow
**Extraction & Cleaning:** Used Python to process and merge multiple datasets, including team_stats_per_game, team_summaries, and team_totals.  

**Database Management:** Engineered a cleaned SQL table structure to handle metrics like o_rtg (Offensive Rating), d_rtg (Defensive Rating), and pace.  

**Validation:** Performed rigorous data integrity checks to ensure zero null values in primary predictors and removed "League Average" noise for cleaner correlation analysis.  

**Visualization:** Built a Power BI dashboard to visualize trends, such as the correlation between 3-point attempts (x3pa_per_game) and win percentages.  

## Key Features & Metrics
**Efficiency Tracking:** Analysis of o_rtg and d_rtg to determine a team's net efficiency.  

**The 3-Point Trend:** Visualizing the impact of increased x3pa_per_game on total wins.  

**Pace Analysis:** Monitoring how the pace of the game has shifted from 2010 to 2024 and its relationship to turnovers (tov_pg).  

**Playoff Success:** Filtering data to see which statistical profiles consistently lead to playoffs appearances.  

## Tech Stack
**Language:** Python (Pandas)

**Database:** SQL

**Visualization:** Power BI

**Timeline:** 2010–2024 NBA Seasons. This specific timeline was chosen because it is when winning formulas and the style of play completely changed.

## Final Analysis & Key Findings
After visualizing 15 years of NBA team data (2010–2024), the following conclusions were drawn regarding the evolution of winning in the league:

**1. Efficiency is King**

The data confirms that **Offensive and Defensive Ratings** remain the strongest predictors of a team's win percentage.  

- **Offensive Dominance:** Teams with high offensive efficiency consistently achieve higher win percentages, proving that how you score is more important than how much you shoot.  

- **Defensive Floor:** Defensive efficiency remains a critical pillar of success; teams that allow fewer points per 100 possessions maintain a significantly higher winning floor.  

**2. The "Warriors Effect" & The 3-Point Revolution**

This analysis highlights a massive league-wide shift toward perimeter-oriented offenses.  

- **The Catalyst:** Starting around 2014, the Golden State Warriors—led by Stephen Curry and Klay Thompson—revolutionized the game with high-volume, high-efficiency 3-point shooting and small-ball lineups.  

- **Volume vs. Efficiency:** While 3-point attempts (3PA) have skyrocketed league-wide, the data shows that volume alone does not guarantee wins; it must be paired with high-level efficiency to translate into a higher win percentage.  

**3. Pace vs. Value**

One of the more surprising insights is the role of Pace:

- **Speed ≠ Wins:** While the NBA has seen a sharp increase in pace due to rule changes and offensive innovation, pace alone shows little correlation with winning.  

- **Ball Security:** Teams that commit fewer turnovers (tov_pg) tend to win more, though this effect is secondary to raw scoring efficiency.

# Cricket-Data-Analytics-Project-Using-Web-Scraping-Python-Pandas-and-Power-BI

**Problem Statement**

This project aims to analyze player performances from the ICC Men's T20 World Cup 2022-23 and select the best XI players based on batting, bowling, and all-round performance metrics. The analysis aims to provide actionable insights for team selection and strategy planning.

**Overview**

This project analyzes T20 cricket match data to derive insights on batting, bowling, and overall team performances. The dataset includes individual player stats, match summaries, and player metadata.

**Objectives**

- Identify top-performing batsmen and bowlers.
- Evaluate strike rates, economy rates, and impact players.
- Select the best XI players based on performance metrics.
- Provide actionable insights for team selection and strategy.

**Data Sources**

- Batting Summary: Individual runs, balls faced, boundaries, strike rate.
- Bowling Summary: Overs bowled, wickets taken, economy rate, dot balls.
- Match Summary: Team performance, match outcomes, and locations.
- Player Info: Player roles, batting/bowling styles.
- Data Scraping: Data collected from ESPN Cricinfo (https://www.espncricinfo.com/records/tournament/team-match-results/icc-men-s-t20-world-cup-2022-23-14450).

**Data Preprocessing**

- Performed using Python and Pandas:
- Data Cleaning: Removed null values, corrected data types.
- Feature Engineering: Created new metrics (e.g., runs per over, dot ball percentage).
- Merging Data: Combined match, player, batting, and bowling data for comprehensive insights.

**Libraries Used**

- Pandas - Data manipulation and preprocessing.
- Power Query (Power BI) - Data transformation and modeling.
- DAX (Power BI) - Data modeling and analysis.

**Key Insights**

- Batting Analysis
- Highest individual scores and consistency metrics.
- Best strike rates and boundary percentages.
- Comparison of openers vs. middle-order contributions.

**Bowling Analysis**

- Most economical and wicket-taking bowlers.
- Dot ball effectiveness and death-over impact.
- Wicket distribution among different types of bowlers.

**Best XI Selection**

- Using performance metrics to select the most balanced team:
- Top Batsmen: Highest run scorers with best strike rates.
- All-Rounders: Players contribute significantly to both departments.
- Bowlers: Most effective in wicket-taking and economy.

**Observations**

- Strike rate plays a crucial role in T20 batting performance.
- Bowlers with high dot-ball percentages and lower economy rates are more valuable.
- All-rounders provide the necessary balance between batting and bowling strengths.
- Powerplay and death-over performances significantly impact match outcomes.

**Technologies Used**

- Python (Pandas) for data processing.
- Power BI for data modeling and dashboard creation.
- Jupyter Notebook for analysis workflow.
- GitHub for project documentation and sharing.

**Future Improvements**

- Use machine learning for predictive player performance.
- Analyze team strategies in different match conditions.
- Expand dataset to include past seasons for trend analysis.

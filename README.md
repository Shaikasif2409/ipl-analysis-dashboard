# ipl-analysis-dashboard
## 📊 Project Overview
This project focuses on analyzing 15 seasons of the Indian Premier League (IPL) from 2008 to 2022 to uncover key insights on team performance, match outcomes, and player contributions. The analysis leverages PostgreSQL for data handling, Power BI for visualization, and DAX for advanced metrics to build a dynamic, interactive dashboard.

## 🗂️ Data & Methodology
### Data Sources:

ipl_matches_2008_2022.csv: Match-level data

ipl_ball_by_ball_2008_2022.csv: Ball-by-ball delivery data

### Database Management:

Created PostgreSQL tables using SQL DDL

Imported CSV datasets using COPY command into respective tables

Data cleaning and transformation done using SQL queries

### Dashboard Tool:

Power BI for interactive dashboard development

DAX functions for metrics such as strike rate, economy, win %, etc.

## 🛠️ Technologies Used
PostgreSQL – For database creation and querying

Power BI – For visualization and dashboard development

DAX – For calculated metrics and KPIs

SQL – For ETL and insight generation

### 🧠 Key SQL Queries
Created tables for ipl_matches_2008_2022 and ipl_ball_by_ball_2008_2022

Loaded CSVs using COPY statements

Key analytical queries:

Top run scorers and wicket-takers

Most successful teams per season

Win percentage calculations

Venue-based win trends

Player performance under pressure


## 📈 Power BI Dashboard Highlights
1. Match Insights
Total matches played per season

Venue-wise match distribution

Toss decision analysis

2. Team Performance
Win/loss stats across seasons

Most consistent franchises

Winning margins and trends

3. Player Performance
Top batters by runs and average

Top bowlers by wickets and economy

Match-winning performances (MOM awards)

4. Seasonal Comparisons
Year-on-year trends

Playoff and final performance

Toss vs match result correlations

## 💡 Insights & Recommendations
Teams winning the toss don’t always win the match—strategy matters more than luck.

Certain venues show a bias toward chasing or defending; teams should plan accordingly.

Some players consistently perform under pressure, offering high ROI for franchises.

Data-backed auction strategies can lead to long-term franchise dominance.

## ✅ Conclusion
The IPL Analysis Dashboard empowers analysts, franchises, and fans with data-driven insights. Leveraging SQL for backend processing and Power BI for storytelling, this project demonstrates how sports analytics can reveal strategic advantages, performance benchmarks, and fan engagement metrics.


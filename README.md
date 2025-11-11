# IPL PROJECT
।

🏏 IPL Data Analysis Project

This project provides a complete exploratory data analysis (EDA) of Indian Premier League (IPL) data using Python, Pandas, NumPy, SQL, and Power BI.
The project includes data cleaning, visualization, season-level performance insights, batsman/bowler rankings, and a full Power BI dashboard.

✅ Tech Stack Used

Python

Pandas

NumPy

SQL

Power BI

Matplotlib / Seaborn (if used)

📂 Dataset Description

Project uses IPL datasets containing match-level and ball-by-ball information.

1. matches.csv

Contains match-level information:

Match ID

Season

Teams

Venue

Winner

Player of the match

2. deliveries.csv / bowling data

Contains ball-by-ball details:

Batsman_runs

Bowler

Total_runs

Dismissal type

Over, ball

Batting & Bowling team

✅ Project Highlights
🔹 1. Data Cleaning

Removed missing values

Converted data types

Merged match & ball-by-ball data

Filtered invalid entries

🔹 2. Data Visualization

Using Python & Power BI:

Run patterns

Wickets trend

Team comparison

Overs-wise analysis

🔹 3. Season-wise Analysis

Total runs scored per season

Highest scoring teams

Most matches won per season

Top batting & bowling performers

🔹 4. Batsman Ranking

Orange Cap trend

Total runs

Strike rate

Boundary count

🔹 5. Bowler Ranking

Purple Cap trends

Total wickets

Economy rate

Dot ball %

🔹 6. Power BI Dashboard

Season filters

Team performance summary

Most valuable players

Toss decision impact

Venue-based win %

(You can add dashboard images here)

![Dashboard](dashboard.png)

✅ SQL Insights

Season-wise total runs

Top 10 batsmen

Most wickets taken

Toss vs match result relation

City-wise match distribution

Example query:

SELECT season, SUM(total_runs) AS total_runs
FROM deliveries d
JOIN matches m ON d.match_id = m.id
GROUP BY season
ORDER BY season;

🛠️ Project Workflow
1. Load dataset
2. Clean & preprocess data
3. Perform SQL & Python analysis
4. Build visualizations
5. Create Power BI dashboard
6. Export insights for reporting

📸 Screenshots

(Add your dashboard or chart images here)

![Visualization](img1.png)
![Dashboard](img2.png)

✨ Conclusion

This project gives a complete understanding of IPL performance trends by analyzing batsmen, bowlers, teams, seasons, and venues.
It is a perfect end-to-end data analytics project combining Python, SQL, and Power BI.

👤 Author

Ashik Kumar
LinkedIn: www.linkedin.com/in/ashik-kumar-99b01a2ba

# NC State Women's Tennis Dashboard Project

Overview
This project is focused on visualizing key metrics for the NC State Women's Tennis team, leveraging data from the CIZR software, which has been used since 2018 to tag and generate stat reports for individual matches. The purpose of this project is to help the coaching staff and players better understand player performance and guide development plans.

Project Goals:
Cumulative Player Stats: Create a cumulative stats profile for each eligible player based on 17 core metrics. The visualizations cover both seasonal and career averages. Eligible players have participated in at least 7 completed matches or logged over 700 points on film.

Team Leaderboard: Develop a leaderboard for each metric, showcasing which players excel in specific areas based on their averages.

Plus/Minus Ratio: Generate a plus/minus ratio for each player using Bill Jacobsen's Aggressive Error Margin formula. The calculation is:
(Aces + Winners + Forced Errors) - (Double Faults + Unforced Errors)

First Serve Performance Rating: Apply Craig O'Shannessy's formula for evaluating first serve performance. It multiplies the first serve percentage by the win percentage for the first serve (e.g., 65% first serve percentage × 70% win percentage = 45.5).

Wins vs. Losses Metrics: Visualize how key metrics differ between wins and losses, focusing on the following:

Unforced Errors
First Serve Percentage
Forced Errors
Double Faults per Second Serve
Performance Against Recruiting Competitors: Using an Excel file of NC State WTA points, the project visualizes the team's performance relative to recruiting competition for the 2023-24 calendar year.

Top 10 WTA Performance Visualization: Showcase top 10 WTA performances by team, singles, doubles, and individual players, including their respective teams.

Key Visualizations
We incorporated 19 metrics and 12 visualizations into the dashboard, equipping coaches with valuable tools to enhance training programs and recruiting efforts.

Project Structure
Tableau Dashboard: The live dashboard includes all the visualizations created based on the above goals (Linked Here: https://public.tableau.com/views/NCSUTennisDashboard/HomePage?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)
R Markdown File: Contains all the data manipulations and metric calculations for this project.
Excel File: Used for visualizing team and individual performances relative to recruiting competitors.

Check out the final presentation here where we discuss the dashboard features and how the visualizations provide actionable insights for both coaches and players.


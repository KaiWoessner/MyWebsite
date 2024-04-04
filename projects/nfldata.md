## National Football League Data Analysis
In this project I processed diverse datasets and constructed graphs to visualize the performance of players and teams in the National Football League (NFL) using Google Colab.
This project uses data from the Python library `nfl_data_py`.
The project itself was split into 4 smaller projects:
1. Weekly and Yearly Team Rankings
2. Matchup Calculator
3. Visual Game Breakdown
4. Win Percentage Breakdown  

### Weekly and Yearly Team Rankings
This sub-project involved using general data from the 2023 NFL season to objectively track the rankings of teams based on EPA/play (Expected points added per play) on Offense, Defense, and Overall.
EPA/play is basically how successful a given play is where a positive number is good and and a negative number is bad.
The data for the Weekly Team Rankings chart is independent for each week (where each week is one game). In games where the team has a bye week (the team did not play), they where removed from the week.
The data for the Yearly Team Rankings chart is dependent on the previous weeks and so the EPA/play is added each week.
Below are a few example charts:  


 

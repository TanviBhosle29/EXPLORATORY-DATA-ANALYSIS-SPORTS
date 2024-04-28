**EXPLORATORY DATA ANALYSIS- SPORTS**


**TASK:** Exploratory Data Analysis on IPL dataset

**Objective:** Perform 'Exploratory Data Analysis' on dataset 'Indian Premier League'. 


**Dataset link:** https://bit.ly/34SRn3b


**Files:** 

deliveries.csv - Information about match, player, runs and wickets

matches.csv - Information about toss, venue, umpire, winner


**Dataset Characteristics:**

**from deliveries data:**
match_id (1 to 11415), inning (1 to 5), batting_team (15 Teams) bowling-team (15 Teams), over (20 overs), ball (9 balls), batsman, non_striker, bowler, is_super_over (0-No, 1-Yes), wide_runs (0 to 5), bye_runs (0 to 4), legbye_runs (0 to 5), noball_runs (0 to 5), penalty_runs (0 and 5), batsman_runs (0 to 7), extra_runs (0 to 7), total_runs (0 to 10), player_dismissed, dismissal_kind, fielder

**from matches data:**
id (record index), season (2008 to 2019), city, date, team1, team2, toss winner, toss decision (bat/field), result, dl_applied (1-yes, 0-no), winner, win_by_runs, win_by_wickets, player_of_match, venue, umpire1, umpire2, umpire3 


**Analysis:**

Firstly we prepared summary for both the datasets to understand the basic information of data.

Then I used EDA technique. EDA is nothing but data exploration technique to understand the various aspects of the data. Here I have used Univariate, Bivariate amd Multivariate visualization techniques.

I presented below informations using charts/graphs using python matplotlib and seaborn libraries:

1) Total IPL seasons
2) IPL team won by scoring the maximum runs
3) IPL team won by taking the maximum wickets
4) IPL team won by taking the minimum wickets
5) Seasonwise number of matches played
6) Seasonwise number of teams played
7) Successful IPL team
8) Venue for maximum matches
9) Umpire for maximum matches
10) Performance of the bowlers
11) Top run getters
12) Decision after winning the toss
13) Teams bat first or second after winning toss






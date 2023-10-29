# player_of_the_match_analysis
Identifying the player likely to have the most  significant impact on a cricket match


FE was a complex task for the task. Which all are necessary and required features was the most difficult task. Based on the observations, for batter mainly runs, bowls, matches played , matches batted were selected; for bowlers overs bowled, runs conceded and wickets were taken. 
Aggregated Strike rate is calculated for the whole picture. Similarly for bowlers aggregated economy is calculated. Also average and average wickets per is calculated for batters and bowlers respectively.


SR = total runs / total bowls faced


Avg runs = total runs / total matches batted


Economy = total runs conceded / overs bowled


Avg wickets = total wickets / total matches bowled

### Extended Feature Engineering


Objectives of extended FE :
1. Correlate batter and bowler
2. Give weightage for both performance of an all-rounder
So, a rating is created for batting and bowling for each player. Then this rating is used to define a standard scale for the correlation.
This was the most important so as the most difficult part of this analysis; how to correlate a batter and a bowler and then the all-rounder ?
Scale is defined as : the percentage of difference between the best rating in the same catogory of the player.


### Space for improvements


More specific data collection is one area to check. Public availability is the issue. Then the clustering can be improved; that’s why for longer betterment agglomerative clustering is used. Still all-rounders can be more analysed. With available data it is done much effectively, but more can be possible.
For batters, features like dot balls, can be utilised for form calculation.

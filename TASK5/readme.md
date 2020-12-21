# Task 5
## About the Task

	Perform ‘Exploratory Data Analysis’ on dataset ‘Indian Premier League’
	As a sports analysts, find out the most successful teams, players and factors contributing win or loss of a team.
	Suggest teams or players a company should endorse for its products.

![Task5](https://github.com/voldemortuk/Data-Science-and-Business-Analytics-Internship/blob/main/TASK5/Task5.png)

# About the dataset
### The dataset has 18 columns. Let’s get acquainted with the columns.
	id: The IPL match id.
	season: The IPL season
	city: The city where the IPL match was held.
	date: The date on which the match was held.
	team1: One of the teams of the IPL match
	team2: The other team of the IPL match
	toss_winner: The team that won the toss
	toss_decision: The decision taken by the team that won the toss to ‘bat’ or ‘field’
	result: The result(‘normal’, ‘tie’, ‘no result’) of the match.
	dl_applied: (1 or 0)indicates whether the Duckworth-Lewis rule was applied or not.
	winner: The winner of the match.
	win_by_runs: Provides the runs by which the team batting first won
	win_by_runs: Provides the number of wickets by which the team batting second won.
	player_of_match: The outstanding player of the match.
	venue: The venue where the match was hosted.
	umpire1: One of the two on-field umpires who officiate the match.
	umpire2: One of the two on-field umpires who officiate the match.
	umpire3: The off-field umpire who officiates the match

## Visualisation

![Task5](https://github.com/voldemortuk/Data-Science-and-Business-Analytics-Internship/blob/main/TASK5/Teams.png)

![Task5](https://github.com/voldemortuk/Data-Science-and-Business-Analytics-Internship/blob/main/TASK5/top_players_ipl.png)


![Task5](https://github.com/voldemortuk/Data-Science-and-Business-Analytics-Internship/blob/main/TASK5/toss.png)



![Task5](https://github.com/voldemortuk/Data-Science-and-Business-Analytics-Internship/blob/main/TASK5/visualise.png)

# Observations:
### The following inferences can be made from the describe() method:
	The .csv file has data of IPL matches starting from the season 2008 to 2019.
	The biggest margin of victory for the team batting first(win_by_runs) is 146 runs.
	The biggest victory of the team batting second(win_by_wickets) is by 10 wickets.
	75% of the victorious teams that bat first won by a margin of 19 runs
	75% of the victorious teams that bat second won by a margin of 6 wickets.
	There were 756 IPL matches hosted from 2008 to 2019.

## Conclusion
	Mumbai Indians is the most successful team in IPL and has won the most number of toss.
	There were more matches won by chasing the total(419 matches) than defending(350 matches). So yeah winning the toss might be an advantage for winning the game
	The presence of the valuable players in a team does not ensure the IPL trophy because as you see teams like Royal Challengers Bangalore.
	It is also seen that Chris Gayle is the most valuable player and other top players can be used by companies to endorse their products for publicity

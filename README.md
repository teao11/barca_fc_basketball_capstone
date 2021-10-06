# First Segment Presentation 

## Selection Topic
With the 2021-2022 NBA season upon us, our team has decided to analyze NBA data to determine what makes a championship team. We aim to identify key factors of past teams to help predict this upcoming season's champion. 


## Reason for Selecting Topic
As fans of the NBA, we wanted to use the skills we learning in this Boot Camp to analyze the sport we all enjoy watching. The NBA is a huge franchise that has large data sets readily available. We aim to take the data to create a model that helps us identify successful NBA teams.  


## Description of the Source of Data
We have three main data sources. 
1. https://www.nba.com/stats/

This dataset is from the NBA official website that provides data through an API we are able to access. 

2. https://www.kaggle.com/wyattowalsh/basketball

This dataset is updated daily and contains data on all games, all teams, and all players within the NBA including:
60,000+ games (every game since the first NBA season in 1946-47) including for the games in which the statistics were recorded:
-Box scores, Game summaries, Officials, Inactive players, Linescores, Last face-off stats, Season series info, Game video availability
30 teams with information including:
  -General team details (stadium, head coach, general manager, social media links, etc), Franchise history information (name changes, location changes, etc)
4500 players with:
  -Basic draft data, Prior affiliations, Career statistics. Anatomical data (height & weight)
and more, with plans for expansion!

3. https://github.com/fivethirtyeight/data/tree/master/nba-raptor

---
files:
  - https://projects.fivethirtyeight.com/nba-model/2021/latest_RAPTOR_by_team.csv
  - https://projects.fivethirtyeight.com/nba-model/2021/latest_RAPTOR_by_player.csv
---
# nba-raptor

This folder contains data behind the story [Introducing RAPTOR, Our New Metric For The Modern NBA](https://fivethirtyeight.com/features/introducing-raptor-our-new-metric-for-the-modern-nba) and the interactive [The Best NBA Players, According To RAPTOR](https://projects.fivethirtyeight.com/nba-player-ratings/).


`modern_RAPTOR_by_player.csv` contains RAPTOR data for every player broken out by season since 2014, when NBA player-tracking data first became available.

`modern_RAPTOR_by_team.csv` contains RAPTOR data for every player broken out by team, season and season_type since 2014, when NBA player-tracking data first became available.

These "modern" data files contain the box score and on/off plus-minus components of RAPTOR, which are then combined into a total RAPTOR rating.


`historical_RAPTOR_by_player.csv` contains RAPTOR data for every player broken out by season since the 1976 ABA-NBA merger.


`historical_RAPTOR_by_team.csv` contains RAPTOR data for every player broken out by team, season and season_type since the 1976 ABA-NBA merger.

These "historical" data files use full player-tracking RAPTOR for seasons since 2014, a version of RAPTOR that mixes box score value estimates with single-year regularized plus-minus data for seasons from 2001 through 2013, and a version of RAPTOR that only uses a box score estimate of value for the seasons from 1977 through 2000. In each era, the RAPTOR version with the highest level of detail is the version used.


The linked file `latest_RAPTOR_by_player.csv` contains RAPTOR data for every player in the latest season.

The linked file `latest_RAPTOR_by_team.csv` contains RAPTOR data for every player broken out by team, season and season_type for the latest season.

These "latest" data files contain the box score and on/off plus-minus components of RAPTOR, which are then combined into a total RAPTOR rating.



Column | Description
-------|---------------
`player_name` |	Player name
`player_id` |	Basketball-Reference.com player ID
`season` |	Season
`season_type` |	Regular season (RS) or playoff (PO)
`team` |	Basketball-Reference ID of team
`poss` |	Possessions played
`mp` |	Minutes played
`raptor_box_offense` |	Points above average per 100 possessions added by player on offense, based only on box score estimate
`raptor_box_defense` |	Points above average per 100 possessions added by player on defense, based only on box score estimate
`raptor_box_total` |	Points above average per 100 possessions added by player, based only on box score estimate
`raptor_onoff_offense` |	Points above average per 100 possessions added by player on offense, based only on plus-minus data
`raptor_onoff_defense` |	Points above average per 100 possessions added by player on defense, based only on plus-minus data
`raptor_onoff_total` |	Points above average per 100 possessions added by player, based only on plus-minus data
`raptor_offense` |	Points above average per 100 possessions added by player on offense, using both box and on-off components
`raptor_defense` |	Points above average per 100 possessions added by player on defense, using both box and on-off components
`raptor_total` |	Points above average per 100 possessions added by player on both offense and defense, using both box and on-off components
`war_total` |	Wins Above Replacement between regular season and playoffs
`war_reg_season` |	Wins Above Replacement for regular season
`war_playoffs` |	Wins Above Replacement for playoffs
`predator_offense` |	Predictive points above average per 100 possessions added by player on offense
`predator_defense` |	Predictive points above average per 100 possessions added by player on defense
`predator_total` |	Predictive points above average per 100 possessions added by player on both offense and defense
`pace_impact` |	Player impact on team possessions per 48 minutes


## Questions We Hope to Answer With the Data
Below are the questions we hope to answer with the data: 

1. What makes a NBA team successful? 
2. What are the key factors to create a NBA championship team? 
3. Can we predict who is going to win this upcoming season? 

## Presentation Slides
Presentation Slides:
version 1:
https://docs.google.com/presentation/d/1sLljaNjBaziVoXdrJZPzjgaGPekuNLCMFgaZKI03sLc/edit#slide=id.p
version final:
https://docs.google.com/presentation/d/1_aBrX5hRLKyGkbuhyHiQy17jugFiyBu4o-Xa3ZeolZw/edit#slide=id.gf5cf6e2850_1_0


Dashboard Slides: 
https://docs.google.com/presentation/d/1S-JOw4kaB802z592JrC_fm34AwflhuWfwSnhh6CypBQ/edit#slide=id.gefc0770f16_0_30

Final Presentation: 
https://docs.google.com/presentation/d/1_aBrX5hRLKyGkbuhyHiQy17jugFiyBu4o-Xa3ZeolZw/edit#slide=id.gf5cf6e2850_3_2

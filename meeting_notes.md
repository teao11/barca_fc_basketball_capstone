# Meeting Notes for Barca FC

This document will hold notes from previous meetings, with TODOs / action items.

**MODELING OBJECTIVE:** Likelihood of winning given a teams attributes?
- Classification: ideal (NBA champs, conference final teams) vs. non ideal (worst X teams in the league)
- Can use this to take a team and predict their likelihood to win the NBA

-----------------------------------------------------------------------------------------------------------------------------------------------------------------
# September 14, 2021
Present: Harry, Kyle, Jyothi, Krystal

Additional Datasource (SQLite database that Jyothi found)
- Bring this in as structured data
- Join to RAPTOR scores and injury stuff
- Can use to build public tableau

Week One deliverables
- Triangle 

-----------------------------------------------------------------------------------------------------------------------------------------------------------------

## September 11, 2021
Present: Harry, Kyle, Jyothi, Krystal

Discussion about the overall objective and machine learning model
- Kyle -- thought about LA and their chances of winning league based on players / stats / team attributes
  - Also thoughts on LoL -- does a player play better in the playoffs?
- Krystal: Fivethirtyeight link (star players in the league)
  - Data here is already structured

Discussing potential data sources:
- Kyle
  - https://www.nba.com/stats/ -- created webscraping tool to pull salaries
    - Hasn't implemented clicks to next pages yet
  - Created API calls for the players and teams
  - Thinking about how to structure tables in SQL
- Harry
  - https://www.basketball-reference.com/players/a/abdelal01.html
  - Kyle Question: Standardized data vs. creating script / pulling ourselves?

Action Items:
- Collaborate on the diagram (Jyothi and Krystal)
  - Share with the team via Google Slides (or other application that enables collaboration / commenting)
- EDA and documentation of data sources (Harry and Kyle)
  - https://www.nba.com/stats/ (Kyle)
  - https://www.basketball-reference.com/players/a/abdelal01.html (Harry)
  - https://github.com/fivethirtyeight/data/tree/master/nba-raptor (Whoever can take)
- Share initial database tables in word doc w/ Krystal and Jyothi (Kyle)

-----------------------------------------------------------------------------------------------------------------------------------------------------------------

## September 9, 2021
Present: Harry, Kyle, Jyothi, Krystal

**Notes:**
- After all researching topics, we have finalized on: investigating / predicting an NBA teams likelihood to win based on players and other organization features!
- Begun researching various sources that we can utilize to create our database
- Outlined the various tools we want to leverage throughout our project
- Planned next steps and a quick sync for Saturday at 5 PM

**Action Items:**
- Everyone to find 2 data sources and run some EDA on those data sources
- Everyone to read up on machine learning models, to get a better understanding of what we want to build
- Meeting on 9-11-2021 to sync on progress for above items and plan the final tasks for week 1 deliverable

-----------------------------------------------------------------------------------------------------------------------------------------------------------------

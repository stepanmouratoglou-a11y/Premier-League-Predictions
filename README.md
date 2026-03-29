# **Premier-League-Predictions**
#### In this repository, I utilize a dataset I got from football-data.co.uk (https://football-data.co.uk/mmz4281/2526/E0.csv) .This dataset contains the data of all the Premier League matches played until this day.It contains a lot of categories that I explain below.Most of these categories are used in the feature engineering part in order to create more useful categories and after that, they are dropped do avoid data leakage.
The main dataset I use is named E0(1).csv .
#### Explanation of the dataset categories as per football-data.co.uk:
* Div = League Division
* Date = Match Date 
* Time = Time of match kick off
* HomeTeam = Home Team
* AwayTeam = Away Team
* FTHG = Full Time Home Team Goals
* FTAG  = Full Time Away Team Goals
* FTR = Full Time Result (H=Home Win, D=Draw, A=Away Win)
* HTHG = Half Time Home Team Goals
* HTAG = Half Time Away Team Goals
* HTR = Half Time Result (H=Home Win, D=Draw, A=Away Win)

Match Statistics (where available)
* Referee = Match Referee
* HS = Home Team Shots
* AS = Away Team Shots
* HST = Home Team Shots on Target
* AST = Away Team Shots on Target
* HHW = Home Team Hit Woodwork
* AHW = Away Team Hit Woodwork
* HC = Home Team Corners
* AC = Away Team Corners
* HF = Home Team Fouls Committed
* AF = Away Team Fouls Committed
* HFKC = Home Team Free Kicks Conceded
* AFKC = Away Team Free Kicks Conceded
* HO = Home Team Offsides
* AO = Away Team Offsides
* HY = Home Team Yellow Cards
* AY = Away Team Yellow Cards
* HR = Home Team Red Cards
* AR = Away Team Red Cards
* HBP = Home Team Bookings Points (10 = yellow, 25 = red)
* ABP = Away Team Bookings Points (10 = yellow, 25 = red)

### All of the above are dropped , and transformed into categories such as:
* Home Team Days Rest
* Away Team Days Rest
* Home Team Average Goals Last 5 Games
* Away Team Average Goals Last 5 Games
* Home Team Average Goals Conceded Last 5 Games
* Away Team Average Goals Conceded Last 5 Games
* Home Team Average Shots Last 5 Games
* Away Team Average Shots Last 5 Games
* Home Team Average Shots Conceded Last 5 Games
* Away Team Average Shots Conceded Last 5 Games
* Home Team Wins Last 5 Games
* Away Team Wins Last 5 Games
* Home Team Draws Last 5 Games
* Away Team Draws Last 5 Games
* Home Team Losses Last 5 Games
* Away Team Losses Last 5 Games
* Home Team ELO Rating
* Away Team ELO Rating


### The predictions of the Premier League are coming from 2 models which are being compared , and there are Random Forest Classifier and XGBoost Classifier.



# cricket-odi-analysis
Cricket is one of the most popular and most watched team sports in the world. Cricket is a sport that contains a lot of statistical
data. There is data about batting records, Bowling records, individual player records, scorecards of various matches played,
etc. Can be used appropriately to predict the outcome of the game. Most viewers today try to make some kind of prediction. At
some stage of the tournament to see which team will eventually win the upcoming match And thus the tournament. This repo.
aims to solve some problems of forecasting results by identifying key features from a data set .The statistics of the last several
years of cricket include details of players, details of match venue, team, ball to ball. Details are taken, and analyzed to draw
various conclusions. Various other attributes such as how the location or decision of the toss affected the match’s win are also
predicted. I have limited my field of study to ODI tournaments which are held every year.

## The Cricket Dataset
The dataset is obtained from cricsheet.org. Cricsheet for Cricket is Retrosheet. They provide ball-by-ball data for men’s and
women’s Test matches, One Day Internationals, Twenty20 Internationals, some other International T20s and all Indian Premier
League seasons. The data is provided in a zip file, which contains ball-by-ball information of nearly 4000 matches played
between 2006-2019, including Test matches, One Day Internationals, Other One Day Matches, International T20, Indian
Premier League mats.I have provided CSV versions (as an experiment) of all matches. This data is then processed to create
a scorecard file and match the information file.
We are using a dataset of 1,788 ODIs for this project. The dataset provides different parameters for each match divided into
two files. The match information file consists of 1788 rows and 25 columns and the scorecard file consists of 37,963 rows and
23 columns. This dataset includes parameters such as match date, venue umpire, winner, running / wicket etc., along with the
scorecard of each match.
The scorecard provides the performance of each player in each match. Players who have contributed through bowling or
batting are included in the dataset.

## Followed Methodology
The methodology consists of 4 main steps - data preprocessing, data cleansing, data preparation, encoding data. Initially, the
ODI season real-time datasets are taken in CSV format. In the data preprocessing phase, the data is Incomplete, noisy and
inconsistent. The data has to be filled with missing values and corrected for discrepancies. Data preparation is important to
achieve optimal results. this To evaluate various predictor variables involves choosing an outcome measure.I have followed the
following methodology in the course of my project
1. Identified the objective and prepared scorecard and match information files accordingly.
2. Descriptive Analysis of the thus generated data.
3. Statistical Analysis of the data.


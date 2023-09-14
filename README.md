# Cricket-Player-Performance-Prediction-using-machine-learning
The datasets to predict Cricket Player Performance are all from kaggle. For this purpose we have 6 datasets, and by using those we have to predict the best performance of a players. 

# Pre-processing
Initially, I have checked datails of all datasets by the help of info() and describe() method. Along with, handled all null values in all datasets. The following datasets have null values:
   * ODI_Match_Results have 1 column that is "BR (Batting Rate)" that consists of 1322 total values in which 716 are null values.
   * ODI_Match_Totals also have 1 column that is "Target" that consists of 1296 records in which 676 are null values.
In order to remove these null values, I decided to use Iterative imputed appraoch where it estimates missing values multiple times, each time refining the imputed values based on the estimates from the previous iteration. I have not choose any other approch like Drop Rows with Null Values, Fill Null Values with any number, Drop Columns with Null Values or Impute Null Values as it may brings biasness in results.

# Data Preparation
  # Batting Parameters
   ## Batting Average
      The batting average is a key statistic that measures a batsman's consistency in scoring runs. It is calculated as the total runs scored divided by the number of times the batsman has been dismissed.
   ## Strike Rate
      Strike rate measures a batsman's ability to score runs quickly. It is calculated as (Total Runs / Total Balls Faced) * 100. A higher strike rate indicates aggressive batting.
   ## Centuries and Half-Centuries
      The number of centuries (100 runs or more in an innings) and half-centuries (50 runs or more in an innings) indicates a player's ability to score big and consistently contribute to the team's total.   
  # Bowling Parameters
   ##  
         
      

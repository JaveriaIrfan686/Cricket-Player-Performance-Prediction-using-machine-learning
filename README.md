# Cricket-Player-Performance-Prediction-using-machine-learning
The datasets to predict Cricket Player Performance are all from kaggle. For this purpose we have 6 datasets, and by using those we have to predict the best performance of a players. 

# Pre-processing
Initially, I have checked datails of all datasets by the help of info() and describe() method. I have checked null values in all datasets.
   * ODI_Match_Results have 1 column that is BR (Batting Rate) that consists of 1322 total values in which 716 are null values.
   * ODI_Match_Totals
In order to remove these null values, I decided to use Iterative imputed appraoch where it estimates missing values multiple times, each time refining the imputed values based on the estimates from the 
previous iteration. I have not choose any other approch like Drop Rows with Null Values, Fill Null Values with any number, Drop Columns with Null Values or Impute Null Values as it may brings biasness in results. 

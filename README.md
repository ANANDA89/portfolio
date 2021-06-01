# Ananda's Portfolio
# Project 1
## [Stock Price Prediction using Time Series, Econometric, Machine Learning, Deep Learning based models, and Natural Language based technique](https://github.com/ANANDA89/Cappstone-Project-)

+ Predicting future values of stock using Time Series, Econometric ML, DL, NLP techniques.
+ Time Series Techniques include Simple Average, Moving Average, Simple Exponential Smoothening, Holt-Winters Exponential Smoothening. 
+ Econometric Technique includes ARIMA, ARCH, GARCH
+ Machine Learning Techniques (Both Classification and Regression). In Regression the used models are Linear Regression, Random Forest, Gradient Boosting, XGBOOST, and MARS. Classification was done to track Stock Price Pattern Movement.
+ Deep Learning Techniques (Simple RNN, GRU, LSTM).
+ Prediction using Sentiment Analysis (used VADER’s Sentiment Intensity Analyser library).
+ Among Time Series based methods best result was obtained from Holt-Winters Exponential Smoothening.
+ For Econometric based methods best result was obtained using GARCH.
+ MARS yielded best result among Machine Learning based methods.
+ LSTM showed best results for Deep Learning based Methods.
+ Overall among all the models best result was obtained using LSTM based technique.
+ UI Building & Deployment using Amazon-AWS EC2.

# Project 2
## [Medical Cost Prediction](https://github.com/ANANDA89/Medical-Cost-Prediction)

+ A robust model has been designed to understand and predict the medical expenditure of users by analyzing factors such as age, weights, smoking behaviors and lifestyle.
+ The best result was obtained using Gradient Boosting Regressor with a R2 value of 0.897
<img src="/images/new.PNG" width="800" />

# Project 3
## [Customer Segmentation](https://github.com/ANANDA89/Customer-Segmentation)

+ Customer purchase data from a retail establishment with 51,243 transactions is being analyzed.
+ Customers were segmented in three categories Recency, Frequency, and Monetory Value.
+ Customeres were split in four clusters depending on the Recency, Frequency, and monetory value of goods purchased using K means clustering
+ Marketing actions and strategies were proposed based on the the RFM value to bring the probable customers back to store.

# Project 4
## [Loan Prediction](https://github.com/ANANDA89/Loan-Prediction)

+ Data cleaning was done to fill missing values with mode.
+ Exploratory Analysis was performed to understand how other features are related to the target.
+ Feature Engineering was performed and log transformation of a numerical column was done
+ Imbalance in the target variable was removed using oversampling method to resample the data.
+ One Hot encoding and Label encoding were performed on catgorical features.
+ Significant features were selected and standard scaling was applied.
+ Logistic Regression and Gradient Descent Boosting algorithm was applied to select final model.
+ Gradient Descent Boosting yielded best result so it was chosen as final model.

# Project 5
## [Employee Promotion](https://github.com/ANANDA89/Employee-Promotion)

+ Data cleaning was done to fill missing values with mode.
+ EDA was performed to understand how other features are related to the target.
+ Under EDA outlier detection was done,univariate, bivariate , and multivariate analysis were performed.
+ Feature Engineering was done to improve the performance of Machine Learning models. Two new colums were created sum_metric and total _score doing feature engineering.
+ Crosstab was used to find relationship between target variable and one of the feature variables.
+ Grouping & Filtering operation was performed for data investigation.
+ An interactive function was created which shows relationship between the target variable with the feature variables in a user usable format.
+ Feature engineering was also done to identify the employees who got undue promotion despite low performance.
+ Label encoding was performed on categorical features.
+ Imbalancing was removed using oversampling method to resample the data.
+ Feature scaling was performed using standard scaler.
+ Logistic Regression & decission Tree were applied to choose the final model.
+ Decission Tree gave better accuracy so it was chosen.
+ Hyperparameter tuning of the Decssion Tree was done to improve model performance.

# Project 6
## [Movie Recommendation](https://github.com/ANANDA89/Movie-Recommendation)

+ Build an Engine that could take customer inputs like Choice of Actors, Genres etc, and Recommend Movies by analyzing the data.
+ Data was cleaned imputing missing values with mode.
+ Duplicate data was removed keeping the first value.
+ Categorization all other language movies except English as 'Foreign'.Duration of the movies were also categorized in long and short.
+ Movie genres were extracted using Split function and different columns were created signifying genres of each movie.
+ Formula was created to calculate the social media popularity of a movie and after movies were sorted in descending manner to get Top 10 popular movies.
+ Top Grossing movies of each genre were displayed using the Group By Operation.
+ Analyzation of the years was done in which the Box Office made the highest profit using Group By and Aggregate function.
+ Top 5 movies with longer duration was derived and the relation between gross earning of a movie depending on its duration was established.
+ IMDB rating of the movies based on their duration was found out.
+ Reports of different actor depending on Maximum gross amount earned of their movie, participation long/short duration movie,time period of the actors, Average IMDB ratingd of their movie,most common genres in which they acted were found out using Group By and Sort function. 
+ An interactive function was defined to explore Gross and Budget of the movies.
+ A function was defined to recommend best movies based on languages.
+ Transactional Encoder was used so to get the Pivot of all the Movie Genres and thus movies of similar genres were recommended.

# Project 7
## [Drugs Prescription using Reviews](https://github.com/ANANDA89/Drugs-Prescription-using-Reviews)

+ A robust model was designed using ML, and NLP based techniques to find out the most useful drug for each health condition.
+ Different EDA methods were used to find out the pattern among the indepent variables with the dependent one.
+ Data Cleaning was done by removing Numbers, Punctuations, and Stop Words.
+ Sentiment Analyses was done using Vader Lexion model and importing Sentiment Intensity Analyzer.
+ Impact of these Sentiment Scores on the Ratings of the Drugs was observed using GroupBy function.
+ A Function was created to calculate the effectiveness and usefulness scores of the drugs.
+ An interactive function was created using the Ipywidgets to get a list of Most Useful and Most Useless Drugs for each Medical Condition.
+ Duplicate drugs were removed from dataset using drop_dupicates function.
+ Another interactive function was created using Ipywidgets which will print the names of Top 5 Most Useful Drug and Top 5 Most Useless Drugs for a Particular Medical Condition, with their Usefulness Rating.

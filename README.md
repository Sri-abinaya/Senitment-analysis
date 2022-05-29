
Sentiment analysis on tweets data

To perform sentiment analysis on the given dataset. The tweets have been pulled from Twitter and manual tagging has been done. The dataset should be splitted into TRAIN and TEST datasets. Model has been which classifies the given data.
 

## Step by step approach
1. The needed libararies are imported.
2. The path of the dataset is given in the working_dir_path.
3. Next the dataset is reviewed to know about the info, number of rows and columns, and the name of the columns.
4. df[df['Sentiment']==''] is used to know about the sentiment of the tweets.
5. The column with the null values will not be useful for sentimant analysis so they are neglected.
6. Bar graph is used for top 10 locations of tweet.
7. Another graph is used to represent the sentiments of the tweet.
8. The data is pre-processed to remove https, urls, numbers and punctuations from the tweet.
9. The most common words from the tweets are identified like corona virus etc.
10. A function is written to collect the hashtags.
11. Frequency distribution is made for top 10 sentiments.
12. The dataset is splitted into training and testing datasets.
13. Linear model is created to classify the given data.






## Usage of models
1. Generate predictions
2. Compare linear model fits
3. Plot residuals
4. Evaluate goodness-of-fit
5. Detect outliers

Here I used linear regression to find the accuracy.

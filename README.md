# Data-Wrangle-
### REPORT
The analysis is based on the collection and the assessment of the tweet archive of Twitter user @dog_rates, also known as WeRateDogs. WeRateDogs is a Twitter account that rates people's dogs with a humorous comment about the dog. The rating has a denominator ratings of about 10, the numerator however can sometimes usually be above ten, eg 11/10, 12/10, 13/10, 14/10 and so 0n.

Data were gathered from From different sources, Twitter API, twitter archives, the data were cleaned and merge to produces an informative dataframe. From the cleaned dataframe, the following were noticed as an insight:

> 1) The cleaned dataframe ( "twitter_archive_master.csv" )  consists of 26 columns with 1973 entries with no missing values.
> 2) The result from the analysis of the cleaned dataset the mean rating (numerator ) is 10.565129, however some numerator rating are higher than 10, eg 11, 12, 13, 15 and so on.
> 3) Also, regarding the ratings (numerator), the minimun value is 0, with the maximum rating been 27, while 75% of the rating ( numerator) is 12 out of the total entries of 1973 data in the cleaned dataframe.

For further insight, information was visualized using seaborn to deploy scatterplot in visualizing the ralationships between two factors. The relationship between Favourite counts and retweet counts was appraised to check the correlation between these 2 factors. From the Visual, it was evident that there is strong positive correlation between favourite counts and Retweet counts. which implies that the higher the favourite count the higher the retweet counts.

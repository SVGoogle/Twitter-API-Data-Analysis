# Data Analysis of Twitter user WeRateDogs

The dataset for the wrangling project (and analyzing and visualizing) is the tweet archive of Twitter user @dog_rates, also known as [WeRateDogs](https://twitter.com/dog_rates?s=20). WeRateDogs is a Twitter account that rates people's dogs with a humorous comment about the dog. These ratings almost always have a denominator of 10. The numerators, though? Almost always greater than 10. 11/10, 12/10, 13/10, etc. Why? Because ***"they're good dogs Brent."*** WeRateDogs has over 4 million followers and has received international media coverage.

## Gathering Data
The relevant data is retrieved by getting each of the three pieces of data as described below:
1. The WeRateDogs Twitter archive of tweets up to to August 1st, 2017.
2. The tweet image predictions, i.e., what breed of dog (or other object, animal, etc.) is present in each tweet according to a neural network.
3. Additionaly, each tweet's retweet count and favorite ("like") count is gathered by querying the Twitter API using Python's Tweepy library.
     
## Cleaning Data
Further each dat piece is assesed and cleaned before analysing and plotting the insights.

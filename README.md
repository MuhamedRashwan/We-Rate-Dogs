# WeRateDogs - Data Wrangling

## Introduction
In this project I will gather data from a variety of sources and in a variety of formats, assess its quality and tidiness,
then clean it. This is called data wrangling. I will document my wrangling efforts in this Jupyter Notebook, plus showcase 
them through analyses and visualizations using Python (and its libraries) and reports.

Our goal in this project will be to make the data ready through the process of Gathering, Assessing and cleaning the data in order to use it for our analysis to answer
our reseach question which are:
1. What are the top 5 most favourited tweets to date?
2. What are the top 5 most retweeted tweets to date?
3. What Does the distribution of rating looks like?
4. What are the top 10 Dog breeds regarding tweet count?
5. What does the correlation between retweet count and favourite count looks like closely?
6. What Months has the highest number of Retweets and Favorites?

The dataset that I will be wrangling (and analyzing and visualizing) is the tweet archive of Twitter user [@dog_rates](https://twitter.com/dog_rates), 
also known as [WeRateDogs](https://en.wikipedia.org/wiki/WeRateDogs). WeRateDogs is a Twitter account that rates people's dogs with a humorous comment 
about the dog. These ratings almost always have a denominator of 10. The numerators, though? Almost always greater than 10. 11/10, 12/10, 13/10, etc. 
Why? Because "[they're good dogs Brent.](https://knowyourmeme.com/memes/theyre-good-dogs-brent)" WeRateDogs has over 4 million followers and has received 
international media coverage.

## Author
This project was completed by Muhammad Rashwan.<br>
FEB 2021.

## Conclusion
**After analyzing this data, we can conclude the findings as follow:**
1. The distribution of ratings is very skewed to the left. From the descriptive statistics above we see that 75% of all ratings are between 10 and 14 inclusive (the IQR is from 10 to 12).
2. The most common dog that is tweeted about, with almost 160 tweets, is the Golden Retriever, as identified (predicted) by the neural network.
3. We can see a high positive correlation between `retweet count` and `favourite count`.
4. The Highest number of Retweets and Favorites were in January and December.

## References and Citation:
- https://stackoverflow.com/questions/25741214/how-to-use-colormaps-to-color-plots-of-pandas-dataframes
- https://code.i-harness.com/en/q/19c9fbc
- https://d17h27t6h515a5.cloudfront.net/topher/2017/August/599fd2ad_image-predictions/image-predictions.tsv
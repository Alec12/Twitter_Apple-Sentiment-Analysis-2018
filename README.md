# Twitter_Apple-Sentiment-Analysis-2018

Here, I analyze the twitter sentiment of the new Apple Iphone using data pulled from the Twitter API, downloading tweets with the tag "Iphone." I hire 5 individuals from AmazonTurk to rate the tweets from -2 (very negative) to 2 (very positive) and then average the scores each individual assigned. The tweets with an average of -2 or -1 are considered "negative" while the remaining tweets are considered "not negative." 

See the "cleaning" document to see how I convert the data into a corpus, and finally how I clean the data to prepare for modelling.

See the "build_model" document to see how I apply Random Forest, CART, Cross-Validated Random Forest, Logistic Regression, Stepwise Regression, Boosting, and Linear Discriminant Analysis on the dataset.

# python_final_pro
First step - understanding business need

Second step - Data Understanding-
At this stage we used different functions in order to understand how the data looks

Third step - Data Preparation
First, we saw that in some of the flights in the data, each airline, each destination, each source appears. After that we found out which is the most frequent airline in the data, which is the most requested destination and which is the origin from which they fly the least.

Fourth step - Modeling
In this part we ran a clustering model using the kmeans algorithm
Since this is a supervised problem, - a problem in which we have a labeled data set.
In addition, we ran an instance of RandomForest that uses 25 different trees for the classification model.

Fifth step - Evaluation
At this point we presented the results from part 4 in detail.
And we presented the confusion matrix that can be summed up in the accuracy index which is in the range 0.8-0.7

Conclusions:

It can be learned that we were able to predict with a fairly high degree of accuracy the domestic flight prices of the flights in India based on the column of the route, the airline and the date (in the date of the month).

From the kmeans algorithm we learned the answer to the question
Into how many groups can the flights be divided so that in each group there will be flights that are similar to each other? (in terms of airline, route, etc.)
The answer that came up is that the optimal division would be into 3 similar groups.
The silhouette index shows us how successful the division was.
The silhouette index came out to us around 0.43, and from this we can learn that the division was between good and controversial because the value is in the range between zero and one.

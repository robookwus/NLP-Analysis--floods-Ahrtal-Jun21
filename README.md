work progress:
XXXXXXXx00 ~77%

docs progress:
XXX0000000 ~30%
sub.wiki ~1%

latex progress:
XXXXXXx000 ~65%

next tasks: add stuff to latex (intro etc)
would be nice: geolocation using twitter api
add ideas in the end that we did not get to.

(full) days left to submit = 3
# NLP-Analysis--floods-Ahrtal-Jun21
Analyzing how the floods in the German Ahrtal (Jun21) impacted the public opinion regarding climate change.

Our main focus here is to find the answers to the following major questions:

1: Total number of tweets (frequency) each day before and after the floods.                                                                                       
2: Overall intensity of all the tweets pre- and post- event.                                                                                                
3: Overall intensity of the tweets of the same users pre- and post- event.


DATA description:
We used the twitter data for the analysis.
The data consists of three columns:

date: shows the date with exact timestamp when the tweet was made.                                                                                          
User: The name of the user who did the tweet                                                                                                                  
Tweet: The content of the tweet                                                                                                                               

For the purpose of analysis, we feauture engineered a new column 'Rating (0/1/2)', which reflects the intensity (how strong a tweet is when it comes to expressing emotions regarding climate change) of tweets.

Some of the values of this new column were manually annotated (around 200), and for the purpose of predicting the reamining labels (Rating (0/1/2)), we used Support vector machine classifiers. Bag of words approach was used to do the analysis. We didn't take into account the discourse or dependencies among the words in a sentence. Because of small dataset (around 200 datapoints), SVM was used as it is one of the best ML method for small dataset and works really well even without optimization.

MIT License 2022.
maybe look into creative commons for writing


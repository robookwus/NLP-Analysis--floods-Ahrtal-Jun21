work progress:
XXXXXXXXXX ~100%

next tasks:
delete sub.wiki

### ! >>>> Recent edit: replaced intensity with classification in this readme-file.


# NLP-Analysis--floods-Ahrtal-Jun21
Analyzing how the floods in the German Ahrtal (Jun21) impacted the public opinion regarding climate change.

Our main focus here is to find the answers to the following major questions:

1: Total number of tweets (frequency) each day before and after the floods.                                                                                       
2: Overall classification of all the tweets pre- and post- event.                                                                                                
3: Overall classification of the tweets of the same users pre- and post- event.

---------
Tweet Custom Classification, based on self-labelled dataset. 
Employing a new idea: #cherrypicking Cherry-Picking.
0: Not interested in change at all, climate change is a lie.
1: I do not know, no opinion (not leaning towards either side strongly)
2: Climate Crisis is NOW.
---------


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


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

1: Total number of tweets (frequency) each day before and after the floods.\n
2: Overall intensity of all the tweets pre- and post- event.\n
3: Overall intensity of the tweets of the same users pre- and post- event.\n



For the purpose of predicting labels (Rating (0/1/2)), we used Support vector machine classifiers. Bag of words approach was used to do the analysis. We didn't take into account the discourse or dependencies among the words in a sentence. Because of small dataset (around 200 datapoints), SVM was used as it is one of the best ML method for small dataset and works really well even without optimization.

MIT License 2022.
maybe look into creative commons for writing


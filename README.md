# Natural Language Processing on restaurant review 
Here we first read in the tab separated dataset and then we need to clean up the data before we do the bag-of-word model


1. lower case every word in a string
2. split the string to a list of words
2. remove stopwords using nltk tool set
3. keep letters only, remove punctuation using re class
4. join the words and append to the complete list


then use the complete list to do the bag-of-words using countvectorize
apply naive bayes to train the data set, and it looks like the accuracy is 72 percent based on the confusion matrix 





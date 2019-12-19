# Document Classification Using Machine Learning 
This is a Machine learning project to perform text classification on the famous Reuters corpus using machine learning models. In this, I 
have read some text files and classified them according to their labels. "Data" folder contains all the files from the Reuters corpus that
are required to perform classification. There is more information about this dataset available on http://disi.unitn.it/moschitti/corpora.htm.

# Steps involved:
1. A function to extract a Pandas's Dataframe containing: (1) headline, (2) text, (3) bip:topics,(4) dc.date.published, (5) itemid, 
(6) XMLfilename. Consider that each news can belong to more than one topic. I have considered only one label among multiple bip topics assigned
to each document making it as Single-label, multi-class problem.
2. A function to perform text preprocessing including removal of stop words, removal of all the words except nouns, stemming and 
lemmetization
3. A function to find all the possible values for bip:topics. 
4. TFIDF, dividing data using train-test-split approach and cross validation approach, and tried multiple classifiers on the data set.
5. Grid Search to perform hyper parameter tuning

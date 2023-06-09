# POS classificatiuon in russian language using ML models
 
Educational project on classification of words in russion language by part of speach.  
Dataset was taken from https://github.com/natasha/nerus.
Different attributes of words were tested as classification features and theese were selected: lenght, first letter, last letter, second to last letter and third to last letter.
KNN, naive bayes algorithm and linear regression were used as base models. Then a comparation between different ensembling methods was performed.  
Among those methods were: Stacking, Pasting, Bagging, Random forest and gradient boosting. For educational purposes some of those methods were implemented independently and compared with their versions in skl.

Best accuracy reached on dataset from 7 classes was 0.92 on by knn with k = 1
Best accuracy reached on dataset from 13 classes was 0.91 by random forest with n_estimators = 300, max_depth = None and max_samples = 6000 (0.6 from dataset length)

# DSL_project

Project carried out for the 2021-2022 course "Data Science Lab", belonging to the first year of the MSc in Data Science and Engineering of Politecnico di Torino

# Summary

In this project, a sentiment analysis of a collection of Twitter posts is addressed. The proposed approach starts with several text preprocessing steps, that include dataset cleaning and word stemming, and finally the creation of a bag-of-words weighted using the tf-idf method. The obtained transformed dataset is then used to train and validate two models, that are a Linear Support Vector Machine Classifier and a Multinomial Naive Bayes Classifier. The tuned models, using the f1 macro score as evaluation metric, are able to outperform the baseline and to reach good results.
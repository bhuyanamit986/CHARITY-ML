# CHARITY-ML
In this project, we will employ several supervised algorithms of your choice to accurately model individuals' income using data collected from the 1994 U.S. Census. We will then choose the best candidate algorithm from preliminary results and further optimize this algorithm to best model the data. Our goal with this implementation is to construct a model that accurately predicts whether an individual makes more than $50,000. This sort of task can arise in a non-profit setting, where organizations survive on donations.  Understanding an individual's income can help a non-profit better understand how large of a donation to request, or whether or not they should reach out to begin with.  While it can be difficult to determine an individual's general income bracket directly from public sources, we can (as we will see) infer this value from other publically available features.   The dataset for this project originates from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Census+Income). 

# Conclusion
___

Here we prepocessed our data, choose the best performing model and did feature selection to filter out important features that can reduce the time taken for training and testing. Random Forest is able to give better results on both accuracy score and Fbeta score therefore, I think this is the appropiate model to choose. we got final accuracy of:

Final Model trained on full data
Accuracy on testing data: 0.8590

F-score on testing data: 0.7331

Final Model trained on reduced data
Accuracy on testing data: 0.8439

F-score on testing data: 0.6882

# Earning Manipulation-Fraud Analytics

Since the data was highly imbalanced, it is prefferd to use ensemble methods. And after training various model we can see that RandomForest Classifier and Voting classifier are most suitable for Manipulator prediction.

Initially we used Logistic Regression which gave an accuracy of 81.65%. But then after applying variour ensembling techniques we got 92% accuracy for VotingClassifier	and AdaBoostClassifier.

Later, on testing these classifers on CompleteData we got 97% accuracy for Random Forest and Voting Classifier. And GradientBoostingClassifier, BaggingClassifier, AdaBoostClassifier and SVC are having an accuracy of 96% and 95% which can also be taken into consideration.

# counterfeit_note_detection
Can we predit whether a note is false or counterfeit using supervised learning? We will implement K-fold cross-validation method. On each fold, we will train Linear Discriminant Analysis (LDA) classifier and logistic regression classifier and look at their accuracies for each fold to decided on a better method of classification. 
After that, we will repeat the K-fold cross-validation on the dataset that has been preprocessed: factor analysis through
maximum likelihood estimation and see its effects on the accuracies of the two models in each fold of the cross validation

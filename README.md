# SVC_hyperparameter_tuning
This project demonstrates the process of hyperparameter tuning for a Support Vector Machine (SVC) classifier using Scikit-Learn ,with hand and using GridSearch, . The goal is to optimize the model's parameters to achieve the best accuracy performance on the given dataset.

Results 🏆

Best Parameters(by hand): {'kernel': 'poly' , 'degree': 4}
Test Accuracy(by hand): %87

Best Parameters(by GridSearch): {'kernel': 'poly' , 'degree': 4}
Test Accuracy(by GridSearch): %90

My Observations 🧐

The accuracy of Grid Search turned out to be better. I think the cross-validation and C parameters used are different from the ones I set manually.

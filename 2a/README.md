# Results of exercise 2a
## Cross-validation
The cross-validation was done with Grid-Search. It has been done first on a small subset of the training set (1000 digits) with 5 folds and then on the whole training set but with limitation in order to limit the time of computation : 3 folds and 100 iterations as a maximum.
### Results during cross-validation
* For the CV on small subset : Please look at the table under the section "SVM from Scikit-learn" in the Group exercise 2a.ipynb" file here on Github
* For the CV on whole training set : Please look at the table under the section "SVM from Scikit-learn" in the pdf file "Results_SVM_trained_on_all_training_set"

### Results on the test set
* Accuracy with the SVM trained on small subset : 88.19%
* Accuracy with the SVM trained on whole training set : 83.86% (this is certainly due to the restriction during CV)

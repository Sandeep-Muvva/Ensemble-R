# Ensemble-R
This reposoitory features about Ionosphere database provided by UCI repository
We used ensemble methods to find better models than the ones we have individually as sub models
We combine different models and acheive better accuracy
We use the following 3 ensemble methods: Boosting, Bagging and Stacking
Of the 3 we found stacking did best as being a supervisor model by combing 5 different models namely 
Linear Discriminate Analysis (LDA)
Classification and Regression Trees (CART)
Logistic Regression (via Generalized Linear Model or GLM)
k-Nearest Neighbors (kNN)
Support Vector Machine with a Radial Basis Kernel Function (SVM)
Through stacking we are able to acheive 95.2% accuracy which cannot be obtained using normal models or sub-models alone

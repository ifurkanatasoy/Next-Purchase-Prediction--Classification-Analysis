# Next Purchase Prediction

**Since this is a hobby project, it was not written with a clean code approach. Moreover, of the studies mentioned below, only some part of codes from the works have been added to the repo. Further, since it is a datathon, the dataset has not been published due to the privacy.**

The provided dataset contained some demographic information about customers and information about the products they purchased. We were supposed to predict the products that the customers that given for submission will purchase. But the data was very unbalanced, so we tried to balance the data by deleting outliers from the majority class.

The problem is analyzed by experimenting with many different techniques and models such as automatic determination of numerical, cardinal and categorical columns with a pre-written class, imputing for null values, both one-hot and label encoding, deleting outliers in the majority class in order to balance the data, data scaling, different classification models (random forest, gradient boosting models etc.) and searching algorithms for the best hyperparameters.
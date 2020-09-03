# data_mining
Discover those factors that contribute to the difference in income of US adults. Build model to predict income each year of US adults based on their given profile. 

Dataset Description:
The Census Income Data Set was extracted by Barry Becker from the 1994 US Census Database. The data set consists of 14 attributes with anonymous information such as occupation, age, native country, race, capital gain, capital loss, education, work class and more. Each row is labelled as either having an annual income of  ">50K" or "<=50K". This data set is already separated into train and test sets with 32561 rows and 16281 rows each.
The categorical attributes are: work class, education, education number, marital status, occupation, relationship, race, gender, native country. The continuous attributes are: age, final weight, capital gain, capital loss, hours per week. This data set is obtained from the UCI repository, and it can be found at: http://mlr.cs.umass.edu/ml/datasets/Census+Income

Machine Learning Methods:
We will apply classification models in the order of logistic regression, Naive Bayes, decision tree, random forest, adaptive boosting and gradient boosting. At the beginning, simple models like binary logistic regression will act good as a baseline and be easy to interpret. From the results, we could understand the relative importance of the variables and whether they are relevant or not. We will then move on to tree-based models and fine-tune them with subtle adjustments. Finally, we will apply the tuned models to the test set and compare their performance by accuracy and AUC.


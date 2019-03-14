# House-category
This ML code based on the data predicts whether a real estate is good,awesome or bad
Currently accuracy is 95.53%. Accuracy can be improved by increasing the dataset

# Steps
# 1
First the data was cleaned. Un-necessary columns were removed.Object datatype were then converted to Categorical datatype. Then these categorical datatype were converted to numerical attributes using catcodes
# 2
The model classifies property, whether it is bad,good or awesome. So the grades column were split into three columns of name bad,good and awesome with values either 0 or 1, True or false.Multiclassification problem
# 3
The dataframe was converted into two arrays. Then using KERAS API , deep neural network was trained with SGD optimizer and 1000 iterations, resulting in 95.53% accuracy.
# 4
Code was done in one commit, within 2 hrs.

# Reference
KERAS Documentation
My previous codes done in Kaggle

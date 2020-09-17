# Music-Genre-Prediction
#This Project aims at predicting the genre of the song as a rock or HIP HOP song.<br>
#We are given with two datasets one for rock songs and one for Hip Hop songs.<br>
#Two datasets are merged using pandas merge and selected only required columns from two datasets<br>
#Standardisation was applied using sklearn preprocessing module to avoid the bias<br>
#PCA was used to find the most important features using cumsum variance plot<br>
#train test split was applied using sklearn train test split<br>
#Decison tree and Logistic regression are applied but the results are not satisfatcory because of imbalanced dataset<br>
#Downsampled the majority class to match with minority class<br>
#This time accuarcy was imporoved a little bit because of balanced class<br>
#Tested the model with crosss validation of 10 folds.

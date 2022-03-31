# Machine_Learning_Projects
Hey folks, find amazing projects of Machine Learning with different models and Tkinter.

Project Description:

The project is spam and ham mail classifier as we get lots of mail every day and we need to know in which category the mail comes under.
This project is build by using the dataset which is spam.csv uploaded in the repo. This project uses the MultinomialNB model of Naive Byes classifier. Which is best model for classification of the text. 
You can check here:http://scikit-learn.org/stable/modules/naive_bayes.html
Also, i have created end to end project as by using Machine Learning using Tkinter GUI. This GUI consist of the text and button as you place your mail into the text and submit it will give you the notification about the spam na ham message. 
Steps:

1) Importing important and required libraries. 
2) Importing dataset using pandas
3) Checking shape of dataset
4) Removing duplicate entries in dataset
5) Again checking shape
6) Renaming columns as v1--> labels, v2--> message
7) checking if any dataset value is null or not in our case we are good to go
8) Now our o/p should in the 1 and 0 format so basically we need to replace spam = 1 and ham = 0
9)  1. Remove punctuations like ,.!# we will do this by using regex.
    2. Removing stopwords
    3. Converting each string into a list of words sepereted by comma because we want list of words
10) Now, message is in text format so we need to convert it into number of matrix so we use vectorizer library you can learn more from here:http://scikit-learn.org/stable/modules/feature_extraction.html
11) Splitting train set and test set.
12) Applying MultinomialNB Check here: http://scikit-learn.org/stable/modules/naive_bayes.html
13) checking accuracy and confusion matrix
14) Creating a predict function so that whenever we pass any text so it shoul get clean then apply to feature extraction and gives us a prediction
15) Creating the Tkinter GUI conntains label, Entry data and Buttons.

Thank You Guys!!! Share with this your friend.
   

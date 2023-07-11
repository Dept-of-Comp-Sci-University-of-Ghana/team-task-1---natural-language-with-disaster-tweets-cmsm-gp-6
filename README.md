[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/sRMOJrsa)
We first of all imported all the neccesary libraries
After this, we loaded the train and test data 
In the preprocessing approach, we removed all links, stopwords and special characters.
We also converted all words to the lower case form and stemmed them to their base form.
We then converted the features into a binary form using count vectorizer so that it can be learned by the model.
Before fitting the dataset, we split the train data into train and validation dataset since we have to use the test set only once. 
The model used in fitting the dataset is the svm model.
After we fitted the data to the model, we made predictions on the validation dataset
Our accuracy was 0.81985
We then preprocessed the test and make predictions to obtain the desired target.

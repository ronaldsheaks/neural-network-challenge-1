# neural-network-challenge-1
Module 18 Neural Networks - Recommendation Systems

Wednesday, September 25th, 2024:

Created Repo

Added starter code to repo

Pushed changes

Uploaded notebook to Google Colab

Imported dependencies

Read csv

Reviewed data types

Checked "credit_ranking" value counts

Defined "y"(label) as "credit_ranking"

Defined "X" as all features except "credit_ranking" by dropping the "credit_ranking" column

Split the data into training and testing datasets

Checked shape of training and testing datasets

Created "StandardScaler()"

Fit/transformed the scaler to training dataset

Fit/transformed the scaler to the testing dataset

Reviewed scaled features

Created a deep neural network by:

Defining number of inputs(same as the scaled shape of "X_trained_scaled"), which is 11 features

Defined a sequential model

Added the first dense layer with 16 neurons and a relu function

Added second dense layer with 8 neurons and a relu function

As the output layer is a binary classification(whether or not a student loan will be repaid based on "credit_ranking"), a dense layer with one neuron and a sigmoid function is used

Displayed model

Compiled model using "adam" optimizer and "binary_crossentropy"

Fit model using 50 epochs

Evaluated model

Saved model as .keras file

Reloaded model

Made predictions with "X_test_scaled" data by converting the predictions to binaries, and creating a df to store the predictions, where predicted variables were flattened to 1D

Printed classification report

Answered discussion questions








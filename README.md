# Assignment_10

In class programming:

Save the model and use the saved model to predict on new text data
(ex, “A lot of good things are happening. We are respected again throughout the world, and that's a great thing.@realDonaldTrump”)
Apply GridSearchCV on the source code provided in the class


A) In this code we are first creating basic packages like pandas and numpy for loading dataframes and dataset and we are also using matpotlib for data visualization, additionally we are importing package for regular expressions. Here Labencoder is also used for converting cateogerical to numerical.From goggle colab platform we are importing drive where we can access the content in it. We are also loading dataset as dataframe and we are selecting only necessary columns text and sentiment and keeping only necessaary columns and removing retweets then we are using maximum words as 2000 to tokenize sentence and also taking values to feature matrix, padding the feature matrix and we are using dimension of the embedded layer as 128, and long short term memory layer neurons as 196 and also using sequential neural network, adding input dimension as 2000 neurons and output dimension 128 neurons. After we are compiling the model and printing model summary. Subsequently we are applying label encoding on the label matrix and then fitting the model, we are using 67 percent of training data and 33percent test data split and using batch size as 32 then we are using a function call to sequential neural network then we are evaluating the model and printing the accuracy of the model then actually we are saving the model and used the saved model to predict on new text data then after we are saving the model then after importing the package for the saved model and then laoding it and then we are applying GridSearchCV on the source code provided in the class and finally sumarizing the results.

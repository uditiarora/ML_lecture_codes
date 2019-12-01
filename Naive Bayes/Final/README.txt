The code file named Project implements the code in 3 different parts.
1st part:
    Filters the 20 news_group data and stores the feature table in a file so as to save time later(so that we don't have to compile the same       code again and get our feature table)
    Splits the data, trains the model and runs inbuilt MultinomialNB
2nd part:
    Gets the mini news_group data, filters it, makes feature table according to trained data and applies inbuilt MultinomialNB
3rd part:
    Applies self coded Multinomial Naive Bayes


The accuracy score obtained using both the methods (self implemented and inbuilt) is approximately same and is around 0.89 

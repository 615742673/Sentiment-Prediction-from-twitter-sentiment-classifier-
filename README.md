# Sentiment-Prediction-from-twitter-sentiment-classifier-
# Part1
The code in part1 is to read four embed pickle file and save them as dataframe data structures.This part of work is making preparation for the training part.

# Part2
The code in part2 is firsly separating the attribute in embed dataframe.The TFIDF and Sentiment are extracted and then the data in train_emb.pkl is saved as train data,the data in dev_embed.pkl is saved as test data.Then,three different models are declared and used for training.The confusion matrics(Accuracy,precision,recall) are printed at the end of this part in order to show the performace difference between models.Beside this,the dev_emb data is also broken down into two parts.One part only contains AAE group,another part only contains SAE group.Based on the research question in the report,the code about adjusting parameter of KNN model and Logic regression model are displayed at the end of this part as well.

# Part3
The code in part3 is used for exploring the research question which shows the gap between AAE group and SAE group.The code tries to print the accuracy of AAE group and SAE in each model separtely.

# Part4
The code in part4 is to show the bar chart of accuracy of AAE and SAE group in each model.This part is also used for exploring the research question in the report to show the gap directly.

# Part5
The code in part5 is used for competition in kaggle.It saves the TFIDF attribute from test_emb.pkl as dataframe firstly.Then it predicts the Sentiment based on the previous data.At last,the prediction is saved as a new csv file.

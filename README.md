EXPLORING HUMAN EMOTIONS FOR DEPRESSION DETECTION FROM TWITTER DATA BY REDUCING MISCLASSIFICATION RATE


STEPS:

Final_Integration.ipynb - Contains the full implementation of the project.

Glove 6B.100d.txtfile can be found here: https://drive.google.com/file/d/1s_b22WHKwN09vSn84m8z_12p1NgICqT3/view?usp=sharing
1. It has to be executed in Google Colab link - https://colab.research.google.com/notebooks/intro.ipynb#recent=true 

2. Create a folder in your Google Drive called Colab Notebooks and place the Vader Sentiment folder, messages.xlsx and Book.xlsx inside it.

3. Execute each cell separately.

4. Press ctrl+z to stop the execution of the first cell, once the required tweets are obtained.

5. Continue to ee=xecute the rest of the cells.

LIST OF FILES GENERATED

rawdt.txt - Raw tweets

emodt2.txt - Lemmatized tweets 

masterdb.xlsx - Excel sheet containing username, raw tweet, twitter id and the lemmatized tweet

vaderpos.txt - Positive tweets classified by VADER

vaderneg.txt - Negative tweets classified by VADER

swnpos.txt - Positive tweets classified by SentiWordsNet

swmneg.txt - Negative tweets classified by SentiWordsNet

textblobpos.txt - Positive tweets classified by TextBlob

textblobneg.txt - Negative tweets classified by TextBlob

pos_output_file.txt - Common positive tweets of all 3 dictionaries

neg_output_file.txt - Common negative tweets of all 3 dictionaries

neutral_output_file.txt - Neutral and ambiguous tweets

nns_output_file.txt - Output of NNS Algorithm

masterdb2.xlsx - Confirmed negatives and nns labelled tweets

all_negatives.txt - Common negatives and NNS output

negative_tweets.xlsx - Username, id and tweets of all negatively classified tweets

unicode.txt - Unicode of emoticons derived from negative_tweets.xlsx


negdb_with_pol.xlsx - contents of negative_tweets.xlsx with polarity of emoticons

user_names.txt - Usenames of people whose twitter history has to be extracted

userhistory2.xlsx - User name and user history 



Paper Can be found here for more details:   https://link.springer.com/chapter/10.1007/978-981-16-3802-2_10
 

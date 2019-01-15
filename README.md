## #KAVANAUGH: TWITTER SENTIMENT ANALYSIS & TOPIC MODELLING TO PREDICT VERDICT

### This project was taken up during the time of the Kavanaugh case in order to capture the sentiments of the people about the situations and entities involved via tweets
#### The following analysis was carried out:
1. Build 2 crawlers to scrape twitter to obtain the older tweets and the latest tweets(past 7 days) -> code can be found in tweets_location.ipynb for the last 7 days and the data for the other dates is present in Data folder
2. Carried out lift and sentiment analysis of the individual entities: kavanaugh and ford across the timeline and identified changes based events that took place
3. Calculated changes in lift and sentiment of case wrt Trump in order to identify if this case was impacting the sentiment towards him
4. Carried out Topic modelling at a daily level to identify and changes in the topics the people focussed on based on the events that took place
5. Following were our insights:
  -Sentiment goes up for Kavanaugh since Trump called on FBI investigation
  -3% rise in approval rate for Trump was observed in accordance with our sentiments, after FBI reports were released 
  -The confirmation vote has resulted in changed predictions for control of the House 
  -Hence we would predict that the vote will favor Kavanaugh
 6. The LDA folder contains the Topic modelling files in html format for every day
 7. The gensim files are intermediate files created for the LDA part of the excercise

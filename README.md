# Predicting Funding Outcomes Using XGBoost and Campaign Narratives: Kickstarter Crowdfunding Campaigns
I examined the effectiveness of the communication that entrepreneurs use in their crowdfunding pitches to secure funding for their ventures. I used Natural Language Processing (NLP) and XGBoost machine learning model to predict funding success based on information contained in campaign narratives. 

Data were collected for all Kickstarter campaigns launched in the US in 2016. The campaign text descriptions were web scrapped from [kickstarter.com](https://www.kickstarter.com/). The resulting dataset amounted to 21,711 campaigns: 9,717 funded and 11,994 unfunded.

The resulting model produced a precision score for successfully funded campaigns of 0.75, which was pretty good considering that text predictors had no apriori theoretical basis. That is, among 1,951 funded campaigns, the model correctly classified 1,456 in a holdout test data set using the text data only.

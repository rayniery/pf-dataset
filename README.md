# pf-dataset
Dataset extracted from [r/personalfinance](https://www.reddit.com/r/personalfinance/) for financial sentiment analysis in short texts. The submissions to construct the dataset were taken from October 2017.

It has 546 observations and each observation is a JSON object. They have two fields: *selftext* with the submissions text, and *sentiment*. The criterion used for labeling a submission as positive or negative was *financial distress*. We used the defition of financial distress provided by [Investopedia](https://www.investopedia.com/terms/f/financial_distress.asp): is the condition where a person cannot meet, or has difficulty paying off, its financial obligations.    

This dataset was used for my dissertation for the Master in Data Science at The University of Auckland.
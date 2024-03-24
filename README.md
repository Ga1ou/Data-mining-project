# Data-mining-project
YouTube Analytics
------------------------------------------------------------------
Problem Setting: 
Our domain topic focuses on the prediction of potential views and likes based on several variables such as video producers, keywords and even published data from YouTube Statistics. This analysis may provide significant insight and ideas for many content creators. 
In addition, we could anticipate and foresee the expected views, profits, and level of favor before stakeholders plan to produce the videos. However, there are some challenges for us so far. Firstly, it might need an advanced predictive model to implement in our project for example: Sentiment Analysis. Next, the future trend is hard to follow even if we capture the common keyword recently. Or the correlation of different variables may not be relevant sometimes. Says, comments are or are not proportional to likes. 

Problem definition: 
1) Based on the comments define the positive and negative emotions from the audience and if this would affect the rate of likes.
2) Capture some potential keywords mentioned in publishers’ videos that may correlate with the views. Maybe a certain topic captures someone’s attention. Can we predict their likes and views from their previous content’s statistics?
3) More viewers watch means more likes. Impute the ratio of likes and views
----------------------
Data Sources: 
Our data mainly includes two files: comments.csv and videos-stats.csv. These data come from the Kaggle website, and the following is the link to the data source. https://www.kaggle.com/datasets/advaypatil/youtube-statistics. 

Data Description: 
The comments dataset contains four columns (Video ID, Comment, Likes and
Sentiment) and 18409 rows; the videos-stats dataset has seven columns (Title, Video ID,
Published At, Keyword, Likes, Comments, and Views) and 1881 rows.
1) Using Video ID and Sentiment as independent variables and Likes as dependent variables we
can know the correlation between the sentiment of the comments and the number of likes.
2) To predict the number of likes, comments, and views a newly published video would receive
we would choose Keywords and Published At as independent variables and choose Likes,
Comments and Views as dependent variables.
3) We can figure out whether there are some correlations between the number of views and
the number of likes and comments, using Views as an independent variable, Likes and
Comments as dependent variables. Besides we could add two columns that store the ratio of
likes and views, and the ratio of likes and comments respectively to help us understand.


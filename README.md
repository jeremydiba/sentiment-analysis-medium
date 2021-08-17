# sentiment-analysis-medium
Sentiment Analysis Notebook for my medium article!

All of The data processing I did can be found here!  

Can download the data here
https://www.kaggle.com/datafiniti/consumer-reviews-of-amazon-products/version/5

Results:

NLTK (VADER) \n
reviews.rating  sentiment
1.0             neg          124
                neu            6
                pos          170
2.0             neg          144
                neu            4
                pos          152
3.0             neg           66
                neu            5
                pos          229
4.0             neg           32
                neu            2
                pos          266
5.0             neg           15
                neu            3
                pos          282
TEXTBLOB
reviews.rating  sentiment
1.0             neg           95
                neu           16
                pos          189
2.0             neg           72
                neu            7
                pos          221
3.0             neg           27
                neu            1
                pos          272
4.0             neg           22
                neu            7
                pos          271
5.0             neg            8
                neu            5
                pos          287
FLAIR
reviews.rating  sentiment
1.0             neg          287
                pos           13
2.0             neg          290
                pos           10
3.0             neg          229
                pos           71
4.0             neg           68
                pos          232
5.0             neg           11
                pos          289

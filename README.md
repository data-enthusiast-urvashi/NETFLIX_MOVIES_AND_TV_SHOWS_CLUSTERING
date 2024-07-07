# NETFLIX_MOVIES_AND_TV_SHOWS_CLUSTERING
# **Problem Statement**
This dataset consists of tv shows and movies available on Netflix as of 2019. The dataset is collected from Flixable which is a third-party Netflix search engine.

In 2018, they released an interesting report which shows that the number of TV shows on Netflix has nearly tripled since 2010. The streaming service’s number of movies has decreased by more than 2,000 titles since 2010, while its number of TV shows has nearly tripled. It will be interesting to explore what all other insights can be obtained from the same dataset.

Integrating this dataset with other external datasets such as IMDB ratings, rotten tomatoes can also provide many interesting findings.

## <b>In this  project, you are required to do </b>
1. Exploratory Data Analysis

2. Understanding what type content is available in different countries

3. Is Netflix has increasingly focusing on TV rather than movies in recent years.
4. Clustering similar content by matching text-based features


# **Conclusion**
We have reached to the conclusion of our excercise !!

We started this project with the intention to obtain some useful insights related to the type of Netflix content. For this,we performed exploratory data analysis on our data after cleaning and making it easy to analyse. This analysis helped us to understand the trend . We found that most of the content on Netflix are of TV-MA and TV-14 rating. USA and India are two countries producing the maximum number of content.Documentaries and Stand up are top genre in terms of number of contents they have on platform. Further we found number of movies on Netflix outnumbers TV-shows. Our next job was to make an unsupervised clustering model. For this, we processed our text by removing unuseful characters like - stopwords, punctuation and did stemming.After getting the length for each text feature we rescaled them for generalisation and started applying algorithms. We first used K-means clustering. In order to find appropriate cluster number we used elbow method and finally got the best sillhoute score of around 0.35. Next, we applied Hierarichal Agglomerative Clustering for which we made dendogram. We also obtained sillhoute score of around 0.32. With this we achieved our objectives of the project

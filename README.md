# Unsupervised_ML-Capstone_Project-
This space contains a project on Unsupervised model as a part of Almabetter job guarantee evaluation metrics.

# Problem Statement

Zomato is an Indian restaurant aggregator and food delivery start-up founded by Deepinder Goyal and Pankaj Chaddah in 2008. Zomato provides information, menus and user-reviews of restaurants, and also has food delivery options from partner restaurants in select cities.

India is quite famous for its diverse multi cuisine available in a large number of restaurants and hotel resorts, which is reminiscent of unity in diversity. Restaurant business in India is always evolving. More Indians are warming up to the idea of eating restaurant food whether by dining outside or getting food delivered. The growing number of restaurants in every state of India has been a motivation to inspect the data to get some insights, interesting facts and figures about the Indian food industry in each city. So, this project focuses on analysing the Zomato restaurant data for each city in India.

The Project focuses on Customers and Company, you have to analyze the sentiments of the reviews given by the customer in the data and made some useful conclusion in the form of Visualizations. Also, cluster the zomato restaurants into different segments. The data is vizualized as it becomes easy to analyse data at instant. The Analysis also solve some of the business cases that can directly help the customers finding the Best restaurant in their locality and for the company to grow up and work on the fields they are currently lagging in.

This could help in clustering the restaurants into segments. Also the data has valuable information around cuisine and costing which can be used in cost vs. benefit analysis

Data could be used for sentiment analysis. Also the metadata of reviewers can be used for identifying the critics in the industry.

**Attribute information**

*Dataset for clustering Zomato Restaurant names and Metadata*
Name : Name of Restaurants

Links : URL Links of Restaurants

Cost : Per person estimated Cost of dining

Collection : Tagging of Restaurants w.r.t. Zomato categories

Cuisines : Cuisines served by Restaurants

Timings : Restaurant Timings

*Dataset for Sentimental_analysis Zomato Restaurant reviews(Perform merge with 1st dataset)*
Restaurant : Name of the Restaurant

Reviewer : Name of the Reviewer

Review : Review Text

Rating : Rating Provided by Reviewer

MetaData : Reviewer Metadata - No. of Reviews and followers

Time: Date and Time of Review

Pictures : No. of pictures posted with review

**Project Description**
*EDA* - Performed exploratory data analysis and text preprocessing
*Data Cleaning* - I have to drop the entire feature as there are 50% null values.
*Feature Selection* - For sentiment analysis, I have used rating and reviews features. - For clustering I got cost, cuisine and timing of the restaurant as the features to build the model.
Model development - For sentiment analysis, developed different models like:- Multinomial NB, Logistic regression, Random forest classifier - For clustering the restaurants we have used the k-means.
**Needs of this project**
**data exploration**
**data processing/cleaning**
**text preprocessing/cleaning**
**sentiment analysis on reviews**
**cluster the restaurant into different segments.**
**Sentiment analysis**
-Plotted the distribution of ratings to have an understanding of the proportion of good and bad reviews. -Made many visualizations which include, top 10/bottom 10 restaurants in terms of average rating. -Had a clear understanding of the cost summary of the restaurants. -Done pre-processing such as removing emojis, punctuations and only used Adjectives and verbs to reduce dimensionality. -TF-IDF vectorizer was used to transform the dataset -Built several models such as Multinomial NB, Logistic regression, Random forest classifier etc.

**Clustering**
-Calculated the time each Restaurant was opened weekly. -Did the pre-processing, Clubbed some cuisines together so that one-hot encoding would be possible. -Removed the unwanted variables and Normalized the data. -Clustered the data using K-means as well as Hierarchical clustering.

**Procedure Involved**

**Model Used on data**
K-mean clustering.
Bad of words.
Logistic Regression.
MultinomialNB.
Decision tree.
Random forest.
**Procedure performed and Observations**
 Started with data loading and importing the libraries and then started with exploring the data and looking into columns and rows. Looked for the missing values in the dataset and imputed accordingly.
Did the EDA for the dataset and tried to find out the trend in the data. Got some of the questions like which are the cuisines which are popular and what are the weekly restaurant timings, and explored the cheap restaurants and costly restaurants in the given dataset. I have found that there were prices around 2500-2800 to maximum or costly prices and where 250 rupees to 150 rupees restaurants were the cheapest. I also have explored some commonly used words like good,order, food, India, Chinese etc.
Once data exploration was done I have started clustering using cuisines where 61 being the highest number for the restaurant with North Indian cuisines and having 7 as top 10th was bakery.
**Moved to the Natural Language Processing (NLP)**
I have performed some of the tasks for the text understanding:
Started with Data-loading and data preprocessing where data preprocessing has below steps to perform.
·         Expand Contractions-(don’t to do not).
·         Lower Case-(Convert to lower case).
·         Remove Punctuations-(!?:).
·         Remove words and digits containing digits- (game5ts7 replace with empty string).
·         Remove Stopwords-(This, that, is, am are).
·         Rephrase Text(converting email ids to email address).
·         Stemming and Lemmatization. (Playing to play, and Methodology-Method)
·         Remove White spaces.( simply removal of extra spaces).

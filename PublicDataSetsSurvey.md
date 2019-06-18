# Public Data Sets for Machine Learning Review

This document contains a review of public data sets that are potentially useful for the WDL , specifically regarding the following topics:
1.  Forecasting Datasets (with a temporal component)
2.  Predictive maintenance datasets
3.  Text classification datasets (OCR data sets included)
4.  Relevant supervised learning datasets 

From sources considered top sources for machine learning

## List of Open Data Sources

The following is a lista that contains popular open data sources:

3. Google Public Data Explorer: can help you explore vast amounts of public-interest datasets. It makes the data from different agencies and sources available.
4. *FiveThirtyEight: It provides its various sources of data for a variety of sectors such as politics, sports, science, economics etc.
5. Data.gov: Allows the acces to US government’s open data. There are now 180,000 datasets. (agriculture, climate, consumer, energy, finance, science and research, etc.)
6.  *DBpedia: aims at getting structured content from the valuable information that Wikipedia created.
7. Free code camp: (Web Analytics,  Social Media Analysis, Social Network Analysis, Education Analytics, Data Visualization, Data-driven Web, Development, Bots)
8. Yelp Open Datasets: it contains reviews and user data from the Yelp platform. (TEXT MINING)
9. Kaggle
10. LODUM: It is the Open Data initiative of the University of Münster. Under this initiative, it is made possible for anyone to access any public information about the university in machine-readable formats.
11. UCI Machine Learning Repository: It serves as a comprehensive repository of database used by the machine learning community
12. Microsoft Research Open Data (biology, healthcare, social science etc.)

Search engines:
13. Google dataset search

## 1. Supervised learning

**From Kaggle:**

The following lists contain the 10 most voted data sets for classification tasks according to their size. However, an extended version with the 100 most voted data sets not only for classification but also for regression tasks (according to their size) is attached to this file, which also include more details.

Most voted **"large"** data sets for classification tasks:
1. CelebFaces Attributes (CelebA) Dataset
2. Stanford Cars Dataset
3. Best Artworks of All Time
4. LISA Traffic Light Dataset
5. One-Shot-Pokemon Images
6. Caltech 256 Image Dataset
7. IP Network Traffic Flows Labeled with 75 Apps
8. Street View House Numbers (SVHN)
9. Cute Cats and Dogs from Pixabay.com
10. Malaria Bounding Boxes

Most voted **"medium"** data sets for classification tasks:
1. mlcourse.ai
2. Heartbeat Sounds
3. Blood Cell Images
4. Google-Landmarks Dataset
5. Rain in Australia
6. Genetic Variant Classifications
7. ECG Heartbeat Categorization Dataset
8. News Category Dataset
9. Data Scientist Job Market in the U.S.
10. MotionSense Dataset : Smartphone Sensor Data 

Most voted **"small"** data sets for classification tasks:
1. Heart Disease UCI
2. News Headlines Dataset For Sarcasm Detection
3. Kuzushiji-MNIST
4. Predicting a Pulsar Star
5. Mobile Price Classification
6. Sloan Digital Sky Survey DR14
7. Bank Marketing Dataset
8. Bank Marketing
9. Turkey Political Opinions
10. Sentiment Labelled Sentences Data Set

**From KEEL data repository:**

This page aims at providing to the machine learning researchers a set of benchmarks to analyze the behavior of the learning methods. It also shows some relevant research papers in which these data sets have been employed. It includes 592 data sets in the category of  "supervised classification" divided in the following sub-categories
- Standard classification data sets (76)
- Standard classification data sets with missing values (26)
- Imbalanced data sets for classification (145)
- Multi instance classification data sets (10)
- Multi label classification data sets (16)
- Classification data sets with Class Noise (76)
- Classification data sets with Attribute Noise (228)

## 2. Forecasting Data Sets

**From Kaggle:**

This list contains the 10 most voted data sets (in decreasing order) out of 129 with the tag "time series". They were collected in a way that not only the temporal feature is included but also additional features concerned with the problem under examination. 

1. S&P 500 stock data: Historical stock data for for all companies currently found on the S&P 500 index.
Goal: 
2. Bitcoin Blockchain: Complete live historical Bitcoin blockchain (blocks and transactions)
3. Historical Hourly Weather Data 2012-2017: Hourly weather data for 30 US cities, Canadian Cities, and 6 Israeli Cities. Various weather attributes, such as temperature, humidity, air pressure, etc. are included.
4. Energy consumption of the Netherlands: electricity and Gas consumed in the Netherlands every year different pollution levels in Madrid from 2001 to 2018.
5. DJIA 30 Stock Time Series Historical stock data for 30 DIJA companies (2006-01-01 to 2018-01-01)
6. Ethereum Classic Blockchain: complete live Ethereum Classic historical blockchain data 
7. MotionSense Dataset : Smartphone Sensor Data: Time-series data generated by smartphone's sensors: accelerometer and gyroscope
8.  Accidents in France from 2005 to 2016: Help prevent accidents
9. Weather Data for Recruit Restaurant Competition:  The focus is on using data about reservations made at various restaurants throughout Japan, along with restaurant location and genre information to predict the actual number of visitors a restaurant will have on a given day.
10.  Quality Prediction in a Mining Process: explore real industrial data and help manufacturing plants to be more efficient. The main goal is to use this data to predict how much impurity is in the ore concentrate.

**From UCI machine learning repository:**

This repository contains 93 data sets under the category "Time-Series", which are useful for tasks such as classification, regression, and clustering (https://archive.ics.uci.edu/ml/datasets.php?format=&task=&att=&area=&numAtt=&numIns=&type=ts&sort=nameUp&view=table). 

**From Awsome  Public Data Sets Collection:**

This repository contains around 5 data sets in the category "Time Series".

**From KEEL data repository:**
This repository includes 40 data sets in the category "Time Series".

## 3. Text mining

**From Kaggle:**
1. Women's E-Commerce Clothing Reviews: 23,000 Customer Reviews and Ratings 
2. Amazon Reviews for Sentiment Analysis: a few million Amazon reviews in fastText format
3. Wikipedia Movie Plots: plot descriptions for ~35,000 movies: 
4. Seinfeld Chronicles: complete Seinfeld Scripts and Episode Details
5. Predict Pakistan Elections 2018: help us predict the next winner: 
6. UCI ML Drug Review dataset: over 200,000 patient drug reviews.
7. IMDB Movie Reviews Dataset: perform Sentiment Analysis and Text Classification using this Dataset
8. Star Wars Movie Scripts: this is a collection of script dialogue between characters for the first three movies (episodes 4-6).
9. English Wikipedia Articles 2017-08-20 SQLite: the dataset encompasses nearly 5 million articles, with more than 23 million individual sections.
10. Melbourne Airbnb Open Data: Detailed and summarized data of Airbnb activity in Melbourne, VIC, Australia

*These are the 10 most voted data sets in kaggle out of 189 with the tags "text mining" and "text data".

**From folks recommendations:**

According to people in the machine learning community, the following are the best data sets:

For sentiment analysis: 
- Multidomain sentiment analysis dataset: A slightly older dataset that features product reviews from Amazon.
- IMDB reviews: An older, relatively small dataset for binary sentiment classification features 25,000 movie reviews.
- Stanford Sentiment Treebank: Standard sentiment dataset with sentiment annotations.
- Sentiment140: A popular dataset, which uses 160,000 tweets with emoticons pre-removed.
- Twitter US Airline Sentiment: Twitter data on US airlines from February 2015, classified as positive, negative, and neutral tweets

Natural language processing data sets:
- HotspotQA Dataset: Question answering dataset featuring natural, multi-hop questions, with strong supervision for supporting facts to enable more explainable question answering systems.
- Enron Dataset: Email data from the senior management of Enron, organized into folders.
- Amazon Reviews: Contains around 35 million reviews from Amazon spanning 18 years. Data include product and user information, ratings, and plaintext review.
- Google Books Ngrams: A collection of words from Google books.
- Blogger Corpus: A collection of 681,288-blog posts gathered from blogger.com. Each blog contains a minimum of 200 occurrences of commonly used English words.
- Wikipedia Links data: The full text of Wikipedia. The dataset contains almost 1.9 billion words from more than 4 million articles. You can search by word, phrase or part of a paragraph itself.
- Gutenberg eBooks List: An annotated list of ebooks from Project Gutenberg.
- Hansards text chunks of Canadian Parliament: 1.3 million pairs of texts from the records of the 36th Canadian Parliament.
- Jeopardy: Archive of more than 200,000 questions from the quiz show Jeopardy.
- Rotten Tomatoes Reviews: Archive of more than 480,000 critic reviews (fresh or rotten).
- SMS Spam Collection in English: A dataset that consists of 5,574 English SMS spam messages
- Yelp Reviews: An open dataset released by Yelp, contains more than 5 million reviews.
- UCI’s Spambase: A large spam email dataset, useful for spam filtering.

**From UCI machine learning repository:**

This repository contains 54 data sets under the category "Text", which are useful for tasks such as classification, regression, and clustering.

**From Awsome  Public Data Sets Collection:**

This repository contains around 37 data sets in the category "Natural Language".

**Recommendations from Wikipedia:**
Wikipedia has dedicated an article  that refer to datasets for machine learning research, this includes a section for "Text data", with subcategories such as: reviews, news articles, messages, tweets, etc. (https://en.wikipedia.org/wiki/List_of_datasets_for_machine-learning_research#Text_data)

### Focused on Optical Character Recognition (OCR)

**From Kaggle:**
According to the most voted (decreasing order)
1. NumtaDB: Bengali Handwritten Digits: Build a classification model for Bengali handwritten digits.
2. CAPTCHA Images

**From Awesome Public Datasets:**
 - Chars74K dataset: Character Recognition in Natural Images

**Recommendations from Wikipedia:**
Wikipedia has dedicated an article  that refer to datasets for machine learning research, this includes a section for "Handwritting and character recognition" with 12 data sets (https://en.wikipedia.org/wiki/List_of_datasets_for_machine-learning_research#Handwriting_and_character_recognition)
## 4. Predictive maintenance 

**From NASA:**

Turbofan Engine Degradation Simulation Data Set:
- Description: Engine degradation simulation was carried out using C-MAPSS. Four different were sets simulated under different combinations of operational conditions and fault modes. Records several sensor channels to characterize fault evolution. The data set was provided by the Prognostics CoE at NASA Ames. 
- Link: https://ti.arc.nasa.gov/tech/dash/groups/pcoe/prognostic-data-repository/#turbofan 
Comments: this data set seems to be popular for research about predictive maintenance.


Li-ion Battery Aging Datasets:
- Description: This data set has been collected from a custom built battery prognostics testbed at the NASA Ames Prognostics Center of Excellence (PCoE). Li-ion batteries were run through 3 different operational profiles (charge, discharge and Electrochemical Impedance Spectroscopy) at different temperatures. Discharges were carried out at different current load levels until the battery voltage fell to preset voltage thresholds. Some of these thresholds were lower than that recommended by the OEM (2.7 V) in order to induce deep discharge aging effects. Repeated charge and discharge cycles result in accelerated aging of the batteries.
- Link: https://c3.nasa.gov/dashlink/resources/133/

**From Microsoft:**

PySpark-Predictive-Maintenance data set:
- Description: This data is simulated to reflect features that are generic for most of the predictive maintenance scenarios.
- Comments: Big data set. 
- Link: https://github.com/Azure/PySpark-Predictive-Maintenance (Other info: https://gallery.azure.ai/Notebook/Predictive-Maintenance-Modelling-Guide-R-Notebook-1)

AMLWorkshop
- Description: Data used in the Azure Machine Learning workshop delivered at Silicon Valley Microsoft Technology Center. The business problem for this example is about predicting problems caused by component failures such that the question “What is the probability that a machine will fail in the near future due to a failure of a certain component?” can be answered.
- Comments: multi-classification problem.
- Link: https://github.com/microsoft/AMLWorkshop


**From Kaggle:**

Hard Drive Test Data (Daily Snapshot of Each Operational Hard Drive in 2016):
- Description: Each day, Backblaze takes a snapshot of each operational hard drive that includes basic hard drive information (e.g., capacity, failure) and S.M.A.R.T. statistics reported by each drive. This dataset contains data from the first two quarters in 2016.

## References:

https://medium.com/towards-artificial-intelligence/the-50-best-public-datasets-for-machine-learning-d80e9f030279

https://towardsdatascience.com/top-sources-for-machine-learning-datasets-bb6d0dc3378b

https://www.freecodecamp.org/news/https-medium-freecodecamp-org-best-free-open-data-sources-anyone-can-use-a65b514b0f2d/
<!--stackedit_data:
eyJoaXN0b3J5IjpbNzI4Mzc3MzY3XX0=
-->
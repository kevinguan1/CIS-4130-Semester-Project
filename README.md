Big Data Clash Royale Battles

My goal in this is to predict who will win the game based on the starting setup they have, which we’ll see in their starting setup by the eight cards and trophies they have.  

I’ve chosen to do this dataset because this is a game I sometimes play, and I think it would be interesting to do for my semester project.

The Kaggle set I chose was https://www.kaggle.com/datasets/s1m0n38/clash-royale-games/data. 

Data set attributes:
- DateTime
- trophies
- crowns
- list of 8 cards each of the players is using.


Language used: PySpark, Python

Libraries used: google.cloud, col, io, matplotlib.pyplot, pandas, numpy, pyspark.sql.types, Pipeline, StringIndexer, OneHotEncoder, VectorAssembler, RandomForestClassifier, CrossValidator, ParamGridBuilder, BinaryClassificationEvaluator, RegressionEvaluator, SparkSession, matplotlib, numpy, seaborn, when

Summary:
1. Data Acquisition: Used GCP tools to download a 92.59 GB Kaggle dataset into GCP buckets.
2. Exploratory Data Analysis: Creating descriptive statistics using GCP
3. Feature Engineering and Modeling: Creating a machine learning pipeline using a random forest classifier.
4. Visualizing Results: Made visualizations of the prediction results on GCP.

Big Data Clash Royale Battles

My goal in this is to predict who will win the game based on the starting setup they have, which we’ll see in their starting setup by the eight cards and trophies they have.  

I’ve chosen to do this dataset because this is a game I sometimes play, and I think it would be interesting to do for my semester project.

The Kaggle set I chose was https://www.kaggle.com/datasets/s1m0n38/clash-royale-games/data. 

Data set attributes:
- DateTime
- trophies
- crowns
- list of 8 cards each of the players is using.


🛠️ Language used: PySpark, Python

🛠️ Libraries used: google.cloud, col, io, matplotlib.pyplot, pandas, numpy, pyspark.sql.types, Pipeline, StringIndexer, OneHotEncoder, VectorAssembler, RandomForestClassifier, CrossValidator, ParamGridBuilder, BinaryClassificationEvaluator, RegressionEvaluator, SparkSession, matplotlib, numpy, seaborn, when

📖 Summary:
1. Data Acquisition: Used GCP tools to download a 92.59 GB Kaggle dataset into GCP buckets.
2. Exploratory Data Analysis: Creating descriptive statistics using GCP
3. Feature Engineering and Modeling: Creating a machine learning pipeline using a random forest classifier.
4. Visualizing Results: Made visualizations of the prediction results on GCP.

Overall, I built a complete machine learning pipeline in this semester-long project that incorporated big data technologies using a cloud infrastructure. I’ve dealt with struggles and successes in making my machine learning pipeline, as I had to go through a proposal, data acquisition, exploratory data analysis and data cleaning, feature engineering and modeling, and data visualization. Going through this whole process has been amazing, and a new way to incorporate coding to help get information from tons of data that is over 10GB. Even though my prediction was pretty straightforward, which was finding out if player one or player two would win based on the starting setup they have from the eight cards and the trophies they have. I enjoy every moment of learning something new that I could use for my daily life if I ever try to look up or want to predict a certain thing from a large dataset. To conclude, even though my predictions from the data processing pipeline weren’t that solid and perfect, they still did a good job predicting which player 1 or 2 would win. But, it was still able to extract all the information they had gotten and give a result on who would win.

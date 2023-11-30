****CMPE 255 Project****

This project was done as part of CMPE 255 course, under Prof. Guzun.

Project Title: Analysis of Trending YouTube videos in US region

Team Members:
1. Atharva Dixit
2. Adi Siva Prasad Reddy Korivi
3. Alan Park

Primary files:
1. US_category_id.json
2. US_youtube_trending_data.csv
3. US_youtube_trending_data_sampled.csv (10% sampled dataset)

Note: For the 2nd file, US_youtube_trending_dataset.csv - please download the file from the kaggle link below:
https://www.kaggle.com/datasets/rsrishav/youtube-trending-video-dataset

This is because, the dataset is too big (around 345 MB), thus it cannot be added to GitHub as an attachment.

Instead, we have included a smaller sample (10%) in our data folder.
**If using the sampled dataset to test, you will need to add `engine='python'` to the pd.read_csv function, as it will fail otherwise.**

Supervised ML Algorithms used:
1. Multinomial Naive Bayes (MNB)
2. Support Vector Classifier (SVC)
3. Random Forest Classifier (RFC)
4. K Neighbors Classifier
5. Decision Tree Classifier

**Instructions to run code**

Required:
1. Jupyter Notebook
2. Python3 (v3.0 or later)

Make sure to change the primary files location to the location where you download it.

**References**

1. Dataset: https://www.kaggle.com/datasets/rsrishav/youtube-trending-video-dataset
2. https://www.kaggle.com/bansmohit/us-youtube-eda-category-predictions
3. Official matplotlib documentation

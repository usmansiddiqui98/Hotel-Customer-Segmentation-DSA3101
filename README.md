# Hotel-Customer-Segmentation-DSA3101

## Summary
We are a group of investors looking to set up our first luxury hotel in Brussels, Belgium. Our definition of luxury hotels comprises all 4* and 5* hotels in the city.  In order to gain sufficient market insight to make informed and strategic business decisions, we will utilise the following methods on a dataset of customer reviews on local hotels in Brussels. 

1.	Customer segmentation using DBSCAN, K-Means and K-Prototype
2.	Sentiment analysis on reviews in each cluster using various tokenization and LDA techniques 



## Instructions to run notebooks

### 1.	Run the file titled “Group3_DataCleaningExploration.ipynb”.
  
_(a)_ In line 2 of the notebook, change the file path to the path where “booking_reviews copy.csv” has been saved.
  
_(b)_	This notebook will produce a cleaned dataset titled “hotels_booking_reviews.csv” (in Datasets folder)
  
### 2.	Run the file titled “Group3_DBSCAN.ipynb”.

_(a)_	In line 3 of the 2nd code block of the notebook, change the file path to the path where “hotels_booking_reviews.csv” was saved to.
  
### 3.	Run the file titled “Group3_KMeans.ipynb”.

_(a)_	In line 2 of the 2nd code block of the notebook, change the file path to the path where “hotels_booking_reviews.csv” was saved to.
  
### 4.	Run the file titled “Group3_KPrototype.ipynb”.

_(a)_	In line 2 of the 2nd section of the notebook, change the file path to the path where “hotels_booking_reviews.csv” was saved to.
  
_(b)_	This notebook will produce a dataset with the clustering titled “dataset_sentiment_analysis.csv” (in Datasets folder)
  
### 5.	Run the file titled “Group3_LDA.Rmd”. 

_(a)_	In line 27 of the code in the Markdown file, change the file path to the path where “dataset_sentiment_analysis.csv” has been saved.
  
_(b)_	5 csv files titled “cluster0_top20.csv”, “cluster1_top20.csv”, “cluster2_top20.csv”, “cluster3_top10.csv”, “cluster3_all.csv” will be generated.
  
_(c)_	4 folders titled “dsa3101_vis_cluster0”, “dsa3101_vis_cluster1”, “dsa3101_vis_cluster2”, “dsa3101_vis_cluster3” will be generated. To view LDA visualisation, open folder, right click index, select open with Firefox. If nothing shows, type “about:config” in search bar, input “privacy.file_unique_origin” in subsequent search bar and switch setting to “false” before reopening index file.
  
### 6.	Run the file titled “Group3_SentimentAnalysis.ipynb”.

_(a)_	In section 1.1 of the notebook, read in the file titled “dataset_sentiment_analysis.csv”. 
  
_(b)_	Read in the 4 files generated in step 5 in order into sections 3.1, 3,2, 3.3 and 3.4 respectively.
  
### 7.	All files used in each of the notebooks/Markdown files are available for download in the Data folder


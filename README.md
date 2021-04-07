# Song-Recommendation-System

• Built a music recommendation system using the million-song dataset using various models which included:
•	An ETL pipeline for data processing from HDF5 file format to Spark Dataframe format for the 259GB dataset, fetched from the S3 bucket, followed by feature engineering like normalization, standardization, stop word removal and using PCA to select top features.
•	A K-means clustering algorithm performed item-based recommendation by collecting the various top song features and creating clusters to recommend the top 5 songs based on cosine similarity metric in the feature space between the existing clusters and a new song
•	A Matrix factorization method exploited user-based recommendation technique using the cosine similarity metric between the various users and their respective song play counts collected from the users’ play history 
![Uploading image.png…]()

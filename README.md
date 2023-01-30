# Recommendation Systems.

### Objective

The purpose of a book recommendation system is to predict buyer’s interest and recommend books to them accordingly. A book recommendation system can take into account many parameters like book content and book quality by filtering user reviews. 
In this project, a collobarative book recommendation systems using designed using K-Nearest Neighbours Machine Learning Algorithm and Cosine Similarity seperately and the results are hence compared.

### Dataset
https://www.kaggle.com/datasets/saurabhbagchi/books-dataset

Users : Contains the users. Note that user IDs (User-ID) have been anonymized and map to integers. Demographic data is provided (Location, Age) if available. Otherwise, these fields contain NULL values.

Books : Books are identified by their respective ISBN. Invalid ISBNs have already been removed from the dataset. Moreover, some content-based information is given (Book-Title, Book-Author, Year-Of-Publication, Publisher), obtained from Amazon Web Services. Note that in the case of several authors, only the first is provided. URLs linking to cover images are also given, appearing in three different flavors (Image-URL-S, Image-URL-M, Image-URL-L), i.e., small, medium, large. These URLs point to the Amazon website.

Ratings : Contains the book rating information. Ratings (Book-Rating) are either explicit, expressed on a scale from 1-10 (higher values denoting higher appreciation), or implicit, expressed by 0

### Methods and Technologies
Data Visualization, Machine Learning, Python, Pandas, Numpy, Matplotlib, Seaborn, Scikit-learn and Descriptive Statistics

### Project Description

EDA - Performed exploratory data analysis on numerical and categorical data.

Data Cleaning - Missing value imputation,Outlier Treaatment

Feature Selection - Used User-ID,ISBN and Books-Rating for model development.

Model development - Popularity based and Collaborative filtering using KNearest Neighbours and Cosine Similarity.

### Results
K-Nearest Neighbours
![image](https://user-images.githubusercontent.com/61462986/215546961-eee7893b-ee6c-4f8d-b0dc-6efa01a4f8b2.png)

![image](https://user-images.githubusercontent.com/61462986/215547038-60e4b599-86b2-43ef-80e1-bf7b5c2b7131.png)

Cosine Similarity
![image](https://user-images.githubusercontent.com/61462986/215547246-dfbb5ee3-58a1-4691-8058-27e1a27ce5ca.png)

![image](https://user-images.githubusercontent.com/61462986/215547429-0e0b045a-294b-42a5-bdef-4bf4b494ed81.png)




# NETFLIX Movies and TV Shows Clustering

![Logo](https://www.edigitalagency.com.au/wp-content/uploads/Netflix-logo-red-black-png.png)

This project is aimed at predicting and gather insights of Netflix Movies and TV Shows.

This dataset consists of tv shows and movies available on Netflix as of 2019. The dataset is collected from flixable which is a third-party Netflix search engine.

In 2018, they released an interesting report which shows that the number of TV shows on Netflix has nearly tripled since 2010. The streaming service's number of movies has decreased by more than 2,000 titles since 2010, while its number of TV shows has nearly tripled. It will be interesting to explore what all other insights can be obtained from the same dataset.

Integrating, this dataset with other external datasets such as IMDB ratings, roten tomatoes can also provide many interesting findings.

We will import NumPy, pandas, matplotlib, seaborn, sklearn models and other librarires in Google Colab then mount the drive. After that we will read csv file from working directory path and assigned it into the data frame. The dataset description is given below :-

1. show_id : Unique ID for every Movie/TV Show

2. type : Identifier - Movie/TV Show

3. title : Title of the Movie/TV Show

4. director : Director of the Movie/TV Show

5. cast : Actors involved in the Movie/TV Show

6. country : Country where the Movie/TV Show was produced

7. date_added : Date it was added on Netflix

8. release_year : Actual Release year of the Movie/TV Show

9. rating : TV Rating of the Movie/TV Show

10. duration : Total Duration - in minutes or number of seasons

11. listed_in : Genre

12. description: The Summary description

In this dataset, there are 7787 rows and 12 columns. The dataset contains no duplicate values and identified null values or missing values. After Data Wrangling, Exploratory Data Analysis is done to get data visualization and deeper insights of the datasets. In feature engineering, feature selection is done. Textual Data Preprocessing is done. Principal Component Analysis is done to reduce the dimensions. Topic Modelling with Gensim is done to gather deeper insights of the dataset. In Machine Learning, K Means Clustering, DBSCAN, Hierarchial Agglomerative Clustering is apllied.

I choose K Means Clustering from the above models as my final prediction model because

1. Silhouette Coefficient is better than the other two models.

2. Davies-Bouldin Index is lower than the other two models. Lower values indiacating better clustering.

3. Calinski-Harabasz Score is much decent than the other two models.




## 🛠 Skills

**Programming Language** :- Python

**Libraries used** :- NumPy, Pandas, Seaborn, Matplotlib, Missingno, Wordcloud, Sklearn, Scipy, NLTK


## Author

- [@sourav03dutta](https://github.com/sourav03dutta)


# Movie Popularity Predictor and Recommendation System Using Machine Learning and Transfer Learning

This project aims to predict the popularity of movies and provide valuable insights for Spectrum, enabling them to excel in the online streaming business venture. By utilizing data-driven models, we analyze movie popularity and offer recommendations to enhance audience engagement.

![READ me](https://github.com/NataliaEde/Movie_Popularity_Predictor-Recommendation-System/assets/44559346/80f93248-4a3c-4186-939f-b57647a4a75b)

### Data
We started with two separate datasets: one containing information on movie features such as genres, languages, budget, popularity, revenue, and runtime, and the other including details on movie titles, cast, and crew. These datasets were merged to create a comprehensive dataset of 4,800 movie data points from Kaggle. This allowed us to analyze a wide range of movies and explore the relationships between different features to gain valuable insights.

https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata

### Exploratory Data Analysis

During our exploratory data analysis, we gained insights into the relationships between these features and movie popularity. For instance, we looked into  interesting patterns in the genre and release month of movies, as shown in the genre and month graphs.

By analyzing patterns in genres and release months, we gained valuable knowledge that can guide decisions in movie production and selection for platforms like Spectrum.

![Genres](https://github.com/NataliaEde/Movie_Popularity_Predictor-Recommendation-System/assets/44559346/cb349067-b872-4b3a-90e8-388a9912797d)



![Release Month](https://github.com/NataliaEde/Movie_Popularity_Predictor-Recommendation-System/assets/44559346/33a9f8ca-f3f3-4c05-b802-74f3c7320cd9)



### Modeling Movie Popularity

We started with linear regression models (OLS) and later explored machine learning algorithms like Random Forest, AdaBoost, and XGBoost. Then, we employed MLP (deep learning) and further refined the Random Forest and MLP models through hyperparameter tuning.

### Modeling Results

The results of our analysis showed that the Random Forest model performed the best in terms of minimizing the Root Mean Squared Error (RMSE) values. The tuned version of the Random Forest model also achieved good results.

![Results](https://github.com/NataliaEde/Movie_Popularity_Predictor-Recommendation-System/assets/44559346/c06f5715-e88f-4a87-b0d2-9fa1c059c6fb)

### Recommendation System

Additionally, we enhanced our recommendation system by incorporating transfer learning techniques using Hugging Face's SentenceTransformer ( https://huggingface.co/sentence-transformers/paraphrase-MiniLM-L6-v2)). By calculating cosine similarity, we were able to measure the similarity between movies and provide personalized and relevant recommendations to Spectrum's users, resulting in higher user engagement.

<img width="512" alt="Demo- reco _sys" src="https://github.com/NataliaEde/Movie_Popularity_Predictor-Recommendation-System/assets/44559346/c94379a0-0be3-407a-bcdb-ca5da610564c">


### Conclusion

We observed that certain months, such as June, July, November, and January, tend to be more popular for movie releases. Additionally, we found that specific genres, such as Adventure, Animation, and Science Fiction, have higher average popularity scores. Based on these findings, we suggest that movie production companies consider releasing movies during these popular months and explore collaborations within these high-performing genres to maximize their chances of success.



### Next Steps

* Gather More Recent Data: Update the dataset with recent movies and TV shows for up-to-date analysis and predictions.

* Collaborate with Influencers and Test New Marketing Strategies: Partner with influencers to inclrease movie awareness and engagement, and we will  test innovative marketing strategies to attract a wider audience.

* Compare Movie and TV Show Popularity: Analyze the popularity trends of movies and TV shows to uncover valuable insights for targeted content production and marketing.


### For More Information

See the full analysis in the Jupyter Notebook, [EDA Part_1](https://github.com/NataliaEde/Movie_Popularity_Predictor-Recommendation-System/blob/main/Movie_Popularity_Predictor(EDA)(Part_1).ipynb), [Modeling Movie Popularity Part_2](https://github.com/NataliaEde/Movie_Popularity_Predictor-Recommendation-System/blob/main/Movie_Popularity_Predictor_(Part_2).ipynb),[Recommendation System Part_3](https://github.com/NataliaEde/Movie_Popularity_Predictor-Recommendation-System/blob/main/%20Recommendation%20System%20(Part_3).ipynb) or review this [EDA Presentation](https://github.com/NataliaEde/Movie_Popularity_Predictor-Recommendation-System/blob/main/presentation.pdf)

### Repository Navigation
```)
├── README.md
├── Movie_Popularity_Predictor(EDA)(Part_1).ipynb
├── Movie_Popularity_Predictor(EDA)(Part_1).PDF
├── Movie_Popularity_Predictor_(Part_2).ipynb
├── Movie_Popularity_Predictor_(Part_2).PDF
├── Recommendation System(Part_3).ipynb
├── Recommendation System(Part_3).PDF
├── Images
├── presentation.pdf
└── requirements.txt




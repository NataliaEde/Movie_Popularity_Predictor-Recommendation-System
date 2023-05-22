# Movie Popularity Predictor and Recommendation System Using Machine Learning and Transfer Learning

This project aims to predict the popularity of movies and provide valuable insights for Spectrum, enabling them to excel in the online streaming business venture. By utilizing data-driven models, we analyze movie popularity and offer recommendations to enhance audience engagement.

![READ me](https://github.com/NataliaEde/Movie_Popularity_Predictor-Recommendation-System/assets/44559346/80f93248-4a3c-4186-939f-b57647a4a75b)

### Data

We worked with a comprehensive dataset of 4,800 movies, which included features such as genres, languages, budget, popularity, revenue, and runtime. We merged two datasets: one containing title, cast, and crew information, and another encompassing the remaining features.
https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata

### Exploratory Data Analysis

During our exploratory data analysis, we gained insights into the relationships between these features and movie popularity. For instance, we looked into  interesting patterns in the genre and release month of movies, as shown in the genre and month graphs.


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

### Repository Navigation



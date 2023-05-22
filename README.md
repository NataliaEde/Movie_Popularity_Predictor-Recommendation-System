# Movie Popularity Predictor and Recommendation System Using Machine Learning and Transfer Learning

This project aims to predict the popularity of movies and provide valuable insights for Spectrum, enabling them to excel in the online streaming business venture. By utilizing data-driven models, we analyze movie popularity and offer recommendations to enhance audience engagement.

![READ me](https://github.com/NataliaEde/Movie_Popularity_Predictor-Recommendation-System/assets/44559346/80f93248-4a3c-4186-939f-b57647a4a75b)

### Data

We worked with a comprehensive dataset of 4,800 movies, which included features such as genres, languages, budget, popularity, revenue, and runtime. We merged two datasets: one containing title, cast, and crew information, and another encompassing the remaining features.
https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata

### Exploratory Data Analysis

During our exploratory data analysis, we gained insights into the relationships between these features and movie popularity. For instance, we looked into  interesting patterns in the genre and release month of movies, as shown in the genre and month graphs.

### Modeling Movie Popularity

We started with linear regression models (OLS) and later explored machine learning algorithms like Random Forest, AdaBoost, and XGBoost. Then, we employed MLP (deep learning) and further refined the Random Forest and MLP models through hyperparameter tuning.

### Modeling Results

The results of our analysis showed that the Random Forest model performed the best in terms of minimizing the Root Mean Squared Error (RMSE) values. The tuned version of the Random Forest model also achieved good results.

### Recommendation System

Additionally, we enhanced our recommendation system by incorporating transfer learning techniques using Hugging Face's SentenceTransformer ( https://huggingface.co/sentence-transformers/paraphrase-MiniLM-L6-v2)). By calculating cosine similarity, we were able to measure the similarity between movies and provide personalized and relevant recommendations to Spectrum's users, resulting in higher user engagement.

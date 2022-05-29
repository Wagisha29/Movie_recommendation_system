# Movie_recommendation_system

Movie Recommendation System created using Collaborative Filtering (Website) and Content based Filtering (Jupyter Notebook).

The details of the movies(title, genre, runtime, rating, poster, etc) are fetched using an API by TMDB, https://www.themoviedb.org/documentation/api, and using the IMDB id of the movie in the API, I did web scraping to get the reviews given by the user in the IMDB site using beautifulsoup4 and performed sentiment analysis on those reviews.

# Objectives
1. To create a movie recommendation system using Collaborative Filtering and machine learning algorithms such as K Nearest Neighbours.
2. The system should recommend movies based on the movie title entered by the user.
3. The system should apply sentiment analysis to categorize user comments on a particular movie.
4. Additional Content Based Filtering is performed using Neural Network to perform Matrix Factorization.

# How to run the project?

1. Clone or download this repository to your local machine.
2. Install all the libraries mentioned in the requirements.txt file with the command pip install -requirements.txt
3. Get your API key from https://www.themoviedb.org/.
4. Replace YOUR_API_KEY in both the places of static/recommend.js file and hit save.
5. Open your terminal/command prompt from your project directory and run the file main.py by executing the command python main.py.
6. Go to your browser and type http://127.0.0.1:5000/ in the address bar.
7. Hurray! That's it.

# web application
<img width="1435" alt="Screenshot 2022-05-29 at 4 39 46 PM" src="https://user-images.githubusercontent.com/77954391/170864984-7d6582c0-bca6-4b72-87a1-8e5ac519200b.png">

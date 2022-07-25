
# Conent Based Movie Recommendation System Machine Learning

It uses attributes such as genre, director, description, actors, etc. for movies, to make suggestions for the users. The intuition behind this sort of recommendation system is that if a user liked a particular movie or show, he/she might like a movie or a show similar to it. I used `Cosine Similiarity` to calculate Similiarity between movies.



## TMDB API 
We are using tmdb api to render poster and movie detials about data for that purpose, make a account in https://www.themoviedb.org/, click on the API connect from the left hand sidebar in your account settings and fill every one of the subtleties to apply for API key. Assuming you are requested the site URL, simply give "NA" in the event that you don't have one. You will see the API key in your API sidebar once your request is approved
## Run Project
Clone or download this repository to your machine
Install all the libraries mentioned in the requirements.txt file into your virtual enviroment with the command.
```bash
pip install -r requirements.txt
```
after installing all the dependencies run the below command
```bash
python main.py
```
then open browser and type `http://127.0.0.1:5000/` in your search bar


## Dataset
Kaggle TMDB Movie Dataset 
https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata
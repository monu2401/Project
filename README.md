# Internship 2021
## Project Title- IMDB BOX OFFICE PREDICTION

Created a simple Prediction Engine based on IMDb ratings and social media presence

The movie industry is a massive sector for investment but larger business sectors have more complexity, and it is hard to choose how to invest. Furthermore, significant investments come with more significant risks
Predicting a movie's box office success is a very complicated task to do. The definition of success of a film is relative, some videos are called successful based on its worldwide gross income, and some movies may not shine in business part but can be called successful for good critics' review and popularity.

The initial objective from this project was to learn in-depth regarding the implementation of Machine Learning algorithms through Python and the IMDb Ratings database gave a perfect and unique opportunity to learn the same. 

The data was equally fascinating since the target variable 'Rating' was Continuous and Ordinal at the same time:
1. The Ordinal part of the variable came from the fact that IMDb Ratings are in the range of 0-10, with 10 being the best
2. The values within these 10 categories are continuous for a single interval

## Hence to make the prediction more robust for Recommendation purposes, I decided to test 3 types of Machine Learning models:
1. Classifiers: to factor in the Ordinal behaviour of the 'Rating' attribute
2. Support Vector Machine: are supervised learning models with associated learning algorithms that analyze data for classification and regression analysis.
3. Artifical Neural Network: An ANN is a network that relates the inputs and outputs of a system and these networks have been successfully used to map non-linear input and output relationships in a wide range of areas.

The ultimate goal through this Project was:
"To enable Prediction of MOVIES based on Social Media attributes such as Facebook Likes for Movie, number of Votes given, popularity of cast members and recognition of Director by the masses"

End Result: Achieved 79% Accuracy for knn 
            Achieved 76% Accuracy for SVC
            Achieved 99% Accuracy for ANN(confusion matrix)

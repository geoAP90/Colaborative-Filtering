# Colaborative-Filtering
About the dataset

There have been good datasets for movies (Netflix, Movielens) and music (Million Songs) recommendation, but not for books. That is, until now.

This dataset contains ratings for ten thousand popular books. As to the source, let's say that these ratings were found on the internet. Generally, there are 100 reviews for each book, although some have less - fewer - ratings. Ratings go from one to five.

Both book IDs and user IDs are contiguous. For books, they are 1-10000, for users, 1-53424. All users have made at least two ratings. Median number of ratings per user is 8.

There are also books marked to read by the users, book metadata (author, year, etc.) and tags.


Packages used: pandas, numpy, matplotlib, seaborn, sklearn
Project goal:

To build a recommendation system that will recommend a user top 5 books of his/her interest.
Project architecture:

Exploratory data analysis (EDA):

    Visualization on some important parts like most rated books, most popular books, most popular authors, most number of ratings

Data Preprocessing:

    Data cleansing
    Nan value treatment
    Extraction of relevant featuress

Model building:

    Splitting data into train and test set
    Neural Network creation(Using functional API)
    Training on train data and validating on test data

Recommendation:

    Loading model
    Creating a function for recommendation


Conclusion:

Recommender systems are a powerful new technology for extracting additional value for a business from its user databases. Recommender systems benefit users by enabling them to find items they like. Conversely, they help the business by generating more sales.

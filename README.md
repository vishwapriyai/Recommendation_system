# Recommendation_system


# Movie Recommendation System

This project implements a movie recommendation system using collaborative filtering with Singular Value Decomposition (SVD) on the MovieLens dataset. The system predicts movie ratings for users based on their historical preferences and recommends new movies accordingly.

## Dataset

The dataset used for this project is the MovieLens dataset, which contains movie ratings provided by users, along with movie metadata such as genres, release year, etc. You can download the dataset from [Kaggle](https://www.kaggle.com/rounakbanik/the-movies-dataset).

## Usage

1. **Data Loading and Exploration**: Load the MovieLens dataset and explore the data to understand its structure and characteristics.

2. **Data Preprocessing**: Prepare the data for modeling by cleaning, transforming, and organizing it into a suitable format.

3. **Model Training**: Use collaborative filtering with Singular Value Decomposition (SVD) to train the recommendation model on the training data.

4. **Evaluation**: Evaluate the model's performance using metrics like Root Mean Squared Error (RMSE) on the test data.

5. **Recommendations**: Generate movie recommendations for users based on the trained model and display the top recommended movies.

## Files

- `recommendation_system.ipynb`: Jupyter Notebook containing the code for building and evaluating the recommendation system.
- `movies.csv`: Movie metadata including movie ID, title, genres, etc.
- `ratings.csv`: User ratings for movies including user ID, movie ID, rating, etc.

## Dependencies

- Python 3.x
- pandas
- NumPy
- scikit-learn
- scipy
- matplotlib

## Acknowledgments

- This project was inspired by the MovieLens dataset and the recommendation systems implemented in various research papers and tutorials.
- Special thanks to Kaggle and Rounak Banik for providing the MovieLens dataset.

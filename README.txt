# Predicting Movie Rental Durations

## Project Description
This is a project where I want to create a tree-based model that can achieve a Mean Squared Error with a value less than 3.
The case was that the Movie Rental Store had a tight budget and only could afford to aim to a MSE less than 3.
This will help them predict their rental durations to best orquestrate their logistics.

I tried:
- Decision Tree Regressor
- KNN regressor (not tree-based)
- Voting Regressor
- Random Forest
- Bagging regressor

I tried several configurations for Cross validation Hyperparameters tuning, the result seen here Is the one I found the best for each, but there are more configurations or the hyperparameters to be explored.

I found out that some of them were overfitting the data.

The best model turned out to be Random Forest.

## Installation

This project uses the following libraries:
- Pandas
- Numpy
- Sklearn

### Clone the repository
```bash
git clone https://github.com/1joserivera/Predicting-Movie-Rental-Durations,git
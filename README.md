# Recipe Ratings Prediction using Machine Learning

## Overview
This project aims to develop predictive models that can forecast the ratings for various recipes based on given information. The dataset provided contains information about recipes, user reviews, and key features, which will be utilized to build the predictive models.

## Dataset Description
The dataset consists of the following files:

- **train.csv**: The training set, including the target variable 'rating' and accompanying feature attributes.
- **test.csv**: The test set, containing similar feature attributes but without the target variable 'rating', as it is the variable to be predicted.

### Columns Description
- **RecipeNumber**: Placement of the recipe on the top 100 recipes list.
- **RecipeCode**: Unique ID of the recipe used by the site.
- **RecipeName**: Name of the recipe the comment was posted on.
- **CommentID**: Unique ID of the comment.
- **UserID**: Unique ID of the user who left the comment.
- **UserName**: Name of the user.
- **UserReputation**: Internal score of the site, roughly quantifying the past behavior of the user.
- **CreationTimestamp**: Time at which the comment was posted as a Unix timestamp.
- **ReplyCount**: Number of replies to the comment.
- **ThumbsUpCount**: Number of up-votes the comment has received.
- **ThumbsDownCount**: Number of down-votes the comment has received.
- **Rating**: The score on a 1 to 5 scale that the user gave to the recipe. A score of 0 means that no score was given (Target Variable).
- **BestScore**: Score of the comment, likely used by the site to help determine the order comments appear in.
- **Recipe_Review**: Text content of the comment.

## Approach
1. **Data Exploration**: Perform exploratory data analysis to understand the distribution of variables, identify patterns, and gain insights into the dataset.
2. **Data Preprocessing**: Clean the data, handle missing values, and perform feature engineering if necessary.
3. **Model Building**: Utilize machine learning algorithms to build predictive models for recipe ratings.
4. **Model Evaluation**: Evaluate the performance of the models using appropriate evaluation metrics.
5. **Deployment**: Deploy the best-performing model for prediction.

## Tools and Libraries Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Note: This project was carried out without the use of libraries like TensorFlow, PyTorch, NLTK, word2vec, textblob etc.

## Usage
1. Clone this repository.
2. Navigate to the project directory.
3. Install the required dependencies
4. Run the Jupyter notebooks or Python scripts to explore the data, build models, and make predictions.

## Contributors
- Venkatachalam Subramanian Periya Subbu


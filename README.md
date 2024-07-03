# Steam User Behaviour Analysis
This project involves analyzing the Steam 200k dataset to uncover insights about user behavior, game popularity, and other key metrics. Using various data science and machine learning techniques, the analysis aims to provide a comprehensive understanding of the patterns and trends within the Steam gaming community. It also involves building predictive models to predict total game playtime.

The dataset is taken from the Steam 200k Video Games Dataset from <a href="https://www.kaggle.com/datasets/tamber/steam-video-games" >Kaggle></a>

## Steps performed

- Data Cleaning and Preprocessing: Prepared the Steam dataset for analysis by filtering and structuring the data.
- Exploratory Data Analysis: visual insights into user behavior, including the distribution of playtime and purchase patterns.
- Feature Engineering: Created new features to enhance the predictive power of machine learning models.
- Model Training and Evaluation: Trained and evaluated multiple models using cross-validation to ensure robust performance.
- Hyperparameter Tuning: Optimized model parameters using GridSearchCV to improve accuracy.
- Visualizations: Generated plots to compare predicted vs. actual playtime and feature importances for each model.

## Models Used

- **Linear Regression:** A baseline model to predict total playtime.
- **Random Forest:** An ensemble model to capture non-linear relationships in the data.
- **XGBoost:** A powerful boosting algorithm for high-accuracy predictions.

## Project Structure

- `data/`: Directory containing the dataset.
- `notebooks/`: Jupyter notebooks with step-by-step analysis, model training and project pipeline.
- `models/`: model outputs.

## Future work
currently working on part 2 - implementing a collaborative filtering approach for recommending games on Steam platform based on user behavior for this dataset

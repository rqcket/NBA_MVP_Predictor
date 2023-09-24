#  NBA MVP Predictor ML Model <br>

![mvp](https://github.com/rqcket/NBA_MVP_Predictor/assets/90141159/72940195-ef7d-45d8-811b-bf9df4d88e6e)

## Project Description:

The NBA MVP Predictor ML Model is an exciting project that combines data scraping, data cleaning, and machine learning to predict the Most Valuable Player (MVP) award recipient in the National Basketball Association (NBA). This project leverages historical NBA statistics to create a predictive model using Ridge Regression, making it a valuable tool for basketball enthusiasts and analysts.

## Project Phases: <br>

### Data Scraping: <br>

The project starts with web scraping from reputable sources such as basketball-reference.com and NBA.com to gather historical NBA player statistics. 
Relevant data includes player performance metrics, team statistics, and MVP award history.
Libraries such as **BeautifulSoup** and **Selenium** are employed to extract data efficiently. <br>

### Data Cleaning: <br>

The scraped data often requires extensive cleaning and preprocessing to ensure its quality and suitability for machine learning.
This phase involves handling missing values, data type conversions, and removing outliers or irrelevant features.
Data is organized into a structured format, making it ready for analysis. <br>

### Feature Engineering: <br>

Feature engineering is a crucial step in creating meaningful predictors. New features were derived from existing data to improve model performance.
Relevant statistics like mean blocks per year, assists per year and points per year can be computed and added to the dataset. <br>

### Model Selection: <br>

Ridge Regression is chosen as the machine learning algorithm for this project. It is a regularization technique that helps prevent overfitting by adding a penalty term to the linear regression model.

### Training and Evaluation: <br>

The dataset is divided into training and testing sets to assess model performance.
A self devised evaluation metric is used to quantify the model's accuracy as we are trying to improve predictions of the ranks in MVP standings.

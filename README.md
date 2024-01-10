# NBA Points ML Model
* Coded in Python in collaboration with Google Colab
* Utilizes models such as Linear Regression and Random Forest Regressor
* Takes in the 2023-2024 NBA Player Stats- Regular Season Dataset that I had obtained through Kaggle

<img width="455" alt="Screen Shot 2024-01-09 at 7 11 08 PM" src="https://github.com/akhilthuremella/NBAMLModel/assets/126734806/6ff30be7-a881-46e6-bbfa-0e515d82b256">

# How to Run
With this being a form of a Jupyter Notebook, it can be downloaded and loaded on any software that has some form of a Jupyter Notebook (For ex: Google Colab)

# What Does it Do?
The program makes use of the Python library "Pandas" to aid with the Data Analysis that this project demands. It starts off by reading the dataset through a csv file that was uploaded. My main focus here was to work with quantitative data and not categorical data. Because of this, I had decided to drop the "Players, Position, and Team" columns from this dataset so that I was working with strictly quantitative data to ensure a smooth process when it came down to training the models. Afterwards, the data was separated into X and Y, with Y being the value predicted which in this case, was Points. The data was then split into training data (80%) and testing data (remaining 20%). After this, two models were built: Linear Regression and Random Forest Regressor. Mean Squared Error and the R^2 Score were used to evaluate the efficiency of these models. In both cases, the predicted values and actual values were very close, almost the same. In order to visualize, I made use of NumPy and made a scatter plot with the trained data and and the predicted trained data from the linear regression model which resulted in a scatterplot which formed a line which was linear. This ensured that the model ran successfully.

# Issues & Improvements Needed
In terms of issues, I had initially had errors with the linear regression model and the original dataset which had categorical data(strings). In order to fix this, I decided to drop the columns which contained categorical data. In terms of improvements, this model predicts values based on the given dataset and performs a historical analysis. I would like to develop the model further so that it can predict the performances of these players in the future as well (for ex: the next 5 games). I understand that it can be a challenge considering the various factors that go into a players performance such as injuries, opposition teams, and transfers/trades. 

# Why This Was Made
I wanted to combine two of my passions: Data Analysis and Sports together to create a project which I thought would be fun and challenging to do. I am active in my Fantasy Basketball League and my initial goal was to create a model to help me for that. I believe that this is a good start and I can only build this model up from here and hope to see what it can achieve. 

Inspiration/Tutorial: https://www.youtube.com/watch?v=29ZQ3TDGgRQ&t=989s
Source: https://www.kaggle.com/datasets/vivovinco/2023-2024-nba-player-stats/data


# **EPL Match Winner Prediction(ML) Projct**

#### *This project aims to predict the outcome of English Premier League (EPL) football matches using historical match data and basic Machine Learning models. The models classify whether a team wins or not, based on match features like venue, opponent, match time, and day.*



## Project Structure

EPL-Match-Winner-Prediction/

├── Datset /*Contains the EPL macth dataset used for the project*

├── Python\_Notebook /*Jupyter notebook containing data processing, model building, evaluation, and visualization code*

├── README.md /*Project documentation and overview*



## Dataset

The dataset includes match-level data from the EPL seasons 2020–2021 and 2021–2022. Key features used for prediction include:

- `venue_code`: Encoded venue (home/away)
- `opp_code`: Encoded opponent
- `hour`: Match start hour
- `day_code`: Encoded day of the week

We trained on matches before 1st Jan 2022 and tested on matches from 2nd Jan 2022 onwards.



## Models Used

- **Logistic Regression**
- **K-Nearest Neighbors (KNN)**
- **Naive Bayes**



## Evaluation Metrics

The models were evaluated using:

- **Accuracy**
- **Precision**
- **F1-Score**
- **Confusion Matrix Visualization**

The goal was to measure how well each model predicted the actual match outcomes. Evaluation shows:

- Each model predicts match wins with varying performance.
- Confusion matrices help understand where models misclassified.



## Insights

- Total test samples: **276**
- Correct predictions:
  - **Logistic Regression**: 146 correct out of 276
  - **KNN**: 169 correct out of 276
  - **Naive Bayes**: 172 correct out of 276
- K-Neares Neighbour Classifier performed the best in terms of accuracy and Precision.



## Key Libraries Used

- `pandas`, `matplotlib`, `scikit-learn`



## Visualizations

- Bar charts comparing model performance (accuracy, precision, F1-score)
- Confusion Matrices for each model



## Author

**Rajarsi Roy Chowdhury**  

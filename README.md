# Spotify Songs’ Genre Segmentation Project Report

## Project Overview

The Spotify Songs’ Genre Segmentation project aims to build an automated system that can classify songs into different genres based on their auditory properties. The dataset used for this project contains various features of songs such as danceability, energy, key, loudness, mode, speechiness, acousticness, instrumentalness, liveness, valence, tempo, and duration. The objective is to develop a machine-learning model that accurately predicts the genre of a song based on these features.

## Data Preprocessing

The dataset was loaded from the provided CSV file, and missing values were checked. It was observed that there were no missing values in the numerical features, ensuring the data's completeness. Non-essential features like track_id, track_name, track_artist, and others were dropped as they were not relevant for genre prediction. The target variable 'genre' was identified as the feature to be predicted, and the data was split into numerical features (X) and the target variable (y).

## Data Analysis and Visualization

Exploratory data analysis was conducted to gain insights into the dataset and the distribution of the target variable (genre). The class balance of the target variable was examined, and it was observed that there was no significant class imbalance, ensuring a balanced dataset for modelling.

Various features' distributions were visualized using histograms, box plots, and scatter plots to understand their relationships with the target variable. Heat maps were plotted to analyze feature correlations, revealing that 'instrumentalness' and 'energy' have the most significant influence on genre classification.

## Clustering Analysis

K-means clustering was performed on the dataset to identify potential clusters of songs based on their features. The number of clusters was set to three, and the resulting clusters were visualized. However, further analysis and interpretation of the clusters' meanings are required to gain insights into the music genres they represent.

## Machine Learning Model Evaluation

Five machine-learning models were trained on the training set: Support Vector Machines (SVM), K-Nearest Neighbors (KNN), Decision Trees (DT), Logistic Regression (LR), and Random Forest (RF). Each model's accuracy was evaluated on the testing set, and the results were as follows:

- Support Vector Machine Accuracy: 0.2344
- K-Nearest Neighbors Accuracy: 0.2499
- Decision Tree Accuracy: 0.4478
- Logistic Regression Accuracy: 0.2548
- Random Forest Accuracy: 0.5579

Based on the accuracy results, the Random Forest model demonstrated the highest performance, making it the selected model for genre segmentation.

## Model Interpretation and Feature Importance

The feature importance of the Random Forest model was analyzed to identify the most influential features in genre classification. 'Instrumentalness' and 'energy' were found to be the most important features, indicating their significance in determining music genres.

## Conclusion

The Spotify Songs’ Genre Segmentation project successfully developed a machine-learning model to predict music genres based on auditory features. The Random Forest model showed promising performance with an accuracy of 55.79%. 'Instrumentalness' and 'energy' were identified as crucial features in genre classification.

This project has the potential to enhance music recommendation systems, enabling more personalized and accurate genre-based song suggestions to Spotify users. Further exploration and fine-tuning of the model can lead to even better genre segmentation and contribute to improving the overall music listening experience.

---

Thank you for reading this report. If you have any questions or need further information, please feel free to contact us.

*Project Team No:10*

*Your Name(s)*

---

(End of Report)

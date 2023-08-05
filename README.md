# Spotify Songs Genre Segmentation using Machine Learning

![Music](music_image.png)

## Introduction
This project focuses on exploring the world of music through machine learning. The goal is to predict song genres and uncover auditory patterns by leveraging data-driven techniques. The project was undertaken as part of my summer internship with Corizo. The project description can be found [here](Project_Description.docx).

## Dataset
The dataset used in this project comprises a rich set of features related to various songs, including their danceability, energy, tempo, and more. It can be found [here](spotify_dataset.csv).

## Dependencies
Ensure you have the following Python libraries installed to run the project:

- numpy
- pandas
- matplotlib
- seaborn
- scikit-learn

You can install any missing dependencies using `pip install library_name`.

## Usage
To run the model and make predictions, execute the `predict.py` script after installing the dependencies. Provide the required inputs as prompted, and the model will output the predicted song genres. The data preprocessing and exploratory data analysis can be found in the Jupyter Notebook [here](main.ipynb).

## Model Evaluation
I have evaluated the performance of several machine learning algorithms, including Support Vector Machines (SVM), K-Nearest Neighbors (KNN), Decision Trees (DT), Logistic Regression (LR), and Random Forest (RF). The best-performing model, along with its evaluation metrics, is documented in the Jupyter Notebook.

## Results
My final model achieves an accuracy of 55.79% in predicting song genres. It's important to note that this model is meant for exploratory purposes and should not be used for critical music recommendations. For a detailed analysis and insights, refer to the [complete report](Model_Prediction_Conclusion_Report.md).

## Contributing
Contributions to enhance the model's performance or explore additional features are welcome. Feel free to open issues or submit pull requests.

## Acknowledgments
I extend my sincere thanks to Corizo for providing the dataset used in this project. The internship experience has been invaluable in developing my skills and knowledge in the field of AI and ML.

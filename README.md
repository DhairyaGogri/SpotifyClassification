This Jupyter Notebook presents a machine learning project focused on predicting the popularity of songs on Spotify. The goal is to develop a model that can accurately predict the popularity score of a song based on various attributes provided in the dataset.

The dataset contains several features that describe each song, including danceability, valence, energy, loudness, liveness, duration, acousticness, speechiness, and more. The target variable is the popularity score, which we aim to predict using different regression models.

The notebook begins by importing necessary packages such as pandas, numpy, matplotlib, seaborn, and scikit-learn. These packages are used for data manipulation, visualization, and implementing machine learning models.

The training and testing data are loaded from separate CSV files. The exploratory data analysis phase involves examining the raw data, performing descriptive statistics, and handling missing values. In this case, 15 null values were identified and removed from the dataset.

After preprocessing the data, the notebook proceeds to build and evaluate different regression models. The models used in this project include linear regression, support vector machine, random forest, decision tree, and gradient boosting regressor. Evaluation metrics such as mean squared error are employed to assess the performance of each model.

The notebook provides step-by-step instructions and code snippets, making it easy to understand and reproduce the analysis. Visualizations, including correlation matrices, are also included to gain insights into the relationships between variables.

By predicting the popularity of songs, this project aims to assist artists and labels in identifying potentially popular songs and producing music that has a higher chance of success. The notebook serves as a comprehensive guide for regression analysis and demonstrates the application of various machine learning algorithms in the context of music popularity prediction.

Overall, this project showcases the power of data analysis and machine learning in the music industry and provides a valuable resource for anyone interested in understanding and predicting song popularity.

# Song Popularity Project

## Problem Statement
The problem at hand involves predicting the loudness of a song based on various features within a dataset comprising approximately 19,000 entries. The dataset was obtained from Kaggle (https://www.kaggle.com/datasets/yasserh/song-popularity-dataset), and the objective is to develop a machine learning model capable of accurately forecasting a song's loudness given its diverse attributes. The initial attempt was to predict song popularity, however, the correlation analysis showed very weak dependency of popularity to score to the provided features. Loudness and a hanfull of other features demonstrated a linkage and I decided to develop a predictive model for estimation the loudness level of a song. The code has been writen such that the target (dependent) variable can be selected by the user. However, the tuning of parameters are based on prediction of loudness of a song.

## Solution Summary
Our solution leverages both neural network and linear regression algorithms to address the problem. Using a neural network architecture with three hidden layers, we aimed to enhance the predictive capabilities of the model. The hyperparameter tuning process was intricate and time-consuming, and there is ongoing consideration for further optimization. The solution demonstrates that neural network model specifically outperforms the linear regression model at the lowest loudness levels.


## Technical Solution
The technical solution involves the implementation of a neural network with three hidden layers in addition to input and output layers. The activation and loss functions are 'relu' and 'mean squared error', respectively. Hyperparameter tuning included determining the number of epoch, batch_size and the neurons of each hidden layer. The comparison between neural network and linear regression models showcases the superior predictive power of the neural network. Detailed technical aspects of the solution are available in the code and documentation.

## Repository Files
1. **README.md:** The main documentation providing an overview of the project, its objectives, and the technical approach taken.
2. **DataExploration.ipynb:** Jupyter notebook contaiing data exploration and correlation analysis. 
3. **ML-predictive-model.ipynb:** Jupyter Notebook containing the code implementation of the machine learning models, data preprocessing, and analysis.
4. **song_data.csv:** The dataset obtained from Kaggle, containing song features.

## Contact Information
For further inquiries or collaboration opportunities, please feel free to reach out:
- Email: gorgannejad.s@gmail.com


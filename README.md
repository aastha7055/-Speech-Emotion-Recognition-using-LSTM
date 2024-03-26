# Speech-Emotion-Recognition-using-LSTM
Project Title: Speech Emotion Recognition using LSTM

# Description:
This project implements a speech emotion recognition system using Long Short-Term Memory (LSTM) neural networks. It aims to classify the emotional content of speech data into different categories such as happiness, sadness, anger, fear, etc. The system utilizes the TESS Toronto emotional speech dataset and extracts Mel-Frequency Cepstral Coefficients (MFCC) features from the audio files. These features are then fed into an LSTM-based neural network model for training and classification.

# DataSet Information:
There are a set of 200 target words were spoken in the carrier phrase "Say the word _' by two actresses (aged 26 and 64 years) and recordings were made of the set portraying each of seven emotions (anger, disgust, fear, happiness, pleasant surprise, sadness, and neutral). There are 2800 data points (audio files) in total.
The dataset is organised such that each of the two female actor and their emotions are contain within its own folder. And within that, all 200 target words audio file can be found. The format of the audio file is a WAV format
# Download Link:https://www.kaggle.com/datasets/ejlok1/toronto-emotional-speech-set-tess

# Key Features:
1.Data loading and preprocessing from the TESS Toronto emotional speech dataset.
2.Feature extraction using MFCC.
3.Parallel processing for efficient feature extraction.
4.Construction of a sequential LSTM model using Keras.
5.Training and validation of the model with early stopping to prevent overfitting.
6.Visualization of training history and performance metrics.
7.Audio visualization tools for waveplots, spectrograms, and playback.

# Dependencies:
Python 3.x ,
Pandas ,
NumPy ,
Matplotlib ,
Seaborn ,
Librosa ,
Scikit-learn ,
Keras ,
Joblib

# Usage:
Clone the repository.
Ensure all dependencies are installed (pip install -r requirements.txt).
Run the main script.
Monitor training progress and visualize results.


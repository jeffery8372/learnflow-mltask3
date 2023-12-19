# learnflow-mltask3
  Speech Recognition using Google Speech Commands Dataset
Overview
This project involves speech recognition using the Google Speech Commands Dataset available on Kaggle. The dataset consists of various spoken commands, including "yes," "no," "up," "down," "left," "right," "stop," "go," and more.

The code provided here allows for:

Data loading and preprocessing
Model building for speech recognition
Training and evaluation of the speech recognition model
Prediction on new audio samples
Requirements
Ensure that the following dependencies are installed before running the code:

Python 3.x
TensorFlow
Keras
Librosa
NumPy
Pandas
Dataset
The Google Speech Commands Dataset can be downloaded from Kaggle at "https://www.kaggle.com/datasets/neehakurelli/google-speech-commands".

Download the dataset and organize it in the following structure:
dataset/
    - train/
        - audio/
            - <training audio files>
        - validation/
            - audio/
                - <validation audio files>
    - test/
        - audio/
            - <test audio files>



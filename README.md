# Task 2: Emotion Recognition from Speech

## Objective

Recognize human emotions (happy, angry, sad, etc.) from speech audio using speech signal processing and deep learning techniques.

## Dataset

RAVDESS (Ryerson Audio-Visual Database of Emotional Speech and Song)

## Feature Extraction

* MFCC (Mel-Frequency Cepstral Coefficients)

## Models Implemented

### Random Forest (Baseline)

* Accuracy: 61.11%

### CNN (Deep Learning)

* Accuracy: 38.89%

## Emotions Detected

* Happy
* Sad
* Angry
* Fearful
* Calm
* Neutral
* Disgust
* Surprised

## Technologies Used

* Python
* Librosa
* TensorFlow / Keras
* Scikit-learn
* NumPy
* Pandas

## Workflow

Audio File → MFCC Feature Extraction → Classification Model → Emotion Prediction

## Future Improvements

* CNN + LSTM Architecture
* Real-time Emotion Detection
* Streamlit Deployment

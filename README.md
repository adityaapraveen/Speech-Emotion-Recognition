# Speech Emotion Recognition with LSTM

This repository contains a deep learning model for Speech Emotion Recognition (SER) using Long Short-Term Memory (LSTM) networks. SER is the task of automatically recognizing the emotional state of a person from their speech signals. The model is trained on a dataset of speech recordings labeled with corresponding emotions. It extracts Mel-Frequency Cepstral Coefficients (MFCCs) as features from the speech signals and feeds them into an LSTM-based neural network for classification. The trained model can accurately predict the emotional state (e.g., happiness, sadness, anger) of a speaker based on their speech.

## Key Features

- Utilizes MFCC features extracted from speech signals for emotion recognition.
- Implements an LSTM-based neural network for sequence modeling and classification.
- Provides training, evaluation, and prediction functionalities for speech emotion recognition tasks.
- Includes visualization tools such as confusion matrix and classification report for performance analysis.

## Usage

1. **Preprocess Your Dataset**: Preprocess your dataset and extract MFCC features from speech recordings.

2. **Train the Model**: Train the LSTM model using the provided code or load a pre-trained model.

3. **Evaluate Model Performance**: Evaluate model performance using classification reports, confusion matrices, and ROC curves.

4. **Predict Emotions**: Use the trained model for predicting emotions in new speech recordings.

## Dependencies

- Python 
- NumPy
- pandas
- scikit-learn
- TensorFlow or PyTorch (for LSTM implementation)
- librosa
- matplotlib
- seaborn

## Contributing

Contributions to this project are welcome! Please feel free to open issues or submit pull requests with any improvements, bug fixes, or additional features.



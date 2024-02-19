# Infant Cry Type Classification


This project aims to classify different types of infant cries based on audio spectrograms using machine learning techniques. The notebook provided here demonstrates the process of extracting features from audio files, generating spectrogram images, training a convolutional neural network (CNN) model, and evaluating its performance in classifying infant cry types.

## Data Preprocessing

The notebook begins with importing necessary libraries and defining functions for generating spectrogram images from audio files. Spectrograms provide a visual representation of the frequency content of audio signals over time, making them suitable for analysis using machine learning algorithms.


## Model Training


The CNN model architecture is defined and trained using the spectrogram images generated from the audio recordings. The model consists of convolutional layers followed by max-pooling and dropout layers to extract relevant features and prevent overfitting. The model is compiled using the AdamW optimizer and trained on the training dataset.

## Model Evaluation


The performance of the trained model is evaluated using the validation dataset. Metrics such as accuracy and loss are monitored during training to assess the model's performance and identify potential areas for improvement.

## Testing

Finally, the trained model is used to predict the cry type for individual audio files. The model predicts the cry type based on the spectrogram images generated from the audio recordings and compares the predictions with the ground truth labels.

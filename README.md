# Fake_Voice_Detection

Overview

This project aims to detect fake (synthesized or deepfake) voices using Convolutional Recurrent Neural Networks (CRNN). 
The model is trained on audio datasets containing both real and fake voices, extracting spectrogram features and 
leveraging deep learning techniques for classification.

Features

-> Audio Preprocessing: Converts raw audio to Mel spectrograms.

-> Feature Extraction: Uses MFCCs, Chroma, Spectral Contrast, and Tonnetz.

-> Deep Learning Model: Combines CNN (for feature extraction) and RNN (for temporal dependencies).

-> Dataset Handling: Supports public datasets like ASVspoof, LA, and custom datasets.

-> Performance Metrics: Accuracy, Precision, Recall, F1-score, and Confusion Matrix.

-> Deployment Ready: Model exported to ONNX for real-time inference.

Results:

Achieved 90% accuracy on test data.

Spectrogram visualizations for real vs fake voices.

Model successfully differentiates deepfake from human speech.

Future Improvements:

Train with larger datasets for better generalization.

Explore Transformer-based architectures.

Implement real-time fake voice detection API.


# Sign Language Classification using CNN

This project implements a Convolutional Neural Network (CNN) to classify American Sign Language (ASL) alphabets from image data. Using a robust architecture with dropout regularization and image augmentation, the model achieves a high test accuracy of 99.40% on the ASL dataset.

## Dataset
The dataset used for training and testing is the American Sign Language Alphabet dataset available on [Kaggle](https://www.kaggle.com/datasets/grassknoted/asl-alphabet).

- Classes: 29 (26 A–Z, plus `del`, `nothing`, and `space`)
- Total images: ~87,000+ labeled images
- Image size: 200x200 pixels

## Model Highlights
- Architecture: CNN with multiple Conv2D and MaxPooling2D layers
- Regularization: Dropout used to prevent overfitting
- Activation: ReLU for intermediate layers and softmax for output
- Optimizer: Adam
- Loss Function: Categorical Crossentropy
- Accuracy Achieved: 99.40%

## Training Techniques
- Data augmentation: rotation, zoom, width and height shift
- Early stopping and model checkpointing to prevent overfitting
- Model trained for 20+ epochs with a batch size of 32

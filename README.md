# cat-dog-classification-cnn
A Convolutional Neural Network (CNN) project built with TensorFlow/Keras to classify images of cats and dogs. Includes data preprocessing, model training, evaluation, and prediction of unseen images.


# Cat vs Dog Classification using CNN

## Project Overview

This project implements a Convolutional Neural Network (CNN) using TensorFlow/Keras to classify images of cats and dogs. The model learns visual features from image data and predicts whether an input image belongs to a cat or a dog.

---

## Objectives

- Build a CNN model for binary image classification.
- Preprocess and augment image data.
- Train and evaluate the model.
- Predict the class of unseen images.
- Visualize training and validation performance.

---

## Dataset

The dataset consists of labeled images belonging to two categories:

- Cats
- Dogs

Images are preprocessed and resized before being fed into the CNN model.

---

## Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Pandas
- Matplotlib
- OpenCV
- Scikit-learn

---

## Project Workflow

1. Import required libraries.
2. Load and preprocess image data.
3. Split data into training and validation sets.
4. Build the CNN architecture.
5. Train the model.
6. Evaluate model performance.
7. Visualize accuracy and loss curves.
8. Predict classes for new images.

---

## CNN Architecture

The model includes:

- Convolutional Layers
- ReLU Activation
- Max Pooling Layers
- Flatten Layer
- Dense Layers
- Output Layer with Sigmoid Activation

---

## Results

The CNN model successfully learns image features and classifies cats and dogs with good accuracy on validation data.

### Performance Metrics

- Training Accuracy
- Validation Accuracy
- Training Loss
- Validation Loss

---

## Installation

Clone the repository:

```bash
git clone https://github.com/your-username/cat-dog-classification-cnn.git
cd cat-dog-classification-cnn
```

Install required packages:

```bash
pip install -r requirements.txt
```

---

## Requirements

Create a `requirements.txt` file containing:

```text
tensorflow
keras
numpy
pandas
matplotlib
opencv-python
scikit-learn
jupyter
```

---

## Usage

Run the Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```text
cat and dog(CNN).ipynb
```

Execute all cells to train and test the model.

---

## Sample Prediction

```python
prediction = model.predict(test_image)
print("Predicted Class:", prediction)
```

---

## Future Improvements

- Use Transfer Learning (VGG16, ResNet50, MobileNet)
- Hyperparameter Tuning
- Deploy using Flask or Streamlit
- Improve accuracy with larger datasets

---

## Author

Mohammed Sinan

```
Deep Learning project using Convolutional Neural Networks (CNN) for Cat vs Dog image classification with TensorFlow/Keras.
```

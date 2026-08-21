# Brain-Tumour-MRI-image-classification

The Project focuses on classifying brain MRI images uisng Deep Learning and Transfer Learning techniques. The goal is to develop an image classification model that can learn patterns from MRI images and classify them into their respective categories.

Multiple deep learning models are trained and evaluated to identify the model that provides the best classification performance.

# Dataset:
The dataset containing images organized into different classes:
- Training data
- Validation data
- Testing data
# Technologies used:
- Python
- Tensorflow
- Keras
- Numpy
- Pandas
- Matplotlib
- Scikit-learn
- Streamlit
  
# Workflow
The project includes image preprocessing, data augmentation, model training, evaluation and comparison of different models.

# Image preprocessing
- Resizing images to the required input size
- Normalizing pixel values
- Assigning class labels
- Data augmentation for training images
- creating training, validation and testing generators

# Models Used:
- 1.Custom CNN
- 2.ResNet50
- 3.InceptionV3
- 4.MobileNetV2

# Model Evaluation
The model are evaluated using:
- Accuracy
- Precision
- Recall
- F1-score
- confusion matrix
- Training and validation loss
- Training and validation accuracy

# Best Model
  Among the evaluated models, InceptionV3 achieved the best overall performance and was selected as the final model for brain MRI classification.

# Streamlit Application
  A streamlit web application is built to make users easy to use. Users can upload a brain MRI image through the application, and the trained InceptionV3 model predicts the corresponding class.
  


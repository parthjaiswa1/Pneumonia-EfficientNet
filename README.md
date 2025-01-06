This repository contains a Jupyter notebook that implements and compares the performance of various EfficientNet base models (B0 to B7) on a Kaggle dataset of X-ray images for detecting Pneumonia (https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia). The primary objective is to evaluate the efficiency and accuracy of these models for binary classification tasks: distinguishing between Pneumonia scans and normal scans. Each EfficientNet model is loaded with pretrained weights and customized by adding additional layers to suit the binary classification task:

Convolutional Layers
Max Pooling
Fully Connected Dense Layers
Dropout for regularization
Output Layer (Sigmoid Activation)

Each model was trained on 10 epochs. The EfficientNet base models include B0, B1, B2, B3, B4, B5, B6, and B7, each with increasing complexity and computational requirements. A classification report and confusion matrix were printed out for each model on the test set. The results can be found at the bottom of the Jupyter Notebook.

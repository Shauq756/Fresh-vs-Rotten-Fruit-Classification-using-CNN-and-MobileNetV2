# Project Title:
Fresh vs Rotten Fruit Classification Using CNN and MobileNetV2

# Dataset Description:
The dataset consists of fruit images categorized into two classes: Fresh and Rotten. The images were preprocessed using resizing and normalization techniques before being used for training and testing. The dataset was divided into separate training, validation, and testing sets to evaluate the performance of the models.

# CNN Model:
A custom Convolutional Neural Network (CNN) was developed using TensorFlow and Keras. The model includes convolutional layers for feature extraction, max-pooling layers for dimensionality reduction, dropout layers to reduce overfitting, and dense layers for classification. The final output layer uses a sigmoid activation function for binary classification.

# MobileNetV2 Model:
MobileNetV2 is a pre-trained deep learning model based on transfer learning techniques. The model was initialized with ImageNet weights and fine-tuned for the fruit classification task. Its lightweight architecture enables efficient training while maintaining high classification performance.

# How to Run the Notebook:
1. Clone the repository from GitHub.
2. Install the required Python libraries such as TensorFlow, NumPy, Matplotlib, and Scikit-learn.
3. Open the notebook file FRESH_VS_ROTTEN_FRUIT_CLASSIFICATION (8).ipynb using Jupyter Notebook, JupyterLab, or Google Colab.
4. Run all cells sequentially to load the dataset, train the models, evaluate performance, and generate the results.

# Results Summary

The CNN model achieved:
- Accuracy: 70.83%
- Precision: 85.71%
- Recall: 50.00%
- F1-Score: 63.16%

The MobileNetV2 model achieved:
- Accuracy: 83.33%
- Precision: 100.00%
- Recall: 66.67%
- F1-Score: 80.00%

# Conclusion:
The results show that MobileNetV2 outperformed the custom CNN model across all evaluation metrics. MobileNetV2 achieved an accuracy of 83.33% and a precision score of 100.00%, indicating highly reliable predictions. The CNN model achieved reasonable performance but was less effective than MobileNetV2. These findings demonstrate the effectiveness of transfer learning and pre-trained feature extraction in improving fruit classification performance.



# Facial Emotion Detection Using Deep Learning

Facial emotion detection involves using deep learning to identify and analyze human emotions based on facial expressions. This project uses convolutional neural networks (CNNs) to build a model that can recognize a range of emotions, including happiness, sadness, anger, surprise, fear, neutral, and disgust.

# Model Architecture

* **Convolutional Layers**: Multiple layers with ReLU activation.

* **Max Pooling**: Applied after convolutional layers to reduce dimensionality.

* **Dropout Layers**: Used to prevent overfitting.

* **Fully Connected Layers**: Dense layers for final classification.

* **Output Layer**: Softmax activation for multi-class classification.
# Features

- Detection of seven emotions from facial images.
- Uses convolutional neural networks (CNNs).
- Includes dropout layers to prevent overfitting.
- Easy integration with various applications.
- Evaluation metrics for model performance.

# Training Results
- Training Accuracy: 0.7338
- Training Loss: 0.7381
- Validation Accuracy: 0.6385
- Validation Loss: 1.0063
# Tech Stack

**Language:** 
-  `python`

**Libraries:** 
-  `pandas`
-  `numpy`
-  `os`
-  `matplotlib`
-  `seaborn`
-  `warnings`
-  `random`
-  `tensorflow`
-  `keras`
-  `tqdm`
-  `sklearn`



## Authors

- [@shibangibaidya](https://www.github.com/shibangibaidya)


## Deployment

To clone and run this project, use the following commands:

```bash
git clone https://github.com/shibangibaidya/Facial_Emotion_Detection.git
cd Facial_Emotion_Detection
jupyter notebook facial-emotion-detection.ipynb



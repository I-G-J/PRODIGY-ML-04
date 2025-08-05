# Hand Gesture Recognition

This project is a deep learning model for recognizing hand gestures from images. It's built using TensorFlow and Keras, and trained on a custom dataset to accurately classify different hand signals.

## 🚀 Key Features

* **Convolutional Neural Network (CNN) Model:** Utilizes a custom-built CNN architecture for robust image feature extraction and classification.
* **Data Augmentation:** Employs `ImageDataGenerator` to augment the training data, which helps in preventing overfitting and improving the model's generalization capabilities.
* **Categorical Classification:** The model is trained to classify gestures into multiple categories, making it suitable for a wide range of applications.
* **Simple and Extensible:** The code is well-structured and easy to understand, allowing for simple modifications, such as adding new gesture classes or fine-tuning the model architecture.

## ⚙️ Technologies Used

* **Python 3.x**
* **TensorFlow & Keras:** For building and training the deep learning model.
* **NumPy:** For numerical operations.
* **Scikit-learn:** For data splitting and preprocessing (though the `ImageDataGenerator` handles most of this).
* **Matplotlib:** For visualizing images and results.


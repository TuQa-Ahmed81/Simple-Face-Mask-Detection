# Simple-Face-Mask-Detection using CNN

A deep learning project that classifies whether a person is wearing a mask or not using a Convolutional Neural Network (CNN). This project was developed as a response to the COVID-19 pandemic to demonstrate the application of computer vision in real-time safety solutions.

---

### 📁 Dataset

The dataset was sourced from Kaggle and contains images categorized into two classes:

* `with_mask`
* `without_mask`
---

### ⚙️ Features

* Data preprocessing and augmentation (resizing, normalization, labeling).
* CNN model built using **TensorFlow/Keras**.
* Trained to classify images into masked and unmasked faces.
* Achieves high accuracy on test data.
---

### 🧪 Technologies Used

* Python
* TensorFlow / Keras
* NumPy
* Matplotlib
* OpenCV
* PIL (Pillow)
* Scikit-learn
* Google Colab

---

### 🏗️ Model Architecture

```text
Sequential CNN model:
→ Conv2D (32 filters) + ReLU
→ MaxPooling2D
→ Conv2D (64 filters) + ReLU
→ MaxPooling2D
→ Flatten
→ Dense (128 units) + ReLU
→ Output Layer (Softmax for 2 classes)
```



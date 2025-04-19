
# 🧠 Image Classification with CNN

This repository contains an image classification project using a **Convolutional Neural Network (CNN)** implemented in a Jupyter Notebook.

## 📁 Repository Structure

```
Image-classification/
│
├── convolutional_neural_network.ipynb  # Main notebook with the CNN model
├── README.md                           # Project documentation
```

## 📌 Project Description

This project is aimed at building an image classification model using CNNs. The model is trained to differentiate between categories of images (e.g., dogs vs cats) using TensorFlow/Keras. The goal is to demonstrate how convolutional layers can be used to extract features and classify images accurately.

## 📊 Model Details

- **Framework**: TensorFlow / Keras
- **Architecture**:
  - Conv2D → MaxPooling
  - Conv2D → MaxPooling
  - Flatten → Dense → Output Layer (Softmax/Sigmoid)
- **Loss Function**: BinaryCrossentropy / CategoricalCrossentropy
- **Optimizer**: Adam

## 🖼️ Dataset

The dataset was originally included in a `Dataset/` directory (now deleted in commit `3b4e72d`). Ensure you have your dataset structured like this:

```
Dataset/
├── cats/
│   ├── cat1.jpg
│   ├── cat2.jpg
│   └── ...
├── dogs/
│   ├── dog1.jpg
│   ├── dog2.jpg
│   └── ...
```

> Note: You can use your own dataset or re-add the previously removed one.

## 🚀 How to Run

1. Clone this repo:
   ```bash
   git clone https://github.com/muhammadnouman911/Image-classification.git
   cd Image-classification
   ```

2. Launch the Jupyter Notebook:
   ```bash
   jupyter notebook convolutional_neural_network.ipynb
   ```

3. Run all cells to train and evaluate the model.




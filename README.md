# AgroScan-Citrus_Leaf_Disease_Detection
To prevent and recognise diseases early regarding leafs of citrus plants based on image classification of leaf images and built a CNN deep learning models to identify early leaf diseases and to make better livelihoods of indian farmers.

🍊 Citrus Leaf Disease Detection using Deep Learning
          ResNet101 • DenseNet201 • AlexNet (Comparative Study)

* This project builds a deep learning-based early disease detection system for citrus leaves using ResNet101, DenseNet201, and AlexNet.
* The goal is to support farmers and agricultural experts through faster and more accurate diagnosis of citrus leaf diseases.
  

## 🚀 Features

* Implements three CNN architectures: ResNet101, DenseNet201, and AlexNet.

* Includes a complete preprocessing + data augmentation pipeline to reduce overfitting and boost model generalization.

* Provides architecture-wise performance comparison, with DenseNet201 achieving the highest accuracy across all categories.

* Modular training pipeline for quick experimentation and model extension.

* Outputs disease predictions with confidence scores.

## 📂 Dataset

This project uses a labeled dataset of citrus leaf images belonging to multiple disease classes.

* Preprocessing includes:

* Image resizing (224 × 224)

* Normalization

* Zoom, brightness variation


## 🧠 Model Architectures
1. ResNet101

* Deep residual network with skip connections

* Strong baseline for complex image classification tasks

* Performs well but mildly prone to overfitting

2. DenseNet201

* Dense connectivity → improved gradient flow and efficiency

* Fewer parameters compared to similar deep networks

* Highest accuracy and fastest convergence in this project

3. AlexNet

* Classic CNN architecture that popularized deep learning in vision

* Shallow compared to modern architectures

* Serves as a strong baseline for comparison

* Useful for evaluating the benefit of deeper and denser networks like DenseNet and ResNet

## ⚙️ Tech Stack

* Python

* TensorFlow / Keras

* NumPy, pandas

* scikit-learn

* Matplotlib

 # Clone the repo  
 ```
git clone https://github.com/Dattatreya2791/AgroScan-Citrus_Leaf_Disease_Detection.git
cd https://github.com/Dattatreya2791/AgroScan-Citrus_Leaf_Disease_Detection ```

 

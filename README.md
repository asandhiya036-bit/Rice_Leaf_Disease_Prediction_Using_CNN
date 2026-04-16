
# 🌾 Rice Leaf Disease Prediction using CNN

## 📌 Overview

This project focuses on detecting and classifying rice leaf diseases using Convolutional Neural Networks (CNN). Early identification of plant diseases helps farmers take timely action, improving crop yield and reducing losses.

---

## 🎯 Problem Statement

Rice is one of the most important staple crops worldwide. However, diseases such as **Bacterial Blight, Brown Spot, and Leaf Smut** significantly reduce productivity. Manual detection is time-consuming and error-prone.

👉 This project aims to automate disease detection using deep learning for faster and more accurate diagnosis.

---

## 📂 Dataset

The dataset consists of labeled images of rice leaves categorized into:

* 🌿 Healthy Leaves
* 🟤 Brown Spot
* 🦠 Bacterial Blight
* 🍂 Leaf Smut

*(Add number of images here — very important)*

---

## ⚙️ Project Workflow

1. **Data Preprocessing**

   * Image resizing
   * Normalization
   * Data augmentation (rotation, flipping)

2. **Model Building**

   * Convolutional layers for feature extraction
   * MaxPooling layers for dimensionality reduction
   * Fully connected layers for classification

3. **Training**

   * Optimizer: Adam
   * Loss Function: Categorical Crossentropy
   * Epochs: XX

4. **Evaluation**

   * Accuracy
   * Loss

---

## 🧠 CNN Architecture (Example)

* Conv2D → ReLU
* MaxPooling
* Conv2D → ReLU
* MaxPooling
* Flatten
* Dense Layers
* Output Layer (Softmax)

---

## 📊 Model Performance

* ✅ Training Accuracy: XX%
* ✅ Validation Accuracy: XX%
* 📉 Loss: XX

📌 (Add confusion matrix / accuracy graph screenshot here)

---

## 📈 Key Insights

* CNN effectively extracts features from leaf images
* Model performs well in distinguishing visually similar diseases
* Data augmentation improves model generalization

---

## 🛠 Tech Stack

* **Language:** Python
* **Libraries:** TensorFlow, Keras, NumPy, Matplotlib
* **Tools:** Jupyter Notebook

---

## 🌍 Real-World Impact

* Helps farmers detect diseases early
* Reduces dependency on manual inspection
* Supports precision agriculture

---

## 🚀 Future Improvements

* Deploy as a mobile/web application
* Use transfer learning (ResNet, MobileNet) for better accuracy
* Integrate real-time image capture

---

## 📌 Conclusion

This project demonstrates the power of deep learning in agriculture by automating disease detection and enabling data-driven farming decisions.

---

## 📁 Project Structure

```bash
Rice_Leaf_Disease_Prediction/
│── dataset/
│── notebooks/
│── model/
│── README.md
```

---

![Python](https://img.shields.io/badge/Python-3.11-blue?style=for-the-badge&logo=python)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.15-orange?style=for-the-badge&logo=tensorflow)
![Streamlit](https://img.shields.io/badge/Streamlit-1.32-red?style=for-the-badge&logo=streamlit)

**Rice Doctor AI** is a Deep Learning-based web application designed to help farmers and researchers identify rice leaf diseases instantly. Using a **Convolutional Neural Network (CNN)**, the app analyzes leaf images and provides diagnosis along with prevention remedies.




## 🚀 Live Demo
Check out the live app here:  
👉 https://bit.ly/4rasczH


## 📂 Project Structure
```text
├── app.py                      # Main Streamlit application
├── rice_leaf_disease_final.keras # Trained CNN Model
├── requirements.txt            # Python dependencies
├── runtime.txt                 # Python version specification
└── README.md                   # Project documentation


---

# 🥦 Calorie Estimation from Food Images

## 📌 Project Overview

This project aims to provide users with a convenient and intelligent system for estimating calorie content from food images.
Built using deep learning techniques, the model is trained to recognize and classify food items using a custom dataset, enabling users to make informed dietary decisions and promote healthy eating habits.

---

## 🎯 Objectives

* Classify food items from user-uploaded images
* Estimate calorie content based on recognized food types
* Provide users with guidance for healthier dietary choices
* Support fitness and wellness goals through visual analysis

---

## 🧠 How It Works

Using a **Convolutional Neural Network (CNN)**, the system processes food images, predicts the food class, and estimates the associated calorie content.
This automation helps users quickly evaluate meals without manually inputting food information.

---

## 📚 Dataset

**Dataset Used:** [Fruit and Vegetable Image Recognition](https://www.kaggle.com/datasets/kritikseth/fruit-and-vegetable-image-recognition)

* **Categories:** 36 food classes including capsicum, tomato, apple, banana, etc.
* Each class includes training, validation, and test images of food/vegetable items in various orientations and lighting conditions.

---

## 🛠️ Tools & Technologies

* **Language:** Python
* **Libraries:** TensorFlow, Keras, NumPy, Matplotlib
* **Notebook:** `calorie_prediction.ipynb`
* **Framework:** CNN built from scratch using Keras Sequential API

---

## 🏗️ Model Highlights

* Convolutional layers with ReLU activation
* MaxPooling for downsampling
* Dropout layers to reduce overfitting
* Final Dense layers for classification
* Softmax output for multi-class prediction

---

## 📈 Training & Evaluation

* **Loss Function:** Categorical Crossentropy
* **Optimizer:** Adam
* **Metrics:** Accuracy
* **Epochs:** Customizable (e.g., 10–20 epochs depending on training resources)
* Real-time visualization using training and validation accuracy/loss curves

---

## 🖼️ Sample Output

* ✅ Correctly classified food item (e.g., *Capsicum*)
* 🔢 Estimated calorie content based on food type
* 📊 Accuracy score and confusion matrix for validation performance

---

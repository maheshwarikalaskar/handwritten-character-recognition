# 🖋️ Handwritten Character Recognition (A-Z)

A deep learning-powered web app that predicts handwritten English alphabet letters (A–Z) using a trained Convolutional Neural Network (CNN) model and an interactive Streamlit interface.

---

## 📖 About the Project

The **Handwritten Character Recognition** project is a deep learning-powered web application designed to recognize handwritten English alphabet letters (A–Z). It demonstrates how machine learning and computer vision techniques can be applied to handwriting recognition tasks, which are widely used in fields like document digitization, OCR (Optical Character Recognition), and assistive technologies.

This project uses a **Convolutional Neural Network (CNN)** trained on the **EMNIST Letters** dataset to classify grayscale images of individual letters. The trained model is then deployed using a clean, interactive **Streamlit** interface, allowing users to upload handwritten characters and receive real-time predictions.

---

## 🔍 Features

- ✅ Predicts handwritten **uppercase English letters (A–Z)**
- 🧠 Uses a trained **CNN model** built with **TensorFlow/Keras**
- 🖼️ Accepts 28x28 grayscale images (EMNIST-style)
- 📷 Automatically inverts and preprocesses uploaded images
- 🎨 Simple and attractive **Streamlit web app**
- 🌐 Easy to deploy locally or on **Streamlit Cloud**

---

## 🧠 Model Details

- **Dataset:** EMNIST (Letters subset)
- **Architecture:** Convolutional Neural Network (CNN)
- **Frameworks:** TensorFlow + Keras
- **Accuracy:** ~91% on validation set
- **Output Classes:** A–Z (26 classes)

---

## 📁 Project Structure

handwritten-app/
├── app.py # Streamlit application
├── model.keras # Trained Keras model (.keras or .h5)
├── requirements.txt # Python dependencies
├── README.md # Project overview (this file)


🧪 Sample Input Format
Format: 28x28 pixel grayscale image
Content: Handwritten English alphabet
Colors: White on black or black on white (both are auto-handled)


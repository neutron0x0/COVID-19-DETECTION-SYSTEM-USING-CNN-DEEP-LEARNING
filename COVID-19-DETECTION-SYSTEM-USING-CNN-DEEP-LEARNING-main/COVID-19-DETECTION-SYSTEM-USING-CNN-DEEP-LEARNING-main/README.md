# 🚀 Unmasking COVID-19: AI-Powered X-Ray Detection with Flask

This isn't just another project; it's a critical step in accelerating COVID-19 detection using the power of **Artificial Intelligence**. This system leverages **Convolutional Neural Networks (CNNs)** to analyze chest X-ray images and detect potential signs of COVID-19 infection.

---

## 🧠 How It Works

At the core of the system lies a **CNN model** built with **TensorFlow** and **Keras**, trained on publicly available chest X-ray datasets. The model is capable of identifying subtle patterns that may indicate the presence of COVID-19.

Key highlights:
- Image preprocessing and normalization
- CNN-based binary classification (COVID-19 or Normal)
- High accuracy and optimized performance on test data

---

## 🌐 Seamless Accessibility with Flask

The trained model is deployed using a **Flask** web application that features:
- 🖼️ Image upload interface for users to submit chest X-rays
- 📸 Simulated camera-based X-ray capture (demonstration purpose)
- ⚡ Real-time inference and prediction display
- 🔒 Secure handling of uploaded files

---

## 🎯 Our Mission

This application aims to serve as a **rapid, AI-driven preliminary screening tool** to support the healthcare system:
- Not a substitute for medical diagnosis, but a **support system** to reduce diagnostic delays
- Demonstrates how deep learning can augment healthcare infrastructure during critical times

---

## 📂 Project Structure
```
├── app.py # Flask application main file
├── static/ # Static files (CSS, images)
├── templates/ # HTML templates (UI)
├── model/
│ └── covid_model.h5 # Trained CNN model
├── utils.py # Helper functions for image preprocessing and prediction
├── test_images/ # Sample test X-ray images
├── requirements.txt # Python dependencies
└── README.md # Project documentation
```
## 🧪 Datasets & Model Training
The CNN model was trained on chest X-ray images from reliable public sources like:

COVID-19 Radiography Database – Kaggle

Training and model development notebooks are available in the notebooks/ directory (optional).


OVID-19 Detection System using CNN & Flask
Unmasking COVID-19: AI-Powered X-Ray Detection with Flask
An AI-driven web application that uses Convolutional Neural Networks (CNNs) to analyze chest X-ray images and detect potential signs of COVID-19. Built with TensorFlow, Keras, and deployed using Flask, this system demonstrates how deep learning can augment healthcare screening and reduce diagnostic delays.

🚀 Features
CNN-based Detection – Binary classification: COVID-19 or Normal.

Image Preprocessing & Normalization – Ensures optimal model accuracy.

Flask Web Interface – Upload chest X-ray images or use a simulated camera capture.

Real-time Predictions – Instant AI-powered results.

Secure File Handling – Safe and efficient processing of medical images.

🧠 How It Works
Preprocesses uploaded chest X-rays (resizing, normalization).

Runs inference using a trained CNN model (covid_model.h5).

Displays prediction results (COVID-19 / Normal) with confidence score.

📂 Project Structure
csharp
Copy
Edit
├── app.py                 # Flask application
├── static/                # CSS, images
├── templates/             # HTML UI templates
├── model/                 # Trained CNN model
├── utils.py               # Preprocessing & prediction helpers
├── test_images/           # Sample X-ray images
├── requirements.txt       # Dependencies
└── README.md              # Documentation
📊 Dataset & Training
Dataset: COVID-19 Radiography Database – Kaggle

Frameworks: TensorFlow, Keras

Training: Performed on publicly available datasets with high accuracy on test data.

⚠ Disclaimer
This application is not a substitute for professional medical diagnosis. It is intended for educational and research purposes only.

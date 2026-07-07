 # 🌱 AI-Based Capsicum Plant Disease Detection System
 AI-Based Capsicum Plant Disease Detection System
📌 Project Overview

The Capsicum Plant Disease Detection project is an AI-powered image classification system that identifies diseases in capsicum (bell pepper) plants from leaf images. The application leverages deep learning to assist in early disease detection, enabling farmers and agricultural professionals to take timely preventive measures and improve crop productivity.

🎯 Objective

To develop an intelligent image classification system that accurately detects diseases in capsicum plants using deep learning and provides quick, reliable predictions from leaf images.

🚀 Features
Detects healthy and diseased capsicum leaves.
Image-based disease prediction.
User-friendly interface for uploading leaf images.
Fast and accurate predictions.
Supports early disease diagnosis for better crop management.

🛠️ Technologies Used
Python
TensorFlow
Keras
MobileNetV2
NumPy
Google Colab

🧠 Deep Learning Model
This project uses MobileNetV2, a lightweight and efficient Convolutional Neural Network (CNN) architecture optimized for image classification tasks. Transfer learning was applied by using the pre-trained MobileNetV2 model and fine-tuning it for capsicum plant disease detection, resulting in improved accuracy and faster training.

📊 Model Performance
Model: MobileNetV2 (Transfer Learning)
Training Accuracy: 99%
Validation Accuracy: 98%
Loss Function: Binary Cross-Entropy
Optimizer: Adam
Evaluation Metric: Accuracy

Project Workflow
Input Leaf Image
Image Preprocessing
Image Resizing & Normalization
Feature Extraction (MobileNetV2)
Disease Classification
Prediction Generation
Result Display (Healthy/Diseased)

▶️ How to Run the Project
Clone this repository.

Install the required dependencies:

pip install -r requirements.txt

Run the application:

python app.py
Upload a capsicum leaf image.
The system will predict whether the leaf is healthy or diseased.

🌱 Future Enhancements
Increase model accuracy with a larger and more diverse dataset.
Detect multiple capsicum diseases.
Provide treatment recommendations based on the detected disease.
Deploy the model as a web or mobile application.
Extend support to additional crop diseases.

👩‍💻 Author
Shwetha H A
BCA Graduate | Python • AI/ML Enthusiast

# edunet_fake_currency_detection
💵 Fake Currency Detection using Machine Learning
This project aims to detect fake currency notes using image processing and machine learning techniques. It uses features extracted from scanned images of Indian currency to distinguish between genuine and counterfeit notes.

📌 Problem Statement
Counterfeit currency is a serious issue affecting the economy. Manual detection is time-consuming and error-prone. This project proposes a system that automatically detects fake currency notes based on visual patterns and characteristics using machine learning.

💡 Proposed Solution
The solution involves:

Image acquisition of real and fake currency

Image preprocessing and feature extraction

Training a machine learning model (e.g., CNN or SVM)

Predicting whether a given currency note is real or fake

🔧 Tech Stack / Libraries Used
Python

OpenCV

NumPy

Matplotlib

Scikit-learn

TensorFlow/Keras (optional, if used)

⚙️ System Workflow
Data Collection – Collected real and fake note images.

Preprocessing – Applied grayscale conversion, resizing, and feature extraction.

Model Training – Trained a classification model using extracted features.

Prediction – Input note image is classified as real or fake.

🧠 Algorithm Used
The project uses image classification with feature extraction and ML algorithms such as:

CNN (Convolutional Neural Networks) (if used)

SVM (Support Vector Machine)

Logistic Regression / Random Forest (optional models)

📊 Results
Achieved good accuracy in detecting fake notes based on color, texture, and watermark features.

Successfully differentiated real and fake ₹2000 notes using visual heatmaps and predictions.

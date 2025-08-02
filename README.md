Introduction
With the increasing accessibility of photo-editing software, tampered images are becoming more common and sophisticated. Detecting such forgeries is essential to maintain the authenticity and trustworthiness of digital content across media, documentation, and legal evidence.

ForgeGuard is an AI-powered tool designed to detect manipulated images using a combination of deep learning models and traditional image forensics techniques. Our system focuses on exposing common forgery methods like splicing, copy-move cloning, and other tampering techniques.
Tech Stack
Programming Language:
Python

Libraries & Frameworks:

OpenCV
NumPy
Scikit-learn
Matplotlib
Pillow (PIL)
TensorFlow (Keras)
Flask (Backend API)
HTML, CSS

System Workflow
Data Collection & Preprocessing:
Utilized the CASIA 2.0 Image Tampering Dataset, with an 80/20 train-test split.

Model Training:
Designed and trained a CNN-based classification model to distinguish between authentic and tampered images.

Web Application Interface:
Built a Flask-based backend API with a simple HTML/CSS frontend to upload images and display results.

Feature Add-ons:
Integrated Noise Analysis, Error Level Analysis (ELA), and forged region highlighting for enhanced forgery visualization.

Results
Achieved an overall accuracy of 94.3% in detecting forged images.


Credits
Project Team:
Jayeeta Shome 
Avni Jain
Aakriti Sharma


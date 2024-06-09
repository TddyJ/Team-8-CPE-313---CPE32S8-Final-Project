# Team-8-CPE-313---CPE32S8-Final-Project
Team 8 <br>
Rojo, Maverick <br>
Roque, Jared Miguel
# Ant Species Classification Using Deep Learning
This repository contains the resources for our research on classifying ant species using deep learning and compute vision. Our goal is to improve the accuracy and efficiency of ant species identification by leveraging convolutional neural networks (CNNs) and a class-based recommendation system.
# Features
- Four Ant Species: Classifies fire ants, ghost ants, weaver ants, and little black ants.
- Models Used: Includes a custom base model, DenseNet121, EfficientNetB0, and MobielNetV2.
- Evaluation Metrics: Detailed performance metrics including accuracy, loss, precision, recall, and F1-score.
- Deployment: The model is deployed using Streamlit for easy access and practical use.
# Dataset
The custom dataset comprises 7,334 images of the four ant species, sourced primarily from Google Images. The dataset is split into training (6,330 images), validation (604 images), and test (400 images) sets.
# Methodology
1. Image Pre-processing: Images resized to 150x150 pixels, augmented with flips, rotations, brightness adjustments, and noise.
2. Model Training: Comparison of four models to determine the best performing architecture.
3. Performance Evaluation: Accuracy and loss metrics assessed on training, validation, and test datasets.
4. Model Deployment: Streamlit is used for deploying the final model, providing a user-friendly interface.
# Results
- Base Model: Test accuracy of 95.50%, demonstrating robust performance.
- DenseNet121: 98.44% training and 96.43% validation accuracy, with a test accuracy of 94%.
- EfficientNetB0: Underperformed with a test accuracy of 25%.
- MobileNetV2: High performance with a test accuracy of 93.25%.

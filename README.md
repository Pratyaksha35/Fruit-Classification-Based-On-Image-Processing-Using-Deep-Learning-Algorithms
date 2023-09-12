# Fruit-Classification-Based-On-Image-Processing-Using-Deep-Learning-Algorithms
Developed a fruit detection system using CNN and LSTM models on the Fruits-360 dataset. Achieved 94.5% accuracy with CNN, while LSTM yielded 10%. Explored future enhancements for increased accuracy and plan to extend the dataset for broader applicability.
Fruit Detection System
Introduction
This project aims to create a robust fruit detection system utilizing Convolutional Neural Networks (CNN) and Long Short-Term Memory (LSTM) models. The goal is to accurately classify various fruits and vegetables from images. The dataset used is Fruits-360, containing 90,483 images across 131 classes.

Dataset Properties
Total Images: 90,483
Training Set: 67,692 images
Test Set: 22,688 images
Classes: 131 (fruits and vegetables)
Image Size: 100x100 pixels
Algorithms Used
CNN
Employed CNN for efficient image processing.
Utilized Convolution Layer, ReLU Layer, Pooling, and Flattening for feature extraction.
Achieved an accuracy of 94.5%.
LSTM
Applied LSTM for sequence prediction.
Performed well in various tasks, especially those involving long-term dependencies.
Obtained an accuracy of 10%.
Results and Accuracy
CNN: Achieved 94.5% accuracy over 4 epochs.
LSTM: Attained 10% accuracy over 5 epochs.
Conclusion
The CNN model, implemented with transfer learning, demonstrated remarkable performance in optimization. However, overfitting issues arose due to dataset uniformity. The LSTM model showcased potential in handling sequential data. Ultimately, CNN proved superior for this project.

Future Work
Experiment with different network structures to enhance accuracy.
Transform layers into convolutional layers for improved performance.
Develop a mobile application for real-time fruit detection.
Expand the dataset to include a wider variety of fruits for greater versatility.
How to Use
Install necessary libraries: pip install -r requirements.txt.
Execute the CNN model: python cnn_model.py.
Run the LSTM model: python lstm_model.py.
Feel free to reach out for any questions or collaboration opportunities!

Note: The project is for educational and experimental purposes only.

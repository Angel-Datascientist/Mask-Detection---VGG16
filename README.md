# Mask-Detection---VGG16
This project is a real-time face mask detection system built using Transfer Learning with the VGG16-CNN architecture. It classifies whether a person is wearing a mask or not from live webcam input.

Utilizes pretrained VGG16 for feature extraction and fine-tuned for mask classification.

Built with TensorFlow/Keras and OpenCV.

Real-time video feed with Haar Cascade face detection.

Achieves high accuracy with  95% a minimal dataset using transfer learning.

Preprocess images and apply face detection,Use VGG16 (without top layers) for feature extraction and add Dense layer for binary classification using activation funtion as sigmoid.

Train and evaluate the model.

Deploy using OpenCV to detect and label faces in real-time.
##Tools Used : 
Python
TensorFlow / Keras
OpenCV
NumPy
Haar Cascade for face detection
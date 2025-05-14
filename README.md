# digit_recognition
This project is a handwritten digit recognition application that uses a Convolutional Neural Network (CNN) to classify digits drawn by the user. It features an interactive GUI built with Tkinter, where users can draw digits (0–9) and receive predictions with confidence scores.

Features:-
   Handwritten Digit Recognition
      Classifies digits (0–9) based on the MNIST dataset using a trained CNN model.
   Interactive Drawing Interface
      A simple and intuitive GUI using Tkinter where users can draw digits with their mouse.
   Model Training and Loading
      Automatically trains a new model if no saved model is found, or loads a previously saved one (digit_recognizer_model.h5).
   Image Preprocessing
      Resizes, inverts, normalizes, and crops user-drawn digits to match the MNIST input format.


Technical tools:-

Python – Core programming language
TensorFlow – For building, training, and saving the CNN model
Tkinter – For the graphical user interface
PIL (Pillow) – For image manipulation and processing
NumPy – For numerical computations and array handling

# Handwritten Digit Recognition using CNN

This project is a real-time handwritten digit recognition system built using Convolutional Neural Networks (CNN), OpenCV, and Tkinter. It uses a webcam to capture digits and predicts them using a trained CNN model.

# Features

•	Live webcam digit detection

•	Real-time digit classification

•	CNN model trained on MNIST dataset

•	Custom GUI using Tkinter

•	Easy-to-train your own dataset

# Tech Stack

•	Python

•	TensorFlow / Keras – Model building & training

•	OpenCV – Webcam integration

•	Tkinter – GUI development

•	NumPy / Matplotlib – Data handling and visualization

# How It Works

1.	Preprocessing: Input images are resized to 28x28 pixels and converted to grayscale.
   
2.	Prediction: The processed image is fed into the trained CNN model.
   
3.	GUI Display: The predicted digit is shown in the GUI using Tkinter.


 # Model Architecture (CNN)
 
Input (28x28x1)

↓

Conv2D → ReLU

↓

MaxPooling

↓

Conv2D → ReLU

↓

MaxPooling

↓

Flatten

↓

Dense → ReLU

↓

Dense → Softmax

# Limitations

•	Only works well on clearly written digits (0–9)

•	Real-time webcam support may require extra setup (OpenCV)

•	Not optimized for deployment (desktop/mobile)

# To-Do

•	Add more accuracy improvement techniques

•	Export model as .tflite for mobile deployment

•	Improve GUI design

•	Add unit & integration testing

# Acknowledgements

•	MNIST Dataset

•	TensorFlow & Keras

•	OpenCV Team

# Future Enhancements

•	Add support for user-drawn digits in GUI

•	Improve prediction speed for real-time applications

•	Export as a web app using Streamlit or Flask












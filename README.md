🖐️ Hand Gesture to Text (ASL) Translator
This project enables real-time American Sign Language (ASL) gesture recognition and translation into text and speech. The system integrates TensorFlow for training and predicting hand gestures, Mediapipe for efficient hand tracking and pose estimation, OpenCV for video capture and preprocessing, and pyttsx3 for converting recognized text into speech output.

🔍 Overview
The project captures live video feed, detects hand landmarks using Mediapipe, classifies the hand gestures into ASL alphabets using a pre-trained model built with TensorFlow, displays the recognized text on the screen, and finally converts the output text into speech.

🧠 Tech Stack
TensorFlow – For building and training the ASL classification model.

Mediapipe – For fast and robust real-time hand tracking and landmark detection.

OpenCV – For video stream capture and preprocessing.

pyttsx3 – For converting the recognized ASL gestures into spoken words (text-to-speech).

📹 Features
🔍 Real-time hand gesture detection using Mediapipe

🔤 ASL alphabet classification with a trained TensorFlow model

🗣️ Speech output for recognized gestures using pyttsx3

📷 Works with live webcam input

🧩 Easily extendable to full word or sentence recognition

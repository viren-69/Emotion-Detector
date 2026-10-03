# Emotion Detector

## Project Description

Emotion Detector is a web-based application that analyzes text and identifies emotions using the Watson NLP Emotion Prediction service.

The application detects five emotions:

- Anger
- Disgust
- Fear
- Joy
- Sadness

It also identifies the dominant emotion present in the given text.

## Technologies Used

- Python
- Flask
- Requests
- Watson NLP
- HTML
- CSS
- JavaScript

## Project Structure

Emotion-Detector/
│
├── EmotionDetection/
│   ├── __init__.py
│   └── emotion_detection.py
│
├── templates/
│   └── index.html
│
├── tests/
│   └── test_emotion_detection.py
│
├── server.py
├── requirements.txt
└── README.md

## Installation

Install the required packages:

pip install -r requirements.txt

## Running the Application

Run the Flask server:

python server.py

Open the following URL in your browser:

http://127.0.0.1:5000

## Features

- Emotion detection from text
- Identification of dominant emotion
- Flask-based web interface
- Blank input validation
- HTTP 400 error handling
- Unit testing

## Author

Emotion Detector Project

# 🎙️ SightVoice: AI-Powered Navigation and Assistance System

## 📌 Overview

SightVoice is an intelligent assistive system designed to empower visually impaired individuals by providing real-time navigation and environmental awareness through Artificial Intelligence, Computer Vision, Speech Recognition, and Natural Language Processing.

The system helps users navigate their surroundings, detect and recognize objects, read printed text aloud, identify familiar people, and interact with digital devices using voice commands and audio feedback.

---

## 🚀 Features

### 🧭 Smart Navigation

* Obstacle detection
* Audio navigation guidance
* Safe route assistance

### 👁️ Object Detection

* Real-time object recognition using YOLO
* Detects people, vehicles, doors, chairs, bottles, and more
* Voice alerts for detected objects

### 📖 Text Reading (OCR)

* Extracts text from images and documents
* Reads signboards, books, labels, and printed documents aloud

### 🎤 Speech Recognition

* Accepts voice commands from users
* Hands-free interaction

### 🔊 Text-to-Speech

* Converts system responses into audio
* Provides continuous voice feedback

### 👤 Face Recognition

* Recognizes known individuals
* Announces detected person's name

### 🤖 NLP-Based Command Processing

* Understands user intent
* Generates intelligent responses

---

## 🏗️ System Architecture

```text
Camera / Microphone
         │
         ▼
Speech Recognition Module
         │
         ▼
Command Processing Layer
         │
 ┌───────┼────────┬────────┐
 ▼       ▼        ▼        ▼
Object   OCR    Face     Navigation
Detect         Recognition
 └───────┼────────┴────────┘
         ▼
Text-To-Speech Engine
         ▼
 Audio Feedback
         ▼
       User
```

## 🛠️ Tech Stack

| Category             | Technology          |
| -------------------- | ------------------- |
| Programming Language | Python              |
| Computer Vision      | OpenCV              |
| Object Detection     | YOLOv8              |
| OCR                  | Tesseract OCR       |
| Speech Recognition   | SpeechRecognition   |
| Text-to-Speech       | pyttsx3             |
| Face Recognition     | face_recognition    |
| NLP                  | NLTK / Transformers |
| Version Control      | Git & GitHub        |

---

## 📂 Project Structure

```text
SightVoice/
│
├── app.py
├── config.py
│
├── modules/
│   ├── object_detection/
│   ├── ocr/
│   ├── speech/
│   ├── navigation/
│   ├── face_recognition/
│   └── nlp/
│
├── models/
├── datasets/
├── assets/
├── audio/
├── tests/
├── docs/
├── logs/
│
├── requirements.txt
├── README.md
├── LICENSE
└── .gitignore
```

---

## ⚙️ Installation

### Clone Repository

```bash
git clone https://github.com/your-username/SightVoice.git
cd SightVoice
```

### Create Virtual Environment

```bash
python -m venv venv
source venv/bin/activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ Running the Application

```bash
python app.py
```

---

## 🧪 Testing

Run unit tests:

```bash
pytest tests/
```

---

## 📈 Future Enhancements

* GPS-Based Outdoor Navigation
* Mobile Application (Flutter)
* Multi-Language Support
* Emergency SOS System
* Smart Glasses Integration
* Cloud-Based AI Services
* Real-Time Distance Estimation

---

## 🎯 Applications

* Assistance for visually impaired individuals
* Smart navigation systems
* Accessibility solutions
* Educational support
* Healthcare and rehabilitation technologies

---

## 👨‍💻 Team

### Team 2 – SightVoice

An AI-powered assistive system developed to improve accessibility, independence, and quality of life for visually impaired users through intelligent voice-guided assistance.

---

## 📄 License

This project is licensed under the MIT License.

---

## ⭐ Support

If you find this project useful, please consider giving it a ⭐ on GitHub.

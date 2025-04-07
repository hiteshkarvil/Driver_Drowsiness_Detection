# 🚗 Driver Drowsiness Detection System 😴

A real-time Driver Drowsiness Detection system built using Python, OpenCV, dlib, SciPy, and Pygame. This project helps prevent road accidents by alerting the driver if signs of drowsiness are detected through eye aspect ratio analysis.

## 🔍 Features

- Real-time face and eye detection
- Calculates Eye Aspect Ratio (EAR) using facial landmarks
- Triggers alarm if drowsiness is detected
- Lightweight and runs on most standard webcams

## 🛠️ Technologies Used

- Python
- OpenCV
- dlib
- imutils
- SciPy
- Pygame

## 📦 Installation

1. **Clone the repository:**

```bash
git clone https://github.com/your-username/driver-drowsiness-detection.git
cd driver-drowsiness-detection

driver-drowsiness-detection/
│
├── shape_predictor_68_face_landmarks.dat  # dlib’s pretrained facial landmark model
├── drowsiness_detection.py                # Main script
├── requirements.txt                       # Required Python packages
└── README.md                              # Project documentation


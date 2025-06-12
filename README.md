# 🧍‍♂️ Posture Rectifier using Python

> A real-time posture monitoring system built with Python and computer vision that alerts users when they slouch or maintain poor posture.

## 📌 Project Overview

The **Posture Rectifier** is a Python-based application that uses computer vision techniques to detect a user's body posture through a webcam. By identifying slouching or improper sitting/standing positions, it provides real-time feedback to encourage better ergonomics and long-term spinal health.

## 🎯 Key Features

- 📷 Real-time webcam monitoring
- 🧠 Posture detection using pose estimation models (e.g., MediaPipe, OpenCV)
- 🔔 Instant alerts for bad posture
- 📊 Visual feedback and posture classification
- 💻 Lightweight and easy to run locally

## 🧰 Technologies Used

- **Python 3**
- **OpenCV**
- **MediaPipe** (for pose estimation)
- **Numpy**
- **Matplotlib** (for optional visualization)
- **Jupyter Notebook** (for development and testing)

## 🚀 How to Run

1. **Clone the Repository**
   ```bash
   git clone https://github.com/prasadloki/Posture-Rectifier-using-Python.git
   cd posture-rectifier
   ```

2. **Install Requirements**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Notebook or Script**
   - You can open and run `Posture Rectifier.ipynb` using Jupyter Notebook
   - Or convert it to a Python script:
     ```bash
     jupyter nbconvert --to script "Posture Rectifier.ipynb"
     python "Posture Rectifier.py"
     ```

## 📸 Sample Output

Real-time tracking with posture alerts like:
- ✅ Good posture detected
- ⚠️ Warning: You are slouching


## 📁 Folder Structure

```
Posture-Rectifier-using-Python/
│
├── Posture Rectifier.ipynb       # Jupyter notebook for the app
├── requirements.txt              # Python dependencies
├── README.md                     # This file
└── assets/                       # Optional: images, models, etc.
```

## 🧠 Future Improvements

- Add posture analytics over time
- Integrate sound/vibration alerts
- Deploy as a desktop or mobile app
- Add user feedback-based calibration

## 🙌 Acknowledgements

- [MediaPipe by Google](https://mediapipe.dev/)
- [OpenCV Library](https://opencv.org/)
- Ergonomics research studies and online pose datasets
- Developed by [Prasad B](https://github.com/prasadloki)

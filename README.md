# Sentimental_analysis
Real-time Engagement &amp; Emotion Detection using OpenCV, Mediapipe, and DeepFace. This project tracks posture and torso movement to estimate engagement levels while simultaneously analyzing facial emotions with DeepFace. The system provides real-time feedback with engagement percentage and emotion labels displayed on the webcam feed.


# Engagement + Emotion Detection

This project combines **pose estimation** and **facial emotion recognition** to estimate a user's **engagement level** in real-time using a webcam.

## 🚀 Features
- **Pose-based engagement detection**
  - Uses Mediapipe Pose landmarks.
  - Calculates posture score (shoulders vs hips).
  - Detects torso movement for engagement estimation.
- **Emotion detection**
  - Uses DeepFace to recognize the dominant emotion.
- **Real-time visualization**
  - Engagement percentage and emotion labels displayed on webcam feed.

## 🛠️ Requirements
- Python 3.8+
- Webcam

Install dependencies:
```bash
pip install -r requirements.txt

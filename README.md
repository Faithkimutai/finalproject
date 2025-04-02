# finalproject
Blood Pressure Detection Using Facial Features
This project aims to estimate systolic and diastolic blood pressure using facial images captured from a webcam. It integrates real-time face detection, remote photoplethysmography (rPPG) signal extraction, and deep learning models (CNN/LSTM) for accurate blood pressure prediction.

Features:
Face Detection: OpenCV-based real-time face tracking.

rPPG Signal Extraction: Analyzes subtle facial color changes to derive pulse signals.

Blood Pressure Estimation: Uses machine learning models trained on the UBFC-Phys dataset and collected data.

Real-Time Monitoring: Displays estimated blood pressure values on a user interface.

Technology Stack:
Frontend: Tkinter-based desktop GUI

Backend: Flask/Django API

Libraries: OpenCV, TensorFlow/PyTorch, pyVHR/rPPG-Toolbox

Usage:
Run the application – Start the face detection module.

Capture real-time video – The system detects the face and extracts rPPG signals.

Estimate Blood Pressure – The model predicts and displays BP values

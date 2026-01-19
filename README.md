😴 Drowsiness Detection System (Python)

A real-time Drowsiness Detection System built using Computer Vision and Facial Landmark Detection. This project monitors eye movements through a webcam and triggers an alarm when drowsiness is detected, helping prevent accidents caused by fatigue.

🚀 Features

Real-time face detection using webcam

Eye Aspect Ratio (EAR) based drowsiness detection

Audio alarm alert when eyes remain closed for a defined duration

Simple Tkinter-based GUI to launch detection

Uses dlib’s 68 facial landmark predictor

🧠 How It Works

Captures live video stream from webcam

Detects face using dlib.get_frontal_face_detector()

Extracts eye landmarks using 68-point facial landmark model

Computes Eye Aspect Ratio (EAR)

If EAR falls below a threshold for consecutive frames:

Triggers an alarm

Displays warning message on screen

🛠️ Tech Stack

Python 3.x

OpenCV

dlib

imutils

SciPy

NumPy

pygame (for alarm sound)

Tkinter (GUI)

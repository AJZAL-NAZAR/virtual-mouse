# virtual-mouse
The Virtual Mouse is an innovative human-computer interaction system that enables users to control cursor movements and perform click operations using hand gestures instead of traditional input devices like a physical mouse. This project leverages computer vision techniques and real-time image processing to detect and track hand gestures via a standard webcam. By using libraries such as OpenCV and MediaPipe, the system identifies hand landmarks and interprets specific finger positions to simulate mouse movements and actions such as left-click, right-click, and scroll. The primary goal of this project is to provide a touchless, intuitive, and accessible alternative for users with physical disabilities or those seeking hands-free control in specific environments. The system demonstrates high accuracy and responsiveness, offering a practical solution for gesture-based control in both personal and professional computing contexts.

# Virtual Mouse using Hand Gestures 🖐️🖱️

This project implements a **Virtual Mouse** using hand gestures captured via webcam. It allows users to move the cursor, click, scroll, and control system volume and brightness — **all without touching a mouse**. It uses real-time **computer vision** powered by **MediaPipe**, **OpenCV**, and system control libraries like **pyautogui**, **pycaw**, and **screen-brightness-control**.

## ✨ Features

- Mouse movement using hand gestures
- Left-click, right-click, and double-click
- Scroll up/down and sideways
- Change system volume and screen brightness
- Gesture classification using hand landmarks and distances

---

## 📁 File Structure

- `main.py`: The main script that runs the gesture recognition and controls the system.
- No separate model files required – gestures are detected based on landmark patterns.

---

## 📦 Requirements

```bash

pip install -r requirement.txt

```
OR
Install the following packages before running the script:

```bash
pip install opencv-python mediapipe pyautogui pycaw screen-brightness-control comtypes protobuf


# Gesture-Controlled PPT Presentation

This project allows users to control PowerPoint presentations using hand gestures. It leverages computer vision to detect hand movements and maps them to slide control actions like next, previous, and pause.

---

## About

In this project, we have built a system that lets you control your presentation using hand gestures instead of buttons. This system will:

1. Use computer vision to detect the user's hands and fingers in real time.
2. Employ machine learning techniques to recognize gestures, like pointing, drawing, etc.
3. Utilize a neural network to translate hand gestures into actions on your computer, such as moving to the next slide or pausing the presentation.

This innovative approach eliminates the need for physical devices like remotes or keyboards during a presentation, making it more intuitive and seamless.

---

## Features

- **Hand Gesture Detection**: Uses a webcam to recognize predefined gestures.
- **Slide Control**: Navigate between slides, pause/resume presentations.
- **User-Friendly Interface**: Simple and intuitive for presenters.

---

## Installation

Follow these steps to set up the project on Python 3.8.10:

1. Clone the repository:
    ```bash
    git clone https://github.com/username/gesture-controlled-ppt.git
    cd gesture-controlled-ppt
    ```

2. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Ensure your Python version is 3.8.10:
    ```bash
    python --version
    ```

4. Run the application:
    ```bash
    python app.py
    ```

---

## Requirements

- Python 3.8.10
- Webcam for gesture recognition
- Libraries:
  - OpenCV
  - MediaPipe
  - python-pptx
    

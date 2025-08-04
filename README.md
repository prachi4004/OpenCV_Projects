# OpenCV_Projects
This repository contains two projects made using OpenCV in Python. The first project (motion_det.py) detects motion in the camera feed and the second project (gesture_recognition.py) detects the number of fingers shown in the camera feed.
# 🤖 Hand Gesture Recognition using OpenCV

This project detects hand gestures (1 to 5 fingers) using a webcam and recognizes them based on convexity defects and contour analysis. It uses OpenCV for image processing and Python for logic implementation.

---

## 📸 How It Works

1. Captures real-time video from your webcam.
2. Extracts a region of interest (ROI) from the frame.
3. Applies:
   - Grayscale conversion
   - Gaussian blur
   - Otsu's thresholding
4. Detects contours and finds the largest one (presumably the hand).
5. Computes convex hull and convexity defects to identify fingers.
6. Uses angles between fingers to count the number of extended fingers.
7. Displays the corresponding gesture name (`ONE`, `TWO`, ..., `FIVE`) on the screen.

---

## 🚀 Getting Started

### 🧰 Prerequisites

- Python 3.x
- OpenCV
- NumPy

### 📦 Install Dependencies

```bash
pip install opencv-python numpy
```
### ▶️ To Run the Program
```bash
python hand_gesture.py
```


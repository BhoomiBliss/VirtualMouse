# Gesture-Controlled Virtual Mouse

An academic Python prototype that uses a webcam and hand gestures to control pointer movement, clicking, and scrolling. The single-file implementation is `virtual_mouse.py`.

## What it demonstrates

- Hand landmark input with OpenCV and MediaPipe
- Gesture-based pointer and click interactions
- PyAutoGUI for desktop input

This is an interaction prototype, not an accessibility-certified product. The previous README stated “90% accuracy” without a reproducible evaluation method; that metric has been removed.

## Setup

Use Python 3 and a working webcam. Install the packages referenced in the project:

```bash
python -m pip install opencv-python mediapipe pyautogui
python virtual_mouse.py
```

The repository currently has no dependency lock or requirements file. The commands above were not run as part of this documentation update; verify package compatibility on your operating system before using desktop input automation.

## Project type

Academic mini-project.

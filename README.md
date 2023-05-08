# Advanced Computer Vision with mediapipe and OpenCV
This repository contains the code for the Advanced Computer Vision with mediapipe and OpenCV course on [freeCodeCamp.org](https://www.youtube.com/watch?v=01sAkU_NvOY).

This repository includes four Python files: `fingerCounter.py`, `HandTracking.py`, `MouseController.py` and `VolumeControlle.py`.

## fingerCounter.py
This Python script uses the Mediapipe library to detect hands in real-time and count the number of fingers displayed. 

### Requirements
- Python 3.x
- OpenCV 
- Mediapipe

### Usage
1. Clone the repository
2. Navigate to the directory where the repository is saved
3. Run the `fingerCounter.py` script:
```bash
python fingerCounter.py
```
4. The script will open the camera feed and display the number of fingers on the screen.

## HandTracking.py
This Python script uses Mediapipe to detect hands in real-time and track the landmarks of the hand.

### Requirements
- Python 3.x
- OpenCV 
- Mediapipe

### Usage
1. Clone the repository
2. Navigate to the directory where the repository is saved
3. Run the `HandTracking.py` script:
```bash
python HandTracking.py
```
4. The script will open the camera feed and draw landmarks on the detected hand.

## MouseController.py
This Python script uses Mediapipe to detect hands in real-time and tracks the landmarks of the hand to move the mouse.

### Requirements
- Python 3.x
- OpenCV 
- Mediapipe
- Autopy

### Usage
1. Clone the repository
2. Navigate to the directory where the repository is saved
3. Run the `MouseController.py` script:
```bash
python MouseController.py
```
4. The script will open the camera feed and move the mouse cursor based on the position of the hand.

Note: This script is tested on MacOS only and might need to be adjusted for other operating systems.

## VolumeController.py
This Python script uses Mediapipe to detect hands in real-time and tracks the landmarks of the hand to control the volume of the system.

### Requirements
- Python 3.x
- OpenCV
- Mediapipe
- Autopy
- PyCaw
- Numpy
- Math

### Usage
1. Clone the repository
2. Navigate to the directory where the repository is saved
3. Run the `VolumeController.py` script:
```bash
python volumeController.py
```
4. The script will open the camera feed and control the volume of the system based on the position of the hand.

### References
- Mediapipe: https://mediapipe.dev/
- Autopy: https://github.com/autopilot-rs/autopy
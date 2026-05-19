

This project is a real-time driver drowsiness detection system built using Python, OpenCV, and MediaPipe.

The main goal of this project is to help improve driver safety by detecting signs of fatigue and drowsiness through eye movement analysis. The system continuously monitors the driver's eyes using a webcam and alerts the user when drowsiness is detected.

## Features

- Real-time face and eye tracking
- Eye Aspect Ratio (EAR) calculation
- Fatigue percentage monitoring
- Drowsiness alert with alarm sound
- Night mode support for low-light environments
- Live fatigue graph visualization
- Simple and lightweight implementation

## Technologies Used

- Python
- OpenCV
- MediaPipe
- NumPy
- Pygame
- Matplotlib

## How the System Works

The webcam captures live video frames and MediaPipe detects facial landmarks.  
Using the eye landmarks, the system calculates the Eye Aspect Ratio (EAR) to determine whether the eyes are open or closed.

If the eyes remain closed for a long duration:
- the fatigue score increases
- warning messages appear
- an alarm sound is triggered

The project also includes:
- night mode enhancement for dark environments
- live fatigue graph plotting for visualization

## Installation

Install the required libraries:

```bash
pip install -r requirements.txt
```

## Run the Project

```bash
python main.py
```

## Controls

- Press `ESC` to close the application

## Project Structure

```text
Driver-Drowsiness-Detection/
│
├── main.py
├── requirements.txt
├── alarmsound.mp3
├── face_landmarker.task
├── README.md
├── LICENSE
└── .gitignore
```

## Future Improvements

Some features that can be added in the future:
- yawning detection
- head pose detection
- mobile application support
- cloud-based monitoring
- driver analytics dashboard

## Author

Mridula Karthikeyan

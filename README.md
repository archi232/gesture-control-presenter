# Gesture Control Presenter

A Python-based project that allows users to control Google Slides using hand gestures through a laptop webcam.

## Features

- Control presentations using hand gestures.
- Real-time hand tracking through webcam.
- Gesture recognition using MediaPipe.
- Keyboard automation using PyAutoGUI.

## Hand Gestures and Actions

| Hand Gesture | Action |
|---|---|
| Open Palm  | Next Slide |
| Three Fingers | Previous Slide |
| Two Fingers | Start Slideshow |
| Closed Fist  | Exit Slideshow |

## Technologies Used

- Python
- OpenCV
- MediaPipe
- PyAutoGUI

## Installation

1. Clone the repository:

```bash
git clone YOUR_REPOSITORY_URL
```

2. Open the project folder:

```bash
cd gesture-control-presenter
```

3. Create a virtual environment:

```bash
python -m venv venv
```

4. Activate it on Windows:

```bash
venv\Scripts\activate
```

5. Install the required libraries:

```bash
pip install -r requirements.txt
```

6. Download the required model:

```bash
python setup_models.py
```

7. Run the project:

```bash
python main.py
```

## How to Use

1. Open Google Slides in Chrome.
2. Run the Python program.
3. Allow webcam access if prompted.
4. Show your hand gestures in front of the camera.
5. Control your presentation using the gestures listed above.

## Learning Outcomes

- Understanding computer vision.
- Working with real-time hand tracking.
- Learning gesture recognition.
- Using Python libraries for automation.

## Future Improvements

- Add more hand gestures.
- Improve gesture detection accuracy.
- Add voice commands.
- Support more presentation controls.

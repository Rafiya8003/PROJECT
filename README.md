# Hand Gesture Recognition Mouse Controller

This Python script utilizes computer vision techniques to enable mouse control through hand gestures captured by a webcam. By detecting and tracking the positions of colored objects (representing fingertips or markers), the script interprets different gestures and translates them into corresponding mouse movements and actions.

## Features

- **Real-time Hand Gesture Recognition**: Tracks hand gestures in real-time using a webcam feed.
- **Mouse Cursor Control**: Maps hand movements to control the position of the mouse cursor on the screen.
- **Left and Right Click Simulation**: Recognizes specific gestures to simulate left and right mouse clicks.
- **Scrolling**: Supports scrolling up and down functionalities based on specific hand movements.
- **Dragging**: Implements dragging functionality by detecting specific gestures for click-and-drag actions.

## Calibration

The script allows for color calibration to adjust the detection of hand gestures based on different lighting conditions or background colors. During calibration, trackbars are provided to fine-tune the HSV color ranges for each targeted color (yellow, red, blue).

## Controls

- **P**: Toggle mouse simulation mode (ON/OFF).
- **C**: Toggle display of centroids of different colored objects.
- **R**: Enter recalibration mode to adjust color ranges.
- **ESC**: Exit the program.

## Requirements

- Python 3.x
- OpenCV
- NumPy
- PyAutoGUI

## Contributing

Contributions are welcome! Feel free to open issues or pull requests to suggest improvements, report bugs, or add new features.

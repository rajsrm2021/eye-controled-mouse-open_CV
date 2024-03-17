# Eye-Controlled Mouse using Python

This project utilizes computer vision techniques to control the mouse cursor with the movement of the user's eye. It uses the MediaPipe library for face mesh detection and PyAutoGUI for controlling the mouse cursor.

## Overview
This Python script captures the video feed from the default webcam and detects the user's face and eye landmarks using the MediaPipe FaceMesh model. It then calculates the position of the eye based on the detected landmarks and updates the mouse cursor position accordingly. Additionally, it implements left eye blink detection to simulate a mouse click action.

## Usage
1. **Requirements:** Ensure you have Python 3.x installed on your system along with the following libraries:
   - OpenCV (`pip install opencv-python`)
   - MediaPipe (`pip install mediapipe`)
   - PyAutoGUI (`pip install pyautogui`)
2. **Setup:** Connect your webcam to your computer.
3. **Execution:** Run the Python script.
4. **Usage:** Position your face in front of the webcam so that your eye is visible. Move your eye to control the mouse cursor. Blink your left eye to perform a mouse click action.

## Notes
- Ensure proper lighting conditions for better detection accuracy.
- The script detects only one face and its landmarks. For multiple face detection, additional modifications may be required.
- Adjust the blink detection threshold (`left[0].y - left[1].y < threshold`) for optimal performance based on individual eye characteristics.
- Feel free to modify and extend the script according to your specific requirements or integrate it into other projects.

## Acknowledgments
- [MediaPipe](https://google.github.io/mediapipe/) for providing the FaceMesh model.
- [PyAutoGUI](https://pyautogui.readthedocs.io/en/latest/) for mouse cursor control automation.

## Working pic

![Screenshot 2024-03-17 135721](https://github.com/rajsrm2021/Voice-Assistant---Alexa/assets/103736313/c47ac13a-0f08-4612-99f8-01089d67fb64)

## Working Demo



## Creator
[Raj Kumar Jaiswal]
[Your GitHub Profile](https://github.com/rajsrm2021)



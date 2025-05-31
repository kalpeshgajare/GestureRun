# **GestureRun - Gesture-Based Game Controller**
🎮 Control games like Temple Run & Subway Surfers using hand gestures!  
This project lets you use your webcam and simple hand movements to control games like Temple Run, Subway Surfers, and more. It uses MediaPipe, OpenCV, and Pynput to track your left wrist and simulate arrow key presses — all from a Jupyter Notebook!  

▶️ [Watch demo video](https://youtu.be/dVvS5PEz6o0?si=lFDgTaJcNi6OJxgj)


## Features
- Hand Gesture Detection using MediaPipe Holistic
- Game Controls: Jump, Slide, Move Left/Right, Start
- Keyboard Simulation with pynput
- Real-time tracking via your webcam
- Fully interactive in a Jupyter Notebook

## Requirements
Install dependencies with:
```bash  
pip install -r requirements.txt
```
## NOTE
- For MacOS - use `pynput` library   
- For Windows - use `pydirectinput` library

## Game Gestures - Working
![illustration](https://github.com/user-attachments/assets/1be3b88d-4907-4e2f-8d0d-5b757b97960e)


### Works best with games that use arrow keys (↑ ↓ ← →) like:
- Temple Run (PC version/emulator)
- Subway Surfers (on PC/BlueStacks)
- Any endless runner game with keyboard support

## Built With
- [Mediapipe](https://ai.google.dev/edge/mediapipe/solutions/guide)
- [OpenCV](https://opencv.org/)
- [Pynput](https://pypi.org/project/pynput/)
  
## License
[License](LICENSE)

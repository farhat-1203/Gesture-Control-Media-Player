# Gesture-Control-Media-Player
A simple Python-based Gesture-Controlled Media Player that uses hand gestures to control volume, play/pause, and mute functionalities. The program captures webcam feed and processes hand gestures using OpenCV to trigger specific media controls with the help of `pyautogui`.
---
## Features

- **Gesture Control**: Control media player actions using hand gestures.
  - **One Finger**: Volume Up
  - **Two Fingers**: Volume Down
  - **Three Fingers**: Mute
  - **Four Fingers**: Play
  - **Five Fingers**: Pause
- **Hand Detection**: Uses OpenCV to detect and process hand gestures in real-time.
- **Simple Media Control**: The gestures correspond to system-wide media controls (volume, play/pause) via `pyautogui`.
- **Real-time Processing**: Uses webcam input to detect and control gestures live.

---

## Tech Stack

- **Programming Language**: Python 3.x
- **Libraries Used**:
  - `opencv-python`: For capturing video and detecting hand gestures.
  - `pyautogui`: For simulating keyboard events to control media player actions.
  - `numpy`: For handling image processing tasks (e.g., array manipulation).
  - `math`: Used for calculating angles to detect the number of fingers based on convexity defects.

---

## Steps to Run the Project

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/yourusername/Gesture-Control-Media-Player.git](https://github.com/farhat-1203/Gesture-Control-Media-Player.git
    cd Gesture-Control-Media-Player
    ```

2. **Install Dependencies**:
    Install the necessary libraries using the `requirements.txt` file.
    ```bash
    pip install -r requirements.txt
    ```

3. **Run the Gesture Control Script**:
    Run the Python script to control media through gestures:
    ```bash
    python vlc-Gesture-Control.py
    ```

4. **Use Gestures**:
    - **One Finger**: Volume Up
    - **Two Fingers**: Volume Down
    - **Three Fingers**: Mute
    - **Four Fingers**: Play
    - **Five Fingers**: Pause

5. **Close the Application**:
    Press **`q`** to quit the application.

---

## Project Structure

```plaintext
gesture-control-media-player/
├── vlc-Gesture-Control.py  # Main script for gesture-controlled media player
├── LICENSE                 # License (optional)
├── README.md               # Project documentation
└── requirements.txt        # List of dependencies

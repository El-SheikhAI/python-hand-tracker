# 🖐️ AI Hand Tracking & Gesture Control

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python](https://img.shields.io/badge/python-3.9+-blue.svg)](https://www.python.org/downloads/)
[![MediaPipe](https://img.shields.io/badge/MediaPipe-0.10.21-orange)](https://developers.google.com/mediapipe)
[![OpenCV](https://img.shields.io/badge/OpenCV-4.x-green)](https://opencv.org/)

A powerful, real-time hand tracking application built with Python, OpenCV, and MediaPipe. This project demonstrates advanced computer vision techniques including gesture recognition, virtual control interfaces, and augmented reality interactions.

**Open Source & Free to Use!** 🚀

---

## ✨ Features

- **📍 Real-time Hand Tracking**: High-precision 21-point hand landmark detection.
- **fps High Performance**: Optimized with an on-screen FPS counter.
- **✋ Handedness Detection**: Automatically identifies Left vs. Right hands.
- **🔢 Finger Counter**: simple utility to count extended fingers.
- **🖥️ Always on Top**: Keep the preview window floating above other apps.

### 🧠 AI Powered Modes

| Mode | Description | Command |
| :--- | :--- | :--- |
| **🖱️ AI Virtual Mouse** | Control your computer cursor with a wave of your finger. Pinch to click! | `--mouse` |
| **🎨 Virtual Painter** | Turn your finger into a digital brush. Draw in the air! | `--draw` |
| **🔊 Volume Control** | Adjust system volume intuitively by pinching your thumb and index finger. | `--volume` |

---

## 🛠️ Installation

1.  **Clone the Repository**
    ```bash
    git clone https://github.com/yourusername/hand-tracking-app.git
    cd hand-tracking-app
    ```

2.  **Install Dependencies**
    ```bash
    pip install -r requirements.txt
    ```

    > **Note**: This project specifically handles dependency conflicts between MediaPipe and Protobuf. The `requirements.txt` is configured to ensure compatibility on Windows.

---

## 🚀 Usage

Run the main script from your terminal:

```bash
python main.py
```

### Advanced Commands

**Select Camera**
Use a different webcam (default is 0):
```bash
python main.py --camera 1
```

**Keep Window on Top**
```bash
python main.py --top
```

**Enable AI Modes**
Combine flags as needed (Note: It's best to run one mode at a time for stability):
```bash
python main.py --mouse       # Virtual Mouse
python main.py --volume      # Volume Control
python main.py --draw        # Virtual Painter
```

---

## 🎮 How to Control

- **Exit App**: Press `q` at any time.
- **Virtual Mouse**:
    - **Move**: Point with Index finger.
    - **Click**: Pinch Index + Thumb.
- **Virtual Painter**:
    - **Draw**: Index finger UP.
    - **Lift Brush**: Raise Middle finger (Two fingers up).
- **Volume Control**:
    - **Change Volume**: Pinch Thumb and Index finger together or apart. Distace = Volume Level.

---

## 🤝 Contributing

Contributions are welcome! This is an open-source project. Feel free to:
- Fork the repository.
- Create a new branch (`git checkout -b feature/AmazingFeature`).
- Commit your changes (`git commit -m 'Add some AmazingFeature'`).
- Push to the branch (`git push origin feature/AmazingFeature`).
- Open a Pull Request.

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.

---
*Built with ❤️ by El-SheikhAI*

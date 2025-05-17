# ✋ Gesture Control System using MediaPipe (Pretrained Model)

This project implements a real-time **gesture recognition system** using **Google MediaPipe** and pretrained models. It detects and classifies hand gestures from webcam input and maps them to specific control actions (e.g., volume control, screen navigation, system commands).

## 🎯 Project Objective

The aim is to build a lightweight and fast **gesture-based control interface** using prebuilt models from MediaPipe for:

- **Hand detection & tracking**
- **Gesture classification**
- **Custom gesture-to-command mapping**

This system can be extended to control applications such as media players, presentations, or smart home devices.

---

## 🛠️ Technologies Used

- **Python 3.8+**
- **MediaPipe** – for hand tracking and landmarks
- **OpenCV** – for video capture and visualization
- **NumPy** – for landmark processing
- **PyAutoGUI / OS commands** – for executing gestures as system-level controls

---

## 📁 Directory Structure
📦gesture-control-mediapipe
┣ 📂models/ # Optional: Custom pretrained models (if extended)
┣ 📂utils/ # Landmark extraction, gesture mapping
┣ 📜gesture_controller.py # Main script
┣ 📜README.md # Documentation
┣ 📜requirements.txt # Python dependencies
┗ 📜gesture_mapping.json # Config file for gesture-action mapping

## 🧪 Example Gestures
Gesture	Action
Thumbs up	Volume up
Palm open	Pause/Play media
Index + Middle	Scroll down
Fist	Screen lock

All mappings are configurable in gesture_mapping.json.

## 🧠 Extending the Project
Add more gestures using angle-based classification or a small custom ML model

Train with TensorFlow or PyTorch for more complex gestures

Integrate with smart devices or presentation tools (e.g., PowerPoint, VLC, Zoom)

## 📜 License
This project is licensed under the MIT License. See the LICENSE file for details.

## 🙋‍♀️ Author
Kavya Sharma
AI/ML Enthusiast | Computer Science
kavyasharmanishu@gmail.com

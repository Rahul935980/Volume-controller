# 🎛️ Gesture-Based System Volume Control using Python & OpenCV

Control your system volume with just your hand gestures! This project uses **Python**, **OpenCV**, **MediaPipe**, and **pycaw** to detect hand gestures via webcam and adjust your system volume based on the distance between your thumb and index finger.

---

## 🛠️ Features

* Real-time hand tracking using **MediaPipe**
* Volume control based on gesture distance
* Works with your system's default audio output
* Simple and intuitive interface

---

## 📦 Requirements

Before running the script, make sure to install the following Python libraries:

```bash
pip install opencv-python mediapipe pycaw
```

---

## 📌 How It Works

1. **Capture Video Feed**
   Access your webcam using OpenCV to capture live video frames.

2. **Detect Hands**
   Use MediaPipe Hands to detect and track your hand landmarks in real-time.

3. **Measure Gesture Distance**
   Calculate the Euclidean distance between the **thumb tip** and **index finger tip**.

4. **Map Distance to Volume Range**
   Convert the distance between fingers into a corresponding system volume level.

5. **Control Volume**
   Use **pycaw** to set the system volume based on the calculated distance.

---

## 🚀 How to Run

```bash
python gesture_volume_control.py
```

Start the script and show your hand in front of the webcam. Move your **thumb** and **index finger** closer or farther to **decrease/increase the volume**.

---

## 📷 Example

![Gesture Demo](example.gif)
*(Replace with a real demo GIF or image if available)*

---

## 🧠 Technologies Used

* **Python** — for scripting
* **OpenCV** — for video capturing and image processing
* **MediaPipe** — for hand landmark detection
* **pycaw** — for controlling system audio
* **math** — for distance calculation

---

## 🤝 Contributions

Feel free to fork, improve, and make a pull request. Suggestions and feedback are always welcome!

---



Let me know if you want me to create the actual `gesture_volume_control.py` script too.

# Rock-Paper-Scissors Object Detection

A real-time computer vision application built using Python, OpenCV, and Ultralytics YOLO.
Detect and classify Rock, Paper, and Scissors hand gestures instantly using your webcam.

---

## ✨ Features

* 🎥 Real-time hand gesture detection via webcam feed.
* 🤖 Powered by custom-trained YOLO weights (`Rock_paper_scissor_best.pt`).
* 🏷️ Displays bounding boxes, class labels, and confidence scores automatically.
* ⚙️ Configurable confidence threshold to prevent false detections.
* 🛑 Easy quit mechanism by pressing the 'q' key.

---

## 🛠️ Technologies Used

* Python
* OpenCV (`opencv-python`)
* Ultralytics YOLO (`ultralytics`)

---

## 📦 Installation

Run the following command in your terminal:
   pip install opencv-python ultralytics
  Replace webcam_detection.py with your Python filename if it is different.

  📖 How to Use
Connect your webcam to your computer.

Launch the application script.

Show your hand gestures (Rock, Paper, or Scissors) in front of the camera.

View real-time bounding boxes and classification results in the video window.

Press the q key on your keyboard to close the application.

⚠️ Requirements
Python installed on your system.

A working webcam (built-in or external USB camera).

Model weights file (Rock_paper_scissor_best.pt) 

🔮 Future Improvements
Add gesture count tracking and scorekeeping logic for a full game experience.

Improve model accuracy across diverse lighting conditions and skin tones.

Optimize frame rates for smoother video playback on lower-end devices.

👨‍💻 Author
Developed as a Python project to explore real-time computer vision and custom object detection using YOLO.

📜 License
This project is available for educational and learning purposes.

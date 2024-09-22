# 🤖 Face Recognition Attendance System

## 📖 Overview
This project implements a face recognition system that captures live video from a webcam, identifies registered users, and marks their attendance in a CSV file.

## ✨ Features
- Real-time face recognition using the `face_recognition` library.
- Attendance logging with timestamps.
- Supports multiple users with images stored in a designated folder.

## 💻 Technologies Used
- Python 🐍
- OpenCV 📸
- face_recognition 🧑‍💻
- NumPy ➕
- CSV 📄
- Datetime ⏰

## 📦 Prerequisites
- Python 3.x
- Required libraries:
  - `opencv-python`
  - `face_recognition`
  - `numpy`

## 🚀 Setup
1. Create a folder named `Training_images` in the project directory.
2. Add images of users to the `Training_images` folder. The filename should represent the user’s name (e.g., `John_Doe.jpg`).

## 🏁 Usage
1. Run the script:
   ```bash
   python face_recognition_attendance.py
   ```
2. The webcam will open, and the system will start recognizing faces.
3. When a registered face is recognized, the attendance will be logged in `Attendance.csv`, and the program will stop capturing.

## 📊 Attendance CSV File
The attendance is logged in `Attendance.csv` in the following format:
```
Name,Time
John_Doe,12:00:00
Jane_Smith,12:05:00
```

## ❌ Exit the Program
- You can manually quit the program at any time by pressing the `q` key.

## 📜 License
This project is licensed under the MIT License.

Feel free to adjust any emojis or icons to better fit your style!

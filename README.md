# Face Recognition System using OpenCV and Tkinter

This project is a complete Face Recognition System developed in Python using **OpenCV**, **Tkinter**, and **LBPH (Local Binary Pattern Histogram)** face recognizer. It provides a user-friendly GUI for capturing facial images, training a recognition model, and recognizing faces in real-time using a webcam.

---

## 🚀 Features

- 📸 **Dataset Generation**: Automatically detects and crops faces from webcam input.
- 🧠 **Model Training**: Uses OpenCV’s LBPH algorithm to train a recognition model.
- 👁️ **Real-Time Face Recognition**: Identifies known users from a live webcam feed.
- 🖥️ **Graphical User Interface (GUI)**: Built with Tkinter for ease of use.
- 🧾 **User Labeling**: Associates names with user IDs in the dataset.

---

## 🛠️ Technologies Used

- Python 3.x
- OpenCV
- NumPy
- Pillow (PIL)
- Tkinter

---

## 📁 Project Structure
- face-recognition-system/  
├── dataset/ # Stores captured facial images  
├── trainer/ # Stores trained model file (trainer.yml)  
├── haarcascade/ # Haar cascade file for face detection  
├── gui_app.py # Main GUI application  
├── dataset_generator.py # Script to generate dataset  
├── trainer.py # Script to train the face recognition model  
├── recognizer.py # Script to perform face recognition  
├── face_detector.py # Utility for detecting faces  
├── user_data.py # Dictionary for mapping user ID to names  
├── README.md # Project documentation  
└── requirements.txt # Required Python packages

---

## Install Dependencies(Terminal)
 - pip install opencv-python numpy pillow
 - pip install face_recognition opencv-python



## 👨‍💻 Author
 **Muhammad Zain Afzal**  
📍 **Pakistan**
🎓 **Information Technology**
🌐 **GitHub:** zainawan2266


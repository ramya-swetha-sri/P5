# 🧠 P5 — Face Recognition Based Smart Attendance System

> An intelligent, automated attendance system powered by Computer Vision and Machine Learning that detects, recognizes, and logs attendance in real-time.

---

## 📌 Overview

P5 is a smart automation project designed to eliminate manual attendance systems by leveraging **face recognition technology**. The system captures facial data, trains a recognition model, and automatically marks attendance when a person is identified via a live camera feed.

This project demonstrates the integration of **Machine Learning**, **Computer Vision**, and **real-time data processing** in a practical use case.

---

## 🚀 Features

* 🎯 Real-time face detection using OpenCV
* 🧠 Face recognition using trained ML models
* 📸 Dataset creation via webcam capture
* 🧾 Automated attendance logging (CSV format)
* ⚡ Fast and efficient recognition pipeline
* 🖥️ Simple and easy-to-use interface
* 🔄 Model training and retraining support

---

## 🏗️ Project Structure

```bash
P5/
│
├── dataset/                # Stored face images for training
├── trainer/                # Trained model files
├── attendance.csv          # Attendance records
├── haarcascade_frontalface_default.xml  # Face detection model
│
├── capture.py              # Capture images for dataset
├── train.py                # Train the recognition model
├── recognize.py            # Recognize faces and mark attendance
├── main.py                 # Main execution script
│
└── README.md               # Project documentation
```

---

## ⚙️ Tech Stack

| Category        | Technology Used         |
| --------------- | ----------------------- |
| Language        | Python                  |
| Computer Vision | OpenCV                  |
| Data Handling   | NumPy, Pandas           |
| ML Algorithm    | LBPH / Face Recognition |
| Storage         | CSV / Local Files       |

---

## 🔄 How It Works

### 1️⃣ Dataset Creation

* Capture multiple images of each individual
* Images are stored in the `dataset/` folder

### 2️⃣ Model Training

* The system processes dataset images
* Extracts facial features
* Trains a recognition model

### 3️⃣ Face Recognition

* Webcam captures live video
* Faces are detected in real-time
* Recognized faces are matched with stored data

### 4️⃣ Attendance Logging

* Recognized individuals are marked present
* Data is stored in `attendance.csv`

---

## ▶️ Installation & Setup

### 🔧 Prerequisites

Make sure you have:

* Python 3.x installed
* Webcam enabled

### 📦 Install Dependencies

```bash
pip install opencv-python numpy pandas
```

---

## ▶️ Usage

### Step 1: Capture Dataset

```bash
python capture.py
```

### Step 2: Train the Model

```bash
python train.py
```

### Step 3: Run Recognition System

```bash
python recognize.py
```

---

## 📊 Sample Output

* Real-time face detection window
* Bounding box around detected faces
* Name displayed upon recognition
* Attendance logged automatically

---

## 📈 Applications

* 🏫 Educational Institutions
* 🏢 Office Attendance Systems
* 🔐 Security & Access Control
* 🧾 Identity Verification Systems

---

## ⚠️ Limitations

* Performance depends on lighting conditions
* Limited accuracy with masks or occlusions
* Requires proper dataset for better results
* Not optimized for large-scale deployment

---

## 🔥 Future Enhancements

* 🤖 Deep Learning integration (FaceNet / Dlib)
* ☁️ Cloud database (Firebase / AWS)
* 📱 Mobile app connectivity
* 🛡️ Anti-spoofing detection
* 📊 Admin dashboard with analytics
* 🌐 Web-based interface

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some feature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📜 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

**Ramya Swetha Sri**

* GitHub: https://github.com/ramya-swetha-sri

---

## ⭐ Support

If you like this project:

* ⭐ Star the repository
* 🍴 Fork it
* 📢 Share it

---

## 💡 Final Note

This project is a strong foundation for building **AI-powered automation systems**. With further enhancements, it can evolve into a **scalable, production-ready smart surveillance or attendance platform**.

---

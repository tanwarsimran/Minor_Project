# 🚗 Car Detection System (OpenCV)

![Python](https://img.shields.io/badge/Python-3.6+-blue?logo=python)
![OpenCV](https://img.shields.io/badge/OpenCV-Computer%20Vision-green)
![Status](https://img.shields.io/badge/Project-Completed-success)

---

## 📌 Overview

A **real-time Car Detection System** built using **OpenCV and Haar Cascade Classifier** that detects vehicles from video streams and highlights them with bounding boxes.

This project demonstrates core concepts of:

* Computer Vision 👁️
* Object Detection 🚗
* Image Processing 🧠

---

## 🎯 Key Features

✅ Real-time car detection
✅ Lightweight & fast processing
✅ Works on video input
✅ Easy to understand implementation
✅ Uses Haar Cascade (no heavy ML model required)

---

## 🧠 How It Works

The system follows a step-by-step pipeline:

```
Video Input → Frame Extraction → Grayscale Conversion → 
Haar Cascade Detection → Bounding Box → Display Output
```

---

## 📊 Project Visualizations

<img width="760" height="768" alt="Image" src="https://github.com/user-attachments/assets/04d4064a-b0a0-40e1-b09e-90fc03eb9ea5" />
<img width="842" height="534" alt="Image" src="https://github.com/user-attachments/assets/eccf6d19-eb52-4c71-9501-3f0b5f5e9106" />
<img width="878" height="690" alt="Image" src="https://github.com/user-attachments/assets/87cee405-da93-4a6f-aa28-9e47611b2343" />

<img width="691" height="502" alt="Image" src="https://github.com/user-attachments/assets/e9b5bdd0-a780-4391-9877-72b852f85c85" />

---

## ⚙️ Tech Stack

| Technology      | Purpose          |
| --------------- | ---------------- |
| Python 🐍       | Core Programming |
| OpenCV 👁️      | Image Processing |
| Haar Cascade 📊 | Object Detection |

---

## 📂 Project Structure

```
Car-Detection-System/
│
├── Car_detection.py     # Main detection script
├── cars.xml             # Haar cascade classifier
├── assets/              # Images for README (graphs)
└── README.md
```

---

## 🚀 Installation & Setup

### 1️⃣ Clone Repository

```bash
git clone https://github.com/your-username/car-detection-system.git
cd car-detection-system
```

### 2️⃣ Install Dependencies

```bash
pip install opencv-python
```

### 3️⃣ Run the Project

```bash
python Car_detection.py
```

---

## 🖥️ Output

* Detects cars in video 🎥
* Draws bounding boxes 📦
* Labels detected objects as "Car"

---

## 📌 Code Explanation

The system performs:

* Capture video using `cv2.VideoCapture`
* Convert frames to grayscale
* Detect cars using `detectMultiScale`
* Draw rectangles around detected cars
* Display results in real-time window 

---

## 🔮 Future Improvements

🚀 Add YOLO (Deep Learning Model)
🚀 Improve detection accuracy
🚀 Add vehicle counting system
🚀 Deploy as web app

Feel free to fork this repo and improve it!

---

## ⭐ Support

If you like this project:

👉 Star ⭐ this repository
👉 Follow for more ML projects

---

## 👨‍💻 Author

**Devashish Srivastava | **
**Simran Tanwar | **
**Priyanshu Sharma | **
**Amit Mishra | **
**Naitik Jain**

---

## 💡 Why This Project Matters

This project showcases:

* Practical implementation of Computer Vision
* Strong fundamentals in OpenCV
* Clean and understandable logic
* Real-world application (traffic systems, surveillance)


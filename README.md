🚗 Car Detection using OpenCV

This project is a simple implementation of a car detection system using OpenCV and Haar Cascade classifiers.
It processes a video file frame-by-frame and detects cars in real time.

🧠 About the Project

I built this project to understand how object detection works using classical computer vision techniques (before jumping into deep learning).

Instead of using heavy models, this project uses a pre-trained Haar Cascade (cars.xml) to detect vehicles efficiently.

⚙️ How it works
Reads video input using OpenCV
Converts each frame to grayscale (required for Haar detection)
Applies detectMultiScale() to find cars
Draws bounding boxes around detected vehicles
Displays both:
Full video with detections
Cropped view of detected cars

Reference from the implementation:

🛠️ Tech Used
Python
OpenCV
Haar Cascade Classifier
📁 Files
main.py        -> detection logic  
cars.xml       -> trained classifier  
vb.mp4         -> sample video input  
▶️ Run Locally
pip install opencv-python
python main.py

Make sure:

cars.xml is in the same folder
Video file path is correct
📸 Output
Cars are detected and highlighted with rectangles
A separate window shows detected regions (cars)
Press ESC to exit
🚧 Limitations
Haar Cascades are not very accurate compared to modern models
Performance depends on lighting and camera angle
May detect false positives
🚀 Future Improvements
Add car counting feature
Use YOLO / Deep Learning models for better accuracy
Real-time detection using webcam
Traffic analytics (density, speed estimation)
👨‍💻 Author

Simran

#📌 Overview

This project is a simple motion detection system built using Python and OpenCV. It captures video from a webcam and detects motion by comparing consecutive frames. When motion is detected, a bounding box is drawn around the moving object, and a message is displayed on the screen.

🚀 Features
Real-time motion detection using webcam
Frame differencing technique
Noise reduction using Gaussian Blur
Contour detection for identifying moving objects
Bounding box around detected motion
"Motion Detected" alert on screen
🛠️ Technologies Used
Python
OpenCV (cv2)
NumPy
📂 Project Structure
motion.py        # Main Python script for motion detection
README.md        # Project documentation
▶️ How It Works
Captures two consecutive frames from the webcam
Computes the difference between frames
Converts the result to grayscale
Applies Gaussian blur to reduce noise
Uses thresholding to highlight motion areas
Detects contours of moving objects
Draws rectangles around detected motion
⚙️ Installation
1. Install Dependencies
pip install opencv-python numpy
2. Run the Program
python motion.py
🎮 Controls
Press ESC key to exit the program
📸 Output
Live webcam feed
Green rectangles around moving objects
"Motion Detected" text displayed when motion is found
⚠️ Limitations
Sensitive to lighting changes
May detect noise as motion
Works best in a stable environment

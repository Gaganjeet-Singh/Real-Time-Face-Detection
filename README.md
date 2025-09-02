# Face Detection with OpenCV  
A simple real-time face detection project using **Python** and **OpenCV Haarcascades**.  

## 📖 About the Project  
This project demonstrates how to detect human faces in images or webcam video streams using OpenCV’s **Haar Cascade Classifier**.  
The program converts frames to grayscale, applies the Haarcascade model, and draws bounding boxes around detected faces.  
It’s a beginner-friendly project that can be extended to applications like face recognition, emotion detection, or smart surveillance systems.  

## ⚙️ How It Works  
1. Load the Haar Cascade Classifier (`haarcascade_frontalface_default.xml`)  
2. Capture input from image or webcam  
3. Convert frames to grayscale for faster processing  
4. Apply the classifier to detect faces  
5. Draw bounding boxes around detected faces  

## 🚀 Features  
- Detects faces in images or live video  
- Lightweight and fast  
- Easy to set up and run  

## 🔧 Installation & Usage  
```bash
git clone https://github.com/your-username/face-detection.git
cd face-detection
pip install opencv-python
python face_detection.py

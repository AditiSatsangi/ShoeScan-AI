# 📱ShoeScan-AI: Shoe Defect Detection App

This project is an AI-powered mobile app designed to detect shoe manufacturing defects. Users can capture or upload images of shoes, and the app will classify whether the shoe is defective or non-defective using advanced deep learning models (YOLO, CNN, etc.).

## 🧠 Features
⚙️ Deep learning-based defect detection

📱 User-friendly Android application

📦 Supports both camera and gallery inputs

✅ Classifies shoes as Defective or Non-Defective

🧪 Trained on real-world annotated shoe images

## 🚀 App Download
Click the link below to download and install the Android app: 
https://drive.google.com/file/d/1uNu77SQ-Z952DHfmnJBUcoHJLbsxtKie/view?usp=sharing  

## 📲 Download APK

💡 Enable "Install from Unknown Sources" on your Android device before installing.

## 📂 Dataset
The training and testing dataset used for model development is available here:  https://drive.google.com/drive/folders/1qh34dE22wqDFTpzncKuYZppcDS8e7MZ-?usp=drive_link 

## 📁 Dataset Drive Folder

It contains:

Defective shoe images

Non-defective shoe images

Annotated labels (for YOLO training)

Compressed data for easier sharing

## 🛠️ Technologies Used
🔍 YOLOv5 / YOLOv8 for defect detection

🧠 CNN models for classification

📱 TFLite for mobile model deployment

🧰 Python, OpenCV, TensorFlow, Android (Kotlin or Java)

## 📸 How It Works
Launch the app

Upload or capture a shoe image

The model detects:

Defect present → shows defect label

No defect → shows "No Defect"

## 📦 Folder Structure
📁 Code used for Model Implementation/
  ├── Code used for YOLO models.ipynb
  ├── Code used for CNN models.ipynb
  ├── Final_deploy.ipynb
  ├── XAI- Code.py

📁 Code used for App Deployment/
  ├── android_app/ (Android Studio project files)
  ├── gradle/
  ├── settings.gradle.kts
  
## 📌 Future Work

More fine-grained defect types

Web dashboard for quality control monitoring

## 🤝 Acknowledgments
Special thanks to the contributors and mentors who guided this project.









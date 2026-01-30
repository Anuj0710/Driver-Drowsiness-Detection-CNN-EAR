# Driver Drowsiness Detection using CNN and Eye Aspect Ratio

This project implements a real-time driver drowsiness detection system using a hybrid
computer vision approach combining Convolutional Neural Networks (CNN) and Eye Aspect Ratio (EAR).

## 🔍 Project Overview
Driver fatigue is a major cause of road accidents. This system monitors eye behavior
using a webcam and detects drowsiness by combining deep learning and geometric features.

## 🧠 Methodology
- CNN-based eye state classification (open / closed)
- Eye Aspect Ratio (EAR) computation using facial landmarks
- Temporal analysis across consecutive frames
- Real-time alert generation for prolonged eye closure

## 📊 Dataset
- **MRL Eye Dataset**
- Grayscale eye images (open and closed)
- Dataset split using training and validation subsets

## 🚀 Model Performance
- Validation Accuracy: ~94%
- Balanced confusion matrix for both eye states
- Robust against blinking and lighting variations due to hybrid logic

## 🛠 Tech Stack
- Python
- TensorFlow / Keras
- OpenCV
- Dlib
- NumPy, Matplotlib

## 📂 Project Structure
See repository folders for notebooks, models, and source code.

## ⚠️ Limitations
- Performance may degrade under extreme lighting or occlusion
- Does not include physiological signals (heart rate, head pose)

## 🔮 Future Improvements
- Head pose estimation
- Mobile or embedded deployment
- Multi-modal fatigue detection

## ▶️ How to Run
1. Install dependencies from `requirements.txt`
2. Run the Jupyter notebook for training
3. Execute real-time detection script for webcam inference

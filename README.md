## A vision-based system for detecting stress using facial features with Machine Learning and Deep Learning.

## 🔍 Overview

This project presents a vision-based system to detect stress levels in students during programming tasks using facial features.

Two approaches are implemented:

* **Full-face stress detection** (captures multiple facial features for higher accuracy)
* **Eyebrow-based stress detection** (privacy-preserving and computationally efficient)

---

## 🧠 Models Used

### Machine Learning:

* Support Vector Machine (SVM)
* Random Forest (RF)
* XGBoost
* Gradient Boosting

### Deep Learning:

* Convolutional Neural Networks (CNN)
* MobileNetV2 (Transfer Learning)

---

## ⚙️ Methodology

The system follows a **two-stage classification approach**:

1. **Stage 1:**

   * Classifies whether a person is *Stressed* or *Not Stressed*

2. **Stage 2:**

   * Classifies stress levels into:

     * Low
     * Medium
     * High

---

## 📊 Feature Extraction

### Eyebrow-Based Features:

* Texture features (GLCM)
* Edge density
* Intensity statistics (mean, standard deviation)
* Gradient-based features
* Shape and thickness-related features

### Full-Face Features:

* Eye Aspect Ratio (EAR)
* Eyebrow distance
* Mouth opening
* Jaw tension
* Head tilt
* Facial symmetry
* Skin texture
* Forehead tension

---

## 📈 Results

* Achieved accuracy up to **96%**
* Deep learning models (MobileNetV2) showed strong performance
* Eyebrow-based approach provided a good balance between accuracy and privacy

---

## 📁 Dataset

* 38 students participated
* 4000+ images extracted from video recordings
* Data preprocessed using resizing and normalization techniques

**Note:** Dataset is not uploaded due to size and privacy concerns.

---

## 🚀 Key Highlights

* Two-stage stress classification framework
* Combination of ML and DL approaches
* Privacy-preserving eyebrow-based analysis
* Real-time capable system
* Adaptive stress analysis using facial features

---

## 👨‍💻 My Contribution

* Collected and prepared the dataset from classroom recordings
* Converted videos into frames for analysis
* Performed facial landmark detection and extracted eyebrow region
* Developed an eyebrow-based stress detection pipeline
* Engineered features including GLCM, edge density, intensity, and gradient features
* Implemented multiple ML models (SVM, Random Forest, XGBoost, Gradient Boosting)
* Applied deep learning models (CNN and MobileNetV2) for eyebrow-based stress classification
* Focused on privacy-preserving stress detection using only eyebrow features

---

## 👥 Team Members

* Gowtham B J
* Sohan Ponnappa P M
* Shreyas M
* Harish C R

---

## 🎓 Guide

* Mr. Akshay S

---

## 🛠️ Technologies Used

* Python
* OpenCV
* MediaPipe
* Scikit-learn
* TensorFlow / Keras
* NumPy, Matplotlib

---

## 📌 Future Improvements

* Real-time video-based stress tracking
* Improved robustness to lighting and head movement
* Larger and more diverse dataset
* Temporal analysis using video sequences

---

## 📬 Contact

For any queries or collaboration:

* Gowtham BJ

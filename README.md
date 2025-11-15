# 🩺 AI-Based Skin Disease Detection Using Deep Learning

This project aims to automatically detect and classify **skin diseases** from images using **Convolutional Neural Networks (CNN)** and **Transfer Learning**.  
Built with **Streamlit**, it provides an interactive web interface for users to upload skin images and receive instant AI-based predictions.

---

## 🚀 Features
- 🧠 **Deep Learning (CNN) Model** for multi-class skin disease detection  
- 📸 Supports **image upload** and real-time prediction  
- ⚙️ **Transfer Learning** using MobileNetV2 / ResNet for 95% accuracy  
- 💧 **Skin Type Detection** (Oily, Dry, Normal)  
- 💡 **Personalized Skincare Recommendations**  
- 🌐 **Streamlit Web App** for user-friendly interaction  

---

## 🧩 Project Workflow
1. User uploads a skin image through the Streamlit interface.  
2. The image is preprocessed (resized and normalized).  
3. The CNN model predicts the disease category among **19 types**.  
4. Another CNN detects the user’s skin type.  
5. The app provides disease information and personalized care suggestions.

---

## 🧠 Technologies Used
- **Python**
- **TensorFlow / Keras**
- **Streamlit**
- **NumPy**, **Pandas**
- **Pillow (PIL)**
- **Matplotlib**

---

## 📂 Project Structure
AI_Skin_Disease_Detection/
│
├── app.py # Main Streamlit Frontend
├── 1_Detect_Skin_Disease.py # Backend Prediction Logic
├── final_skin_model.1.keras # Trained CNN Model
├── skin_type_model.keras # Skin Type Model
├── requirements.txt # Dependencies
└── README.md # Project Documentation



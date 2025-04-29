# WAVELET-BASED LUNG CANCER CLASSIFIER WITH GESTURE INTERFACE
An advanced **automated lung cancer diagnosis system** using CT scan images, integrating **wavelet-based image processing** and **machine learning algorithms** for accurate stage classification. The system also features a **gesture-based interface** for hands-free, efficient interaction by medical professionals.

---

## 📌 Project Overview

The Wavelet-Based Lung Cancer Classifier is designed to improve the early detection and treatment of lung cancer. By analyzing CT scan images, the system:
- Identifies tumors
- Classifies the stages of cancer
- Assesses tumor severity for better treatment planning

A gesture-controlled interface enhances usability, allowing medical professionals to interact with the system without physical contact, promoting efficiency, hygiene, and convenience in clinical environments.

This project combines advancements in:
- Artificial Intelligence (AI)
- Computer Vision
- Human-Computer Interaction (HCI)

It aims to support radiologists and clinicians in making **more informed and timely decisions**, ultimately improving patient outcomes.

---

## 🛠️ Technologies Used

| Area                      | Tools / Libraries             |
|----------------------------|-------------------------------|
| Programming Language       | Python                        |
| Image Processing           | OpenCV, PyWavelets             |
| Machine Learning           | TensorFlow / Scikit-learn      |
| Gesture Interface          | MediaPipe, OpenCV HandTracking |
| GUI Development (Optional) | Tkinter or PyQt                |

---

## 🧠 Key Features

- **Automated CT Scan Analysis**  
- **Tumor Detection and Stage Classification**  
- **Wavelet Transform for Feature Extraction**  
- **Gesture-Based User Interface for Hands-Free Interaction**  
- **Enhanced Diagnostic Speed and Precision**

---

## 🚀 How It Works

1. **Image Input**: Upload lung CT scan images into the system.
2. **Preprocessing**: Apply wavelet transform to extract critical features.
3. **Classification**: Use machine learning models to predict cancer stage.
4. **Gesture Interaction**: Use hand gestures to navigate and control the system.

---

## 🖼️ Future Scope

- Integration with hospital systems (PACS)
- Real-time processing for large CT datasets
- Expansion to classify other pulmonary diseases

---

## 📂 Folder Structure
.
├── Lung_Cancer_Prediction.ipynb
├── README.md
├── dataset
│ ├── train
│ │ ├── adenocarcinoma_left.lower.lobe_T2_N0_M0_Ib
│ │ ├── large.cell.carcinoma_left.hilum_T2_N2_M0_IIIa
│ │ ├── normal
│ │ └── squamous.cell.carcinoma_left.hilum_T1_N2_M0_IIIa
│ ├── test
│ │ ├── adenocarcinoma_left.lower.lobe_T2_N0_M0_Ib
│ │ ├── large.cell.carcinoma_left.hilum_T2_N2_M0_IIIa
│ │ ├── normal
│ │ └── squamous.cell.carcinoma_left.hilum_T1_N2_M0_IIIa
│ └── valid
│ ├── adenocarcinoma_left.lower.lobe_T2_N0_M0_Ib
│ ├── large.cell.carcinoma_left.hilum_T2_N2_M0_IIIa
│ ├── normal
│ └── squamous.cell.carcinoma_left.hilum_T1_N2_M0_IIIa
└── best_model.hdf5


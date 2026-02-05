# 🧠 Brain Tumor Detection using CNN (MRI Images)

A Deep Learning based Computer Vision project that detects **Brain Tumor from Brain MRI scans** using **Convolutional Neural Networks (CNN)**.

This model classifies MRI images into:

✔ Tumor (yes)  
✔ Normal (no)

---

# 🎯 Project Objective

Manual MRI diagnosis is slow and requires medical experts.

This system:
- Automatically analyzes MRI scans
- Detects tumor presence
- Gives fast & accurate predictions
- Demonstrates Medical AI using Deep Learning

---

# 📂 Dataset

Brain MRI Images for Brain Tumor Detection

Classes:
- yes → Tumor
- no → Normal

Original structure:

brain_tumor_dataset/
│
├── yes/
├── no/

After automatic train-test split:

data/
│
├── train/
│   ├── yes/
│   ├── no/
│
├── test/
│   ├── yes/
│   ├── no/

Train/Test ratio = 80/20

---

# 🛠 Tech Stack

- Python
- TensorFlow / Keras
- NumPy
- Matplotlib

---

# ⚙️ Features

✅ Automatic dataset split  
✅ Image preprocessing  
✅ Data augmentation  
✅ CNN training  
✅ Model saving (.h5)  
✅ Single image prediction  
✅ Accuracy & loss visualization  

---

# 🧠 Workflow

Raw Images  
↓  
Train/Test Split  
↓  
Resize (224x224)  
↓  
Normalize (0–255 → 0–1)  
↓  
Data Augmentation  
↓  
CNN Training  
↓  
Save Model  
↓  
Prediction  

---

# 🧪 Preprocessing Steps

Training data uses:

- Rescaling
- Rotation
- Zoom
- Shift
- Horizontal flip

Benefits:
- Improves generalization
- Prevents overfitting
- Increases dataset size

---

# 🧠 CNN Architecture

Conv2D(32)  → MaxPool  
Conv2D(64)  → MaxPool  
Conv2D(128) → MaxPool  
Flatten  
Dense(128)  
Dropout(0.5)  
Dense(1, Sigmoid)

Binary classification → Sigmoid activation

---

# ▶️ How to Run

Step 1 — Split dataset

python split_data.py

Step 2 — Train model

python train.py

Step 3 — Predict image

python predict.py

---

# 👨‍💻 Author

Yuvraj Bhavsar  
Machine Learning & Deep Learning Enthusiast

---

# ⭐ If you like this project

Give it a star on GitHub ⭐

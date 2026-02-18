markdown
Copy code
# ✋ Hand Gesture Recognition using SVM (Synthetic Data)

This project implements a **Hand Gesture Recognition system** using a **Support Vector Machine (SVM)** classifier.  
Instead of real images, **synthetic grayscale gesture images** are generated to demonstrate how SVM can be applied to image-based classification problems.

This project is ideal for **machine learning practice**, **college assignments**, and **SVM algorithm demonstration**.

---

## 📌 Features

- Synthetic hand gesture image generation
- Grayscale image processing
- Train–test data splitting
- SVM-based multi-class classification
- Accuracy evaluation and classification report
- Visualization of predicted gesture

---

## 📂 Project Structure

Hand-Gesture-SVM/
│
├── hand_gesture_svm.py
├── requirements.txt
└── README.md

yaml
Copy code

---

## 🧠 Gestures Supported

Example gesture classes:
- Fist
- Palm
- Thumbs Up
- Thumbs Down

(Exact gestures depend on the `gesture_names` list in the code.)

---

## ⚙️ How the Code Works

1. Generates synthetic grayscale images representing hand gestures
2. Flattens image data into feature vectors
3. Assigns gesture labels
4. Splits data into training and testing sets
5. Trains an SVM classifier
6. Evaluates accuracy and prints classification report
7. Displays a test image with predicted gesture label

---

## ▶️ How to Run

### Step 1: Clone the Repository
```bash
git clone https://github.com/your-username/Hand-Gesture-SVM.git
cd Hand-Gesture-SVM
Step 2: Install Required Libraries
bash
Copy code
pip install -r requirements.txt

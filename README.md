# 🔍 Real-Time Disaster Response System (ML Model)

This project is part of a larger real-time disaster response system. It focuses on the **machine learning component** that classifies the type or severity of a natural disaster based on input features like rainfall, magnitude, temperature, and more.

---

## 🎯 Project Goal

To build a machine learning model that can:
- Predict the **type of disaster** (e.g., flood, earthquake)
- Or classify the **severity level** (e.g., high-risk vs low-risk)

This component is intended to be integrated later into a full disaster response platform with real-time alerts and visualization.

---

## 🧠 What’s Inside

- `Real-Time Disaster Response System.ipynb`: The full notebook with data preprocessing, model training, and evaluation.
- `train.csv`: CSV file listing image paths and their corresponding labels (used for training).
- `test.csv`: CSV file for validation/testing.
- `requirements.txt`: Python dependencies used in this project.
- `README.md`: You’re reading it!

---

##  📊 About Dataset
1. Images are collected from Google, it may be noisy and different resolutions, therefore, preprocessing is recommended.
2. Please remove irrelevant image if necessary
3. Number of image samples in each class is different which may result biased model. Select images according to your application.
4. I tried to remove duplicate images, still there may be some. Delete those images before training the model.

---

## ⚙️ Technologies Used

- TensorFlow + Keras
- TensorFlow Hub
- Transformers (HuggingFace)
- OpenCV
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- NLTK
- WordCloud


---

## 🚀 How to Run Locally

1. **Clone the repository**
```bash
git clone https://github.com/your-username/real-time-disaster-ml.git
cd real-time-disaster-ml


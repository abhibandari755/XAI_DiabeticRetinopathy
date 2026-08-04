# 👁️ XAI Diabetic Retinopathy Detection

An Explainable Artificial Intelligence (XAI) based Deep Learning project for the automated detection of **Diabetic Retinopathy** from retinal fundus images. The project combines high-performance image classification with explainability techniques such as **Grad-CAM** to help visualize the regions that influence the model's predictions.

---

## 📌 Overview

Diabetic Retinopathy (DR) is one of the leading causes of blindness among diabetic patients. This project uses Deep Learning and Explainable AI to classify retinal images and provide visual explanations for the predictions, improving model transparency and trust.

---

## 🚀 Features

- 🩺 Automatic Diabetic Retinopathy Detection
- 🧠 Deep Learning-based Image Classification
- 🔍 Explainable AI using Grad-CAM
- 📊 Model Evaluation Metrics
- 📈 Training & Validation Visualization
- 💻 User-friendly interface (if applicable)

---

## 🛠️ Tech Stack

- Python
- TensorFlow / Keras (or PyTorch)
- OpenCV
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- Grad-CAM
- Streamlit (if used)

---

## 📂 Project Structure

```
XAI_DiabeticRetinopathy/
│
├── dataset/
├── models/
├── notebooks/
├── app.py
├── train.py
├── predict.py
├── requirements.txt
├── README.md
└── outputs/
```

---

## 📦 Installation

### Clone the Repository

```bash
git clone https://github.com/your-username/XAI_DiabeticRetinopathy.git
cd XAI_DiabeticRetinopathy
```

### Create a Virtual Environment

```bash
python -m venv venv
```

Activate the environment:

**Windows**

```bash
venv\Scripts\activate
```

**Linux/macOS**

```bash
source venv/bin/activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ Running the Project

Train the model:

```bash
python train.py
```

Run prediction:

```bash
python predict.py
```

If using Streamlit:

```bash
streamlit run app.py
```

---

## 📊 Dataset

The project uses retinal fundus images for Diabetic Retinopathy classification.

Example classes:

- No DR
- Mild
- Moderate
- Severe
- Proliferative DR

---

## 🧠 Explainable AI

This project implements **Grad-CAM** to generate heatmaps highlighting the regions of retinal images that influenced the model's prediction.

Benefits:

- Improved transparency
- Increased trust in AI predictions
- Better clinical interpretation

---

## 📈 Model Performance

Example metrics:

| Metric | Score |
|--------|-------|
| Accuracy | XX% |
| Precision | XX% |
| Recall | XX% |
| F1 Score | XX% |

Replace with your actual results.

---

## 📸 Screenshots

Add screenshots here:

- Home Page
- Prediction Result
- Grad-CAM Visualization
- Accuracy/Loss Graph

---

## 📋 Requirements

Install dependencies using:

```bash
pip install -r requirements.txt
```

---

## 👨‍💻 About the Author

**Abhinaya Sri Bandari**

Aspiring AI & Machine Learning Engineer passionate about building intelligent applications using Deep Learning, Computer Vision, Generative AI, and Explainable AI (XAI).

- 🌐 GitHub: https://github.com/abhibandari755
- 💼 LinkedIn: https://www.linkedin.com/in/abhinaya-sri-bandari-489571324/

Feel free to connect with me for collaborations, project discussions, or AI-related opportunities.

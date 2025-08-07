# 🥔 Potato Leaf Disease Detection using Deep Learning

A web-based AI system that detects diseases in potato plant leaves from images, built using **TensorFlow**, **Flask**, and **React**. The system provides real-time predictions with confidence scores and (optionally) suggests treatments based on severity.

---

## 🌱 Motivation

Potato crops are vulnerable to various leaf diseases that can significantly reduce yield. Farmers often lack access to timely, expert diagnosis. This project aims to bridge that gap with a simple yet powerful AI tool that:
- Identifies common potato leaf diseases
- Works in the browser via an intuitive web interface
- Provides disease names and prediction confidence
- (Optional) Suggests organic or chemical treatment approaches

---

## 🔍 Features

- 🖼 Upload potato leaf images and detect disease type
- ✅ Real-time AI predictions with high accuracy
- 📊 Confidence scores shown for transparency
- 💡 (Optional) Treatment recommendation module
- 🌐 Web interface using React and Flask backend
- 🧠 Model trained on TensorFlow 2.5, compatible with 2.16+

---

## 🚀 Live Demo

> Coming Soon — stay tuned!

Or run it locally by following the steps below.

---

## 🧠 Model Details

- **Architecture**: Custom CNN with dropout and batch normalization
- **Trained on**: PlantVillage Dataset (Potato class)
- **Classes**: 
  - Early Blight
  - Late Blight
  - Healthy
- **Accuracy**: ~96.8%
- **Framework**: TensorFlow 2.5 (compatible with 2.16+)

---

## 🛠️ Tech Stack

| Frontend       | Backend     | AI Model        | Deployment    |
|----------------|-------------|------------------|----------------|
| React.js       | Flask       | TensorFlow 2.5   | Netlify (FE) + Render (BE) |
| Material UI    | REST APIs   | Keras            | GitHub Actions (CI/CD)    |

---

## ⚙️ Installation

### 🔹 1. Clone the repository
```bash
git clone https://github.com/your-username/potato-leaf-disease-detection.git
cd potato-leaf-disease-detection

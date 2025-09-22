# 🌿 Plant Disease Classification API

A Flask-based web application for predicting **plant leaf diseases** using a trained deep learning model.  
Users can upload a leaf image through a simple **HTML frontend**, and the backend model will classify it as:

- **Early Blight**
- **Late Blight**
- **Healthy**

---

## 🚀 Features
- Flask API with `/predict` endpoint.
- HTML UI (Bootstrap) for uploading images and viewing results.
- Image preview before upload.
- Returns predicted class and confidence score.
- Cross-origin support for frontend integration.

---

## 📂 Project Structure
final/
│── main.py # Flask app
│── templates/
│ └── index.html # Frontend UI
│── saved_models/ # Trained model folder or file
│── README.md # Project documentation


---

## ⚙️ Setup & Installation

1. **Clone the repository**

   git clone https://github.com/Yash-Kesharwani1/potatodiseaseclassification.git
   cd plant-disease-classifier/final

2. **Create and activate virtual environment**
    python -m venv .venv
    source .venv/bin/activate   # Linux/Mac
    .venv\Scripts\activate      # Windows
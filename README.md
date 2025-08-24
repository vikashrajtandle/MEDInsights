# **MedInsights – Multi-Disease Prediction Web App** 🧠🫁🫀

A **Flask-based web application** that predicts multiple diseases using **Machine Learning (ML)** and **Deep Learning (DL)** models. The app provides quick, AI-driven health insights for early detection of critical illnesses.

---

## ✅ **Features**

* **Multi-Disease Support**:

  * 🦠 COVID-19 Prediction
  * 🧠 Brain Tumor Detection
  * 🧬 Alzheimer Detection
  * 🩸 Diabetes Prediction
  * 🎗 Breast Cancer Prediction
  * 🫁 Pneumonia Detection
  * ❤️ Heart Disease Prediction
* **AI Models**: Trained using TensorFlow, Scikit-learn, and Joblib.
* **Image & Tabular Input**: Upload medical images or enter patient details.
* **Simple UI**: Easy-to-use web interface built with **Flask** and **HTML/CSS**.

---

## 🛠 **Tech Stack**

* **Frontend**: HTML, CSS
* **Backend**: Flask (Python)
* **ML/DL Libraries**:

  * TensorFlow/Keras
  * Scikit-learn
  * Joblib, Pickle
* **Image Processing**: OpenCV, Imutils
* **Deployment**: Localhost (Flask)

---

## 📂 **Project Structure**

```
MedInsights/
│
├── app.py                # Main Flask application
├── requirements.txt       # Project dependencies
├── templates/            # HTML templates
│   ├── homepage.html
│   ├── covid.html
│   ├── braintumor.html
│   ├── diabetes.html
│   ├── alzheimer.html
│   ├── pneumonia.html
│   ├── heartdisease.html
│   ├── resultc.html
│   └── ...
├── static/
│   └── uploads/          # Uploaded images
└── models/               # Trained ML/DL models
    ├── covid.h5
    ├── braintumor.h5
    ├── alzheimer_model.h5
    ├── diabetes.sav
    ├── heart_disease.pickle.dat
    ├── pneumonia_model.h5
    └── cancer_model.pkl
```

---

## 🚀 **How to Run Locally**

### 1️⃣ **Clone the Repository**

```bash
git clone https://github.com/your-username/MedInsights.git
cd MedInsights
```

### 2️⃣ **Create Virtual Environment**

```bash
python -m venv venv
source venv/bin/activate   # For Linux/Mac
venv\Scripts\activate      # For Windows
```

### 3️⃣ **Install Dependencies**

```bash
pip install -r requirements.txt
```

### 4️⃣ **Add Model Files**

Due to GitHub's file size limit, models are not included.
➡ **[Download Models from Google Drive](YOUR_MODEL_LINK_HERE)** and place them in the `models` folder.

### 5️⃣ **Run the App**

```bash
python app.py
```

Open in browser:

```
http://127.0.0.1:5000
```

---

## ✅ **requirements.txt**

```
Flask==3.0.3
tensorflow==2.20.0
opencv-python==4.10.0.84
imutils==0.5.4
scikit-learn==1.5.2
joblib==1.4.2
numpy==1.26.4
```

---


## ⚠ **Note**

* This app is for **educational purposes only** and should not be used for actual medical diagnosis.
* Large model files are hosted externally due to GitHub size limitations.

---


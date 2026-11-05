# 🔍 Live Camera Object Detection

A browser-based real-time object detection application that uses TensorFlow.js and the pre-trained COCO-SSD model to identify objects through a webcam.

<p align="center">
  <a href="https://yolov8-object-detection-9gk7.onrender.com/">
    <strong>🚀 View Live Demo</strong>
  </a>
</p>

## 🌐 Live Application

**Website:** https://yolov8-object-detection-9gk7.onrender.com/

**GitHub Repository:** https://github.com/jsivaramateja1-del/YOLOv8-Object-Detection

## ✨ Features

* Real-time object detection using a webcam.
* Browser-based machine learning inference.
* TensorFlow.js integration.
* Pre-trained COCO-SSD object detection model.
* Live camera preview.
* Object identification and detection visualization.
* No server-side GPU required.
* Responsive web interface.

## 🛠️ Technologies Used

| Technology    | Purpose                            |
| ------------- | ---------------------------------- |
| HTML5         | Webpage structure                  |
| CSS3          | Styling and interface              |
| JavaScript    | Application functionality          |
| TensorFlow.js | Browser-based machine learning     |
| COCO-SSD      | Pre-trained object detection model |
| Python        | Backend application                |
| FastAPI       | Web server and static file serving |
| Uvicorn       | ASGI server                        |
| Render        | Application deployment             |

## 📁 Project Structure

```text
YOLOv8-Object-Detection/
│
├── app.py
├── index.html
├── requirements.txt
├── render.yaml
├── README.md
│
├── css/
│   └── styles.css
│
└── js/
    └── script.js
```

## 🚀 Run Locally

### 1. Clone the repository

```bash
git clone https://github.com/jsivaramateja1-del/YOLOv8-Object-Detection.git
```

### 2. Navigate into the project

```bash
cd YOLOv8-Object-Detection
```

### 3. Create a virtual environment

```bash
python -m venv venv
```

Activate it on Windows:

```bash
venv\Scripts\activate
```

### 4. Install dependencies

```bash
pip install -r requirements.txt
```

### 5. Start the application

```bash
uvicorn app:app --reload
```

### 6. Open in your browser

```text
http://127.0.0.1:8000
```

Allow camera access when prompted.

## ☁️ Deployment

This application is deployed using Render.

**Build Command:**

```bash
pip install -r requirements.txt
```

**Start Command:**

```bash
uvicorn app:app --host 0.0.0.0 --port $PORT
```

**Health Check Endpoint:**

```text
/health
```

## 🧠 How It Works

1. The user opens the web application.
2. The browser requests webcam permission.
3. JavaScript accesses the camera stream.
4. TensorFlow.js loads the COCO-SSD model.
5. Video frames are processed directly in the browser.
6. Detected objects are identified and visualized.

**Note:** Object detection inference happens in the browser, not on the Python backend.

## ⚠️ Requirements

* Modern web browser.
* Webcam or camera-enabled device.
* Internet connection for loading the TensorFlow.js libraries and model.
* Camera permission enabled.
* Python 3.10 or compatible version for local backend execution.

## 📌 Important Information

Despite the repository name, the currently deployed implementation uses TensorFlow.js with COCO-SSD rather than running the Ultralytics YOLOv8 model on the server.

## 👨‍💻 Author

**Siva Rama Teja**

GitHub: https://github.com/jsivaramateja1-del

---

⭐ If you find this project useful, consider giving the repository a star!

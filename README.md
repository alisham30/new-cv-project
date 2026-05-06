🔍 Crime Detection System

This project is a real-time **Crime Detection System** using **Deep Learning** and **Computer Vision**. It helps monitor both **live CCTV feeds** and **recorded videos**, detect suspicious or criminal activities, and trigger alerts (including alarms) in real-time.

---

## 🚀 Features

- 🎥 **Live CCTV Stream Analysis**  
  Analyze live footage by entering a CCTV stream URL.

- 📼 **Recorded Video Detection**  
  Upload and analyze recorded videos for crime detection.

- 🧠 **Deep Learning Based Detection**  
  Uses a pre-trained deep learning model to classify frames as *crime* or *non-crime*.

- 🔔 **Alarm System**  
  Triggers an alarm and displays "Crime Detected" when a crime is identified.

- ✅ **Frontend Interface**  
  A user-friendly, professional UI to interact with the system.

---

## 🛠️ Tech Stack

- **Backend**: Python, Flask  
- **Frontend**: HTML, CSS, JavaScript  
- **Model**: CNN-based crime detection model  
- **Others**: OpenCV, NumPy, TensorFlow/PyTorch, etc.

---

## 📂 Folder Structure

```
Crime-Detection-System/
│
├── static/             # Static files (CSS, JS)
├── templates/          # HTML templates
├── uploads/            # Uploaded videos
├── app.py              # Main Flask application
├── model/              # Trained deep learning model
└── requirements.txt    # Python dependencies
```

---

## 📦 Installation

### 1. Clone the Repository

```bash
git clone https://github.com/MuthamizhSelvan01/Crime-Detection-System.git
cd Crime-Detection-System
```

### 2. Create a Virtual Environment (Optional but recommended)

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

---

## ⚙️ Usage

### Start the Flask App

```bash
python app.py
```

### Open in Browser

Visit: [http://localhost:5000](http://localhost:5000)

---

## 🧪 How It Works

1. Choose either **Live CCTV** or **Recorded Footage** on the homepage.
2. If "Live CCTV" is selected:
   - Enter a valid CCTV stream URL (e.g., EarthCam).
   - The system will analyze the stream in real-time.
3. If "Recorded Footage" is selected:
   - Upload a video file.
   - The system will scan the full video before providing a result.
4. The result will either show **"Crime Detected"** with an alarm or **"No Crime Yet"**.

---

## 📸 Example

- Input: Live CCTV from a public place or a test video file.
- Output: "Crime Detected" or "No Crime Yet", with sound alarm if crime is detected.

---

## 🧠 Model Details

- Type: CNN-based custom classifier
- Input: Video frames (preprocessed with OpenCV)
- Output: Binary classification — Crime / No Crime

> 🔐 The model is trained using annotated surveillance footage with crime labels.

---

## 🛡️ Disclaimer

This system is a prototype and should **not be used in production** or for legal evidence. Always verify results with human supervision.

---

## 📌 To-Do

- [ ] Improve model accuracy with a larger dataset  
- [ ] Add crime type classification (e.g., theft, assault)  
- [ ] Enhance UI/UX with animations and mobile responsiveness  
- [ ] Add database to store history of detections  

---
---

Let me know if you'd like me to generate a `requirements.txt` as well or tailor the README further for deployment on platforms like Heroku or Render.

# 🧠 Multimodal Depression Detection System

An intelligent, privacy-conscious system designed to detect signs of **depression** through multiple input types — combining **image, audio, video, text, and questionnaire analysis**. All models used in this project are **custom-trained**, making it suitable for offline use and further development.

---

## 🎯 Objective

To provide an early indication of depressive symptoms by analyzing a user’s behavior across multiple modalities, combining them into a final depression severity score using ensemble techniques.

---

## 💡 Modalities Used

| Modality        | Input Type         | Analysis Method                         |
|-----------------|--------------------|------------------------------------------|
| 🖼️ Image         | Facial Expression  | CNN model to infer depressive cues       |
| 🎤 Audio         | Voice Recording    | Custom-trained audio feature extractor   |
| 🎥 Video         | Webcam Feed        | Combined audio-visual depression signals |
| ✍️ Text          | Free-Text Input    | NLP-based depression keyword detection   |
| 📋 Questionnaire | MCQ + Open-ended   | PHQ-inspired weighted scoring            |

---

## ⚙️ Tech Stack

### 🔙 Backend
- Python (Flask)
- TensorFlow / Keras
- scikit-learn
- OpenCV
- librosa

### 🖥️ Frontend
- React.js
- Axios (for API communication)
- Chart.js (graphical results)
- Tailwind CSS / plain CSS

---

## 🧠 Modalities
- **Image Analysis** (Facial expressions)
- **Audio Analysis** (Speech tone)
- **Video Analysis** (Facial + voice combined)
- **Text Analysis** (Free-text response)
- **Questionnaire** (MCQ and open-ended)

## ⚙️ Tech Stack
- **Frontend**: React.js
- **Backend**: Python (Flask)
- **ML Models**: Pre-trained models adapted for depression detection

## 🛠 How to Run

### Backend
```bash
cd backend
pip install -r requirements.txt
python app.py


Frontend

cd frontend
npm install
npm start

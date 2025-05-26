# Car Damage Detection using YOLOv8, OpenCV, FastAPI, and React

This project detects car damages using a trained YOLOv8 model and serves results via a FastAPI backend and a React frontend.

## 🚀 Technologies Used
- YOLOv8 (Ultralytics)
- OpenCV (image processing & inference)
- FastAPI (backend API)
- React.js (frontend interface)
- ONNX (model format)

## 📁 Project Structure

- `/backend`: FastAPI backend with ONNX model inference.
- `/frontend`: React.js frontend for image upload and result display.
- `/data`: Images and sample datasets.

## 🛠️ Setup

### Backend

```bash
cd backend
python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows
pip install -r requirements.txt
uvicorn main:app --reload

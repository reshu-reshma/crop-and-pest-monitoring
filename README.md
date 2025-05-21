# crop-and-pest-monitoring
# Crop and Pest Detection System

This project detects crop types and identifies pests using deep learning and computer vision. It includes real-time video analysis and a FastAPI-based backend for integration with other systems.

---

## Features

-  Crop and pest recognition using trained TensorFlow models
-  Real-time detection via webcam or video input
-  Lightweight FastAPI server for deploying the model as an API
- 🛠 Easy to set up and extend for future enhancements

---

##  Installation

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/crop-pest-detection.git
cd crop-pest-detection
# crop-and-pest-detection

2. Create a Virtual Environment
python -m venv temo

3. Activate the Environment (Windows)
temo\Scripts\activate

4. Install Required Libraries
pip install fastapi uvicorn opencv-python numpy tensorflow

▶️ How to Run
🖥️ Real-time Video Detection
python vidnew.py

🌐 Run the Web API using FastAPI

uvicorn fast:app --reload

Project Structure
crop-pest-detection/
│
├── fast.py             # FastAPI server script
├── vidnew.py           # Real-time video detection script
├── model/              # Directory for trained models
├── utils/              # Utility functions (optional)
├── README.md           # Project documentation
└── requirements.txt    # (optional) For dependency management

Libraries Used
FastAPI – for building the web API

Uvicorn – ASGI server for FastAPI

OpenCV – for handling video and image data

NumPy – numerical processing

TensorFlow – deep learning framework for model training and inference

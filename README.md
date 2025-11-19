DeepGynScan – AI-Powered Cervical Cancer Detection using CNN

DeepGynScan is an intelligent healthcare application designed to assist in the early detection of cervical cancer using Convolutional Neural Networks (CNN).
It aims to support healthcare professionals by providing fast, reliable, and AI-based screening insights from cervix images.

🔍 Overview

Cervical cancer is one of the most preventable cancers when detected early. DeepGynScan leverages deep learning to analyze cervical images and classify them into normal or abnormal categories.
The system includes:

🧠 AI Model (CNN-based image classification)

🌐 Frontend Web Application (User-friendly interface for uploading images & viewing results)

⚙️ Backend API (Processes images, runs AI model, and returns predictions)

🧠 Key Features

AI-powered cervical cancer detection using CNN

High accuracy predictions based on labeled medical datasets

Real-time image uploading and analysis

Secure backend handling

Clean and simple UI for healthcare workers

Modular architecture (frontend + backend)

📁 Project Structure
HealthcareProject/
   ├── frontend/      # React-based or web-based UI
   └── backend/       # Python/Node backend + CNN model

🏗️ Tech Stack
Frontend

React / HTML / CSS / JavaScript

Axios for API calls

User-friendly interface

Backend

Python (Flask / FastAPI / Django) [Use whichever you implemented]

TensorFlow / Keras for CNN model

Image preprocessing pipeline

REST API for prediction

AI Model

Convolutional Neural Network

Trained on cervical cancer image dataset

Multi-class or binary classification

🚀 How It Works

User uploads a cervical image through the frontend.

Image is sent to backend API.

Backend preprocesses the image (resize, normalize, etc.).

CNN model performs inference.

The result (Normal / Precancerous / Cancerous) is returned to the UI.

User receives interpretation and risk assessment.

⚙️ Setup Instructions
1. Clone the Repository
git clone https://github.com/Nivas2004/HealthcareProject.git
cd HealthcareProject

2. Frontend Setup
cd frontend
npm install
npm start

3. Backend Setup
cd backend
pip install -r requirements.txt
python app.py

📊 Model Performance

(Add your accuracy, precision, recall once your model is tested.)

Example:

Accuracy: 92%

Recall: 90%

Precision: 88%

🛡️ Disclaimer

DeepGynScan is an AI-assisted tool, not a replacement for professional medical diagnosis.
It should only be used to support clinical decisions by qualified healthcare practitioners.

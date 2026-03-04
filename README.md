🧠 Brain Tumor Detection System

A full-stack web application that detects the presence of brain tumors from MRI images using a deep learning model. The system allows users to upload MRI scans through a web interface and receive an automated prediction indicating whether a tumor is detected.
This project demonstrates the integration of machine learning models with a full-stack web application, enabling real-time medical image analysis through a user-friendly interface.

🚀 Features

Upload MRI brain scan images through a web interface
Deep learning model analyzes the image for tumor detection
Real-time prediction results displayed to the user
REST API for communication between frontend and backend
Clean and responsive UI for easy interaction
Local deployment with full backend and frontend integration

🏗️ System Architecture
User Uploads MRI Image
        │
        ▼
Frontend (React / Web Interface)
        │
        ▼
Backend API (Node.js / Python / Flask)
        │
        ▼
Deep Learning Model (CNN)
        │
        ▼
Prediction Result Returned to UI
🧠 Machine Learning Model

The model is trained on MRI brain scan datasets to classify images into:
-Tumor Detected
-No Tumor Detected

Model Details
Architecture: Convolutional Neural Network (CNN)
Input: Brain MRI image
Output: Binary classification (Tumor / No Tumor)
Framework: TensorFlow / Keras
The model extracts spatial features from MRI scans and predicts tumor presence based on learned patterns.

🛠️ Tech Stack
Frontend
React.js
HTML5
CSS3
JavaScript
Backend
Node.js 
REST API
Machine Learning
Python
TensorFlow / Keras
NumPy
OpenCV

Other Tools
Git & GitHub

Localhost deployment

📂 Project Structure
brain-tumor-detector
│
├── frontend
│   ├── src
│   ├── components
│   └── pages
│
├── backend
│   ├── routes
│   ├── controllers
│   └── server.js
│
├── model
│   ├── tumor_model.h5
│   └── prediction.py
│
├── dataset
│
└── README.md


⚙️ Installation & Setup

1️⃣ Clone the Repository
git clone https://github.com/Pratyushanand1/brain-tumor-detector.git
cd brain-tumor-detector

2️⃣ Backend Setup
cd backend
npm install
npm start

3️⃣ Frontend Setup
cd frontend
npm install
npm start

4️⃣ Run the ML Model Server (if separate)
python app.py

5️⃣ Open in Browser
http://localhost:3000

Upload an MRI image and view the prediction result.

📸 Application Workflow
User uploads an MRI scan image
Image is sent to the backend API
Backend processes the image and sends it to the ML model
Model performs prediction
Result is returned and displayed on the frontend

🔬 Future Improvements

Deploy the application using Docker / AWS / Vercel
Improve model accuracy with larger medical datasets
Add tumor segmentation and localization
Implement user authentication and patient records
Integrate cloud-based inference

⚠️ Disclaimer

This project is developed for educational and research purposes only.
It should not be used for clinical or medical diagnosis without professional medical validation.

👨‍💻 Author

Pratyush Anand

Computer Science Undergraduate
KIIT University

Interested in Software Development, AI/ML, and Full Stack Engineering

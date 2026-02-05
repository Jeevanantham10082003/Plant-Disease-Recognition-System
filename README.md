🌿 Plant Disease Recognition System (Flask + CNN)

A deep learning–based web application that detects plant diseases from leaf images using a Convolutional Neural Network (CNN).
The system predicts the disease and displays its cause and organic cure, with English and Tamil language support.

🚀 Features

🌱 Plant disease detection using leaf images

🧠 CNN model trained on plant disease dataset

📸 Image upload and instant prediction

📋 Displays disease name, cause, and remedy

🌐 Multi-language UI (English 🇬🇧 & Tamil 🇮🇳)

🎨 Responsive UI using Bootstrap

⚡ Flask-based lightweight backend

🧠 Tech Stack

Backend

Python

Flask

TensorFlow / Keras

NumPy

Frontend

HTML5

CSS3

Bootstrap 5

JavaScript

Data

JSON files for disease data and translations

📁 Folder Structure
📦 Plant-Disease-Recognition
├── .vscode/                 # VS Code settings
├── env/                     # Virtual environment
├── models/                  # Trained CNN model
├── static/
│   ├── css/
│   │   ├── bootstrap.min.css
│   │   └── style.css
│   ├── images/              # Background & UI images
│   ├── js/                  # JavaScript files
│   └── lang/
│       ├── en.json          # English UI translations
│       ├── ta.json          # Tamil UI translations
│       └── predictions/
│           └── ta.json      # Tamil disease translations
├── templates/
│   └── home.html            # Main web page
├── test/                    # Testing files (optional)
├── uploadimages/            # Uploaded leaf images
├── app.py                   # Flask application logic
├── plant_disease.json       # Disease causes & cures
└── README.md                # Project documentation

⚙️ Installation & Setup
1️⃣ Clone the Repository
git clone https://github.com/your-username/plant-disease-recognition.git
cd plant-disease-recognition

2️⃣ Create & Activate Virtual Environment (Recommended)
python -m venv env


Windows

env\Scripts\activate


Linux / macOS

source env/bin/activate

3️⃣ Install Required Dependencies
pip install flask tensorflow numpy

▶️ Run the Application
python app.py


Open your browser and go to:

http://127.0.0.1:5000/

🧪 How It Works

User uploads a leaf image

Image is resized and preprocessed

CNN model predicts the disease

Disease details are fetched from plant_disease.json

Output shows:

Disease Name

Cause

Organic Cure

Language can be switched between English & Tamil

🌾 Supported Crops

Apple

Corn

Grape

Potato

Tomato

Pepper

Strawberry

Cherry

Blueberry

Orange

Peach

Soybean

Includes both healthy and diseased classes.

🌍 Multi-Language Support

English 🇬🇧

Tamil 🇮🇳

Language switch is available directly in the UI.

📸 Screenshots

(Add screenshots for better GitHub visibility)

✔ Home Page
<img width="1911" height="1029" alt="Plant Disease Recognition Home page" src="https://github.com/user-attachments/assets/861c4b0b-6a98-4526-bd31-ced560c75f72" />

✔ Image Upload
✔ Disease Detection Result
✔ Tamil Language Output

🔮 Future Enhancements

📊 CNN accuracy & confidence graphs

📱 Mobile application integration

☁️ Cloud deployment (AWS / Firebase)

🧾 PDF disease report generation

🎯 Improved model accuracy

📜 License

This project is licensed under the MIT License.

👤 Author

jo
Electronics & Communication Engineering (ECE)
Interested in AI, Deep Learning & Smart Agriculture

**🌾 Smart Crop Recommendation System**

A Machine Learning powered web application that recommends the most suitable crop to cultivate based on soil nutrients and environmental conditions.

This project demonstrates end-to-end ML workflow including data preprocessing, model training, evaluation, and deployment using Flask.

**🚀 Project Overview**

- Selecting the right crop is critical for maximizing agricultural productivity. This application predicts the most suitable crop based on:

Nitrogen (N), Phosphorus (P), Potassium (K), Temperature, Humidity, pH value, Rainfall

- The system uses supervised machine learning models trained on agricultural data to provide accurate crop recommendations.

**🧠 Machine Learning Workflow**

The project follows a complete ML pipeline:

- Data Cleaning & Preprocessing

- Exploratory Data Analysis (EDA)

- Feature Selection

- Model Training

- Model Evaluation

- Model Serialization (model.pkl)

- Web Application Integration

**🤖 Models Used**

Random Forest Classifier

**📊 Dataset**

The dataset contains agricultural parameters such as soil nutrients and climate conditions mapped to crop labels.

**🖥️ Application Features**

✔ User-friendly web interface

✔ Real-time prediction

✔ Clean and responsive UI

✔ Pre-trained ML model integration

✔ Flask backend

**🏗️ Tech Stack**

**- Frontend:**

HTML

CSS

Backend:

Flask (Python)

**- Machine Learning:**

Scikit-learn

Pandas

NumPy

Matplotlib / Seaborn

**📂 Project Structure**
Crop_prediction/
│
├── app.py
├── model.pkl
├── Crop_recommendation.csv
├── templates/
├── static/
├── requirements.txt
└── README.md

**⚙️ Installation & Setup**
1️⃣ Clone the Repository
git clone https://github.com/MadamPujitha/Crop_prediction.git
cd Crop_prediction

2️⃣ Create Virtual Environment (Optional but Recommended)
python -m venv venv
source venv/bin/activate  # Mac/Linux
venv\Scripts\activate     # Windows

3️⃣ Install Dependencies
pip install -r requirements.txt

4️⃣ Run the Application
python app.py


Open your browser and go to:

http://127.0.0.1:5000/

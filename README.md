# 🍃 Potato Leaf Disease Detection (Flask Web App)

A deep learning-based web application built using Flask and Convolutional Neural Networks (CNNs) to classify potato leaf images into **Early Blight**, **Late Blight**, or **Healthy**.

## 🔍 Project Overview

This project aims to assist farmers and agricultural experts in quickly identifying potato plant diseases through image classification. The user can upload a leaf image via the web interface, and the app will display:
- The **predicted class**
- The **actual class**
- The **confidence level**

## 🧠 Model Details

- The CNN model was trained using a Kaggle dataset containing images of diseased and healthy potato leaves.
- Achieved high accuracy on validation and test sets.
- Saved the trained model as `model.h5`.

## 🛠️ Technologies Used

- **Frontend**: HTML, CSS (simple Flask template)
- **Backend**: Python, Flask
- **Modeling**: TensorFlow, Keras, NumPy, Matplotlib
- **Deployment**: Flask (local or production using services like Heroku/Render)

## 📁 Project Structure

project/
│
├── static/
│ └── style.css # Optional CSS styling
├── templates/
│ └── index.html # Frontend HTML page
│
├── model.h5 # Trained CNN model
├── app.py # Flask application
├── predict.py # Helper prediction function
├── requirements.txt # Python dependencies
└── README.md # Project documentation


# 1. Clone the repository
git clone https://github.com/ShivangGit123/Potato_Leaf_Disease.git
cd Potato_Leaf_Disease

# 2. Create and activate a virtual environment
python -m venv venv
# On macOS/Linux
source venv/bin/activate
# On Windows
venv\Scripts\activate

# 3. Install the dependencies
pip install -r requirements.txt

# 4. Run the Flask app
python app.py

# 5. Open your browser
http://127.0.0.1:5000/

🖼️ Sample Screenshots
<img width="946" height="864" alt="Screenshot 2025-07-29 124441" src="https://github.com/user-attachments/assets/3d8763da-3a84-4766-83f3-f1cce2494de8" />



🧪 Dataset
Dataset used: Potato Leaf Disease Dataset from Kaggle

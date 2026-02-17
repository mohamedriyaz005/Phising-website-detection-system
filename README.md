# 🛡️ Phishing Website Detection System

A **production-grade phishing website detection system** built using **Django**, **Machine Learning**, and **MongoDB**.  
The system analyzes URL-based features and predicts whether a website is **legitimate** or **malicious** using a trained **Random Forest model** with up to **95% accuracy**.

---

## 🛠️ Tech Stack

- **Python 3.10+**  
- **Django REST Framework**  
- **Scikit-learn**  
- **MongoDB**  
- **HTML / CSS / JavaScript**  

---

## 🤖 Machine Learning Model

- **Algorithm:** Random Forest Classifier  
- **Accuracy:** 94–97% (depending on dataset)  
- **Training Dataset:** Phishing Websites Dataset (UCI / Kaggle)  

---

## 🔑 Features

- 🔍 Real-time URL scanning  
- 🧠 Machine learning-based classification  
- 💾 MongoDB scan history storage  
- 🌐 REST API architecture  
- 🏗️ Clean modular backend structure  
- 🚀 Deployment on AWS / Azure  

## ⚡ How to Run

1. **Install Dependencies**  
```bash
pip install -r requirements.txt
✅ After installing dependencies, you can continue in the same terminal. No need to exit.

Train the Model

python training/train_model.py
✅ After training, the model will be saved. Keep the terminal open for running the server.

Run the Server

python manage.py runserver
⚠️ Keep this terminal open while the server is running.
The server logs and API requests will display here.

Open Frontend
Open index.html in your browser.

🔹 This step is done in your browser, no Bash commands needed.

API Endpoint

POST /api/predict/
🔹 You can use tools like Postman or curl to test this endpoint.

Closing Bash / Terminal

Once you’re done with all tasks (server stopped, testing completed):

exit
Or press Ctrl + D to safely close the terminal.


---

### ✅ Key Notes:

- **Do NOT exit Bash after installing dependencies**—you need the same terminal to train the model and run the server.  
- **Keep the server running in Bash** while testing the frontend or API.  
- **Exit only at the very end**, when all tasks are complete.  

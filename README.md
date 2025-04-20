# 🌱 EcoCheck – Carbon Footprint Tracker

EcoCheck is a full-stack web application that allows users to monitor and reduce their carbon footprint by submitting daily or monthly routine inputs. It predicts the user's carbon footprint using machine learning, provides real-time feedback, and even integrates an AI-powered chatbot offering personalized green lifestyle tips.

---

## 📌 Features

- 🔍 **Carbon Footprint Prediction** using a trained XGBoost ML model
- 🧾 **Form-based UI** for daily/monthly user inputs (transportation, energy usage, diet, etc.)
- 📊 **Real-time Feedback** based on user data
- 🤖 **AI Chatbot** (powered by LangChain + Ollama) for eco-friendly lifestyle suggestions
- 💾 **User Authentication** and personalized data storage
- 🔁 **Dynamic UI Updates** with error handling
- 🌐 **RESTful API** using FastAPI for communication between frontend and backend

---

## 🛠️ Tech Stack

### 🎨 Frontend:
- **HTML, CSS, JavaScript** – For building and styling the web interface
- **Form-based UI** – To capture daily/monthly inputs
- **JavaScript DOM Manipulation** – For real-time interactivity
- **Fetch API** – For sending/receiving data from backend
- **Error Handling** – For dynamic user feedback

### ⚙️ Backend:
- **MERN Stack (MongoDB, Express, React, Node.js)** – For scalable and modular backend
- **FastAPI** – Core backend framework (used with Python)
- **Python** – For logic and ML integration
- **XGBoost** – Machine Learning model for carbon footprint prediction
- **LangChain + Ollama** – Natural Language AI chatbot integration
- **Pydantic** – Data validation layer
- **MongoDB with Mongoose** – For user data, submissions, and authentication
- **Encoders** – Preprocessing and transforming input data for ML

---

## ⚙️ How It Works

1. **User signs up/logs in** to the platform.
2. They fill out a **form** about their daily or monthly activities (e.g., transport, energy, food).
3. Submitted data is **validated and preprocessed**.
4. The backend sends it to the **XGBoost model**, which returns a carbon footprint estimate.
5. The user receives **real-time feedback** with tips to reduce their footprint.
6. They can also interact with a **chatbot** for personalized eco-advice.

---

## 🔮 Future Enhancements
-  Mobile App Integration
-  Carbon Tracker Map for regional comparison
-  Carbon History Timeline to visualize progress
-  Fine-tuned Chatbot with more personalized responses
-  Gamification – badges & achievements for greener habits
-  OAuth Integration for secure logins

---

## 🚀 Getting Started

### 1. Clone the Repo
```bash
git clone 
cd ecocheck



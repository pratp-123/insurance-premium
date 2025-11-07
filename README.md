# 🧾 Insurance Premium Prediction

This project is a **machine learning-based web application** that predicts the medical insurance premium category based on various user inputs related to health, lifestyle, and personal profile.

It features a backend powered by **FastAPI**, a frontend built with **Streamlit**, and is containerized using **Docker** for easy deployment.

### 🌐 Live Demo

👉 [Click to Try the App](https://insurance-premium-vt5ywi9jizbgreedxca4g5.streamlit.app/)
👉 [Click to Try the Api](https://insurance-premium-ht6v.onrender.com/)
```
/predict # Hit this https://insurance-premium-ht6v.onrender.com/predict for prediction
```
---

### You can pull Docker image from 
👉 docker pull 
```
docker pull prateekx/insurance-premium
```


## 📌 Project Overview

The application allows users to input personal and health details, which are processed by a FastAPI backend to predict the insurance premium category. The prediction is made using a trained machine learning model.

---

## 🧠 Input Features

- **Age** – User's age in years  
- **Weight (kg)** – Body weight  
- **Height (m)** – Height in meters  
- **Annual Income (LPA)** – Income in lakhs per annum  
- **Smoker Status** – Whether the person smokes (True/False)  
- **City** – City of residence (e.g., Mumbai)  
- **Occupation** – Current job status (e.g., retired)


---



## 📦 Clone and Run Locally

```bash
git clone https://github.com/pratp-123/insurance-premium-prediction.git

# Navigate into the project folder
cd insurance-premium-prediction
## Directory Structure
```
## Creating environment
```
# create env on window
python -m venv venv

#activate env
venv\Scripts\activate
```
```
# create env on mac
python3 -m venv venv
#activate env
source venv/bin/activate
```

## Install Dependencies
```
pip install -r requirements.txt
```

## Run code
⚙️ Run the FastAPI Backend

Navigate to the project root (where main.py is located).
Run the API with Uvicorn:
```bash
uvicorn main:app --reload
```

Open your browser and check:
API Root: http://127.0.0.1:8000
Docs (Swagger UI): http://127.0.0.1:8000/docs

## Directory Structure
```
Directory structure:
└── pratp-123-insurance-premium/
    ├── README.md
    ├── app.py
    ├── Dockerfile
    ├── frontend.py
    ├── requirements.txt
    ├── config/
    │   └── city_tier.py
    ├── model/
    │   └── predict.py
    └── schema/
        ├── prediction_response.py
        └── user_input.py
```
## 🛠️ Technologies Used

- **Frontend**: Streamlit  
- **Backend**: FastAPI  
- **Machine Learning**: Scikit-learn  
- **Containerization**: Docker

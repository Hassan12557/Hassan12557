<h1 align="center">Hi, I'm Muhammad Hassan Raza</h1>

<p align="center">
  <b>Data Scientist | Machine Learning Engineer | Full-Stack ML Deployment</b><br>
  Building ML systems that go from raw data to live, containerised cloud applications.
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/muhammad-hassan-raza-999553262/"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:muhammadhassanrazabscs@gmail.com"><img src="https://img.shields.io/badge/Email-Contact%20Me-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
  <a href="https://github.com/Hassan12557"><img src="https://img.shields.io/badge/GitHub-Hassan12557-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"></a>
</p>

---

## About Me

- BSc Computer Science student at **Sukkur IBA University** (Aug 2021 - Dec 2025), based in Sukkur, Pakistan.
- I focus on **predictive modelling, ML pipelines, and full-stack deployment**.
- I do not stop at notebooks. I ship models as **REST APIs**, wrap them in **Docker**, and deploy them to the **cloud**.
- I care about **model judgment**, not just metrics. In my churn project I rejected a 0.99 AUC model after finding data leakage.
- Currently learning: ### Currently Learning and Upskilling
- Model Monitoring and MLOps
- Explainable AI (SHAP)
- Generative AI and Large Language Models (LLMs)
- Natural Language Processing (NLP)
- AI Agents and AI Engineering
---

## Tech Stack

### Languages
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)

### Machine Learning and Data Science
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-337AB7?style=flat-square)
![Joblib](https://img.shields.io/badge/Joblib-ML%20Pipelines-555555?style=flat-square)

Random Forest, Logistic Regression, SMOTE, PCA, Feature Engineering, Threshold Optimisation, Class Imbalance Handling, Model Evaluation (AUC-ROC, PR-AUC, MAE, R-squared)

### Deep Learning
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![Vision Transformers](https://img.shields.io/badge/Vision%20Transformers-ViT-8A2BE2?style=flat-square)

### Backend and APIs
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=flat-square&logo=sqlalchemy&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![Pydantic](https://img.shields.io/badge/Pydantic-E92063?style=flat-square&logo=pydantic&logoColor=white)

REST APIs, Swagger / OpenAPI, Async Programming (Python), BackgroundTasks, bcrypt Password Hashing, Session Management, OTP Email Verification

### Frontend
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![Axios](https://img.shields.io/badge/Axios-5A29E4?style=flat-square&logo=axios&logoColor=white)

### DevOps and Cloud
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Docker Compose](https://img.shields.io/badge/Docker%20Compose-2496ED?style=flat-square&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub Codespaces](https://img.shields.io/badge/GitHub%20Codespaces-181717?style=flat-square&logo=github&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging%20Face%20Spaces-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![Back4app](https://img.shields.io/badge/Back4app%20Containers-4285F4?style=flat-square)
![Streamlit Cloud](https://img.shields.io/badge/Streamlit%20Community%20Cloud-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)

CI/CD (Git-to-cloud pipelines), Multi-Stage Dockerfiles, Environment Variable Handling

### Analytics and Tools
![Excel](https://img.shields.io/badge/Excel-217346?style=flat-square&logo=microsoftexcel&logoColor=white)
![Power Query](https://img.shields.io/badge/Power%20Query-F2C811?style=flat-square&logo=powerbi&logoColor=black)

---

## Featured Projects

### 1. Bank Customer Churn Prediction - Production ML Model
**Stack:** Python, Scikit-learn, Pandas, Logistic Regression, SMOTE, REST API

A full churn prediction pipeline with a business implementation plan for a bank.

- Chose **Logistic Regression (L2)** over XGBoost and Random Forest after finding that their **0.99 AUC came from data leakage**. A credible, explainable model beats an inflated one.
- Moved the decision threshold from **0.50 to 0.15** to reach about **70% churn recall**, because a missed churner costs far more than a retention call.
- Designed a 2-phase retention programme: **Phase 1** (68 customers) gives **$6,100 net gain**, and **Phase 2** (273 customers) projects **$23,850 net quarterly profit** at $50 per intervention.
- Segmented customers into **5 behavioural risk tiers**. Low-income males (35.5% churn rate) and ages 50-60 (23.3%) were priority targets.
- Planned production use: monthly scoring, **PSI drift monitoring**, and a 12-month KPI framework.

---

### 2. EngageIQ - Predictive Workforce Analytics Platform
**Stack:** Python, Django, Scikit-learn, Pandas, NumPy, Docker, Git, Back4app Cloud

A full-stack platform that forecasts employee job satisfaction from workplace metrics.

- Built a **Random Forest Regressor** to predict job satisfaction indexes.
- Built a **Django REST API** that turns JSON payloads into Pandas DataFrames for real-time inference.
- Wrote a **multi-stage Dockerfile** to remove differences between local and cloud environments.
- Cut runtime memory by **50%** (disabled the Django auto-reloader with `--noreload` and optimised image layers) to fit a **256 MB RAM limit** and stop Out-of-Memory crashes.
- Set up a **Git-to-cloud CI/CD pipeline** on Back4app Containers. Every push to master rebuilds and updates the app.

---

### 3. CustomerPredictor - Customer Segmentation and Prediction Platform
**Stack:** Python 3.11, FastAPI, SQLAlchemy, SQLite, React, Vite, Tailwind CSS, Axios, Docker, Docker Compose

A containerised full-stack ML app that predicts customer personas from engagement, spend and satisfaction data.

- **Frontend:** React + Vite + Tailwind CSS, with Axios interceptors for session and API handling.
- **Backend:** FastAPI REST API with SQLAlchemy and SQLite persistence.
- **Security:** bcrypt password hashing, session management and **asynchronous OTP email verification**.
- **Docker Compose** orchestration with `node:20-slim` and `python:3.11-slim` containers.
- Configured **Vite proxies** to route `/api` traffic to the backend container, fixing cross-origin and gateway blocks in GitHub Codespaces.
- Moved SMTP email sending to FastAPI **BackgroundTasks**, which removed request hangs and **504 gateway timeouts**.

---

### 4. End-to-End Property Valuation Platform
**Stack:** Python, Scikit-learn, Random Forest, Streamlit, Docker, Hugging Face Spaces, Git

- Cleaned the dataset and handled outliers with **percentile capping**.
- Trained a **Random Forest Regressor**: validation **R-squared 0.892** and **MAE $18,950**.
- Built a **Streamlit** interface for real-time inputs (square footage, rooms, location) with millisecond-level inference.
- **Dockerised** the app and deployed it live on **Hugging Face Spaces**.

---

### 5. Real Estate Property Rating Predictor
**Stack:** Python, FastAPI, Pydantic, Scikit-learn, Joblib, Streamlit, Docker, Back4app, Streamlit Community Cloud

- Built a Scikit-learn **feature transformation pipeline** and saved model artifacts with **Joblib**.
- Served predictions through a **FastAPI microservice** with **Pydantic validation** and interactive **Swagger docs**.
- Built a **Streamlit dashboard** so non-technical users can change property parameters and see results.
- Wrote production-ready **Dockerfiles** (`$PORT` handling, multi-stage installs, headless execution).
- Used a **decoupled, zero-cost deployment**: API on Back4app Containers, UI on Streamlit Community Cloud.

---

### 6. Melanoma Skin Cancer Detection - Final Year Project
**Stack:** Python, PyTorch, Vision Transformers (ViT), ISIC 2020 Dataset

- Built an AI system with **Vision Transformers** to classify skin lesions from dermoscopic images.
- Trained on the **ISIC 2020 dataset (33,126 high-resolution images)**.
- Built preprocessing pipelines (resizing, normalisation, augmentation) for uniform input and efficient GPU use.
- Used attention mechanisms to support earlier and more interpretable melanoma diagnosis.

---

## Certifications

- Google Data Analytics Professional Certificate (Coursera)
- Google Advanced Data Analytics Certificate (Coursera)
- Google Business Intelligence Certificate (Coursera)
- Google AI Essentials (Coursera)
- Diploma in Data Analytics in Python (Alison)
- Prompt Engineering for AI Applications (Alison)

---

## GitHub Stats

<p align="center">
  <img height="170" src="https://github-readme-stats.vercel.app/api?username=Hassan12557&show_icons=true&hide_border=true&count_private=true" alt="GitHub stats">
  <img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Hassan12557&layout=compact&hide_border=true" alt="Top languages">
</p>

---

## Let's Connect

I'm open to **Data Scientist** and **ML Engineer** roles and collaborations.

- Email: muhammadhassanraza659@gmail.com
- LinkedIn: [muhammad-hassan-raza](https://www.linkedin.com/in/muhammad-hassan-raza-999553262/)

<p align="center"><i>Thanks for visiting. Star a repo if you like it!</i></p>

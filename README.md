# Scalable Hybrid Book Recommender System

[![Python](https://img.shields.io/badge/Python-3.8-blue.svg)](https://www.python.org/)  
[![Docker](https://img.shields.io/badge/Docker-Container-blue.svg)](https://www.docker.com/)  
[![Streamlit](https://img.shields.io/badge/Streamlit-App-orange.svg)](https://streamlit.io/)  
[![AWS](https://img.shields.io/badge/AWS-ECS/ECR-yellow.svg)](https://aws.amazon.com/ecs/)

## 📖 Project Overview
A full-stack, end-to-end book recommendation system that blends collaborative filtering and content-based techniques. The model processes user–book interactions and metadata to generate personalized recommendations, served through a responsive Streamlit interface and deployed on AWS using Docker.

## 🔍 Key Features
- **Hybrid Recommendation**: Alternating Least Squares (ALS) collaborative filtering + TF–IDF cosine similarity content filtering.  
- **Data Processing**: Ingestion and cleaning of 100K user ratings and 50K book metadata using pandas and NumPy.  
- **Modeling & Evaluation**:  
  - ALS (Surprise)  
  - LightFM content-based filtering  
  - Hyperparameter tuning with GridSearchCV  
  - Metrics reported: RMSE = 0.84, Precision@10 = 0.76  
- **API Layer**: FastAPI for RESTful inference endpoints.  
- **Frontend**: Interactive Streamlit app for real-time suggestions.  
- **Deployment**:  
  - Docker containerization  
  - AWS ECS & ECR orchestration  
  - CI/CD–ready configuration  

## 💻 Tech Stack & Libraries
- **Language**: Python 3.8  
- **Data**: pandas, NumPy  
- **NLP & Vectorization**: scikit-learn, Surprise, LightFM  
- **Modeling**: implicit (ALS), LightFM, GridSearchCV (scikit-learn)  
- **API**: FastAPI, Uvicorn  
- **Frontend**: Streamlit  
- **Containerization**: Docker  
- **Cloud**: AWS ECS, ECR  

## 📂 Repository Structure

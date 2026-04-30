# Eleni Michala – Portfolio

MSc Applied Artificial Intelligence @ University of Warwick  
BSc Computer Science @ University of Cyprus

I’m a Computer Science graduate currently pursuing my MSc in Applied AI.  
My work spans machine learning, deep learning, data analysis, backend development, and full-stack web applications.  
I enjoy building practical systems, designing end-to-end pipelines, optimizing performance, and explaining technical concepts clearly.

---

## Tech Stack

- **Languages:** Python, Java, JavaScript, C, C++, SQL
- **Machine Learning / AI:** PyTorch, Scikit-learn, Hugging Face Transformers, CNNs, Transfer Learning, NLP, LLMs
- **Frameworks:** Flask, FastAPI, Spring Boot, Django, Wagtail CMS
- **Frontend:** HTML, CSS, JavaScript, Streamlit, Leaflet.js
- **Databases:** SQLite, PostgreSQL, MSSQL
- **Tools & Platforms:** Docker, Kafka, Git, Linux command line, Jupyter Notebook
- **Specialties:** Machine Learning, Deep Learning, NLP, Full-Stack Web Development, Microservices, Distributed Systems

---

# Featured Projects

## Machine Learning & AI Projects

### Brain Tumor MRI Classification

A deep learning project for classifying brain MRI scans into four categories: glioma, meningioma, pituitary tumour, and no tumour.

The project compares traditional machine learning, a custom CNN, and transfer learning models to evaluate which approach performs best for medical image classification.

**Key Features:**
- HOG + SVM traditional ML baseline
- Custom CNN trained from scratch
- ResNet18 and EfficientNetB0 transfer learning models
- Accuracy, macro F1-score, confusion matrices, and class-level evaluation
- Grad-CAM visualisation for interpretability
- Kaggle API dataset download workflow

**Repository:** https://github.com/Elenimichala55/brain-tumor-mri-classification

---

### Amazon Dataset – Product Review Intelligence Pipeline

A machine learning and LLM-based pipeline for analysing Amazon Electronics reviews and extracting actionable product insights.

This project was developed as part of a group assignment for the WM9B7 Artificial Intelligence & Deep Learning module. The pipeline identifies useful reviews, filters low-value content, extracts product aspects, and generates product-level sentiment summaries.

**Key Features:**
- Streaming EDA and stratified sampling from large-scale Amazon review data
- Helpfulness classification using TF-IDF + Logistic Regression, BiLSTM, and DistilRoBERTa
- LLaMA 3.1 8B aspect extraction with demo-mode fallback
- Product-level sentiment and aspect reporting
- LIME-based model attribution
- Separate deployed frontend for visualising generated insights

**Repository:** https://github.com/Elenimichala55/product-review-intelligence-pipeline  
**Frontend Demo:** https://elenimichala55.github.io/amazon-reviews-dataset-frontend/  
**Frontend Repository:** https://github.com/Elenimichala55/amazon-reviews-dataset-frontend

---

### Diabetes Prediction

A machine learning project for predicting diabetes risk using patient health indicators.

**Key Features:**
- Data preprocessing and exploratory analysis
- Classification model training and evaluation
- Model performance comparison using standard ML metrics
- Clean notebook-based workflow for reproducibility

**Repository:** https://github.com/Elenimichala55/diabetes-prediction

---

### Kohonen Self-Organising Map

A full Python implementation of a Kohonen Self-Organising Map for clustering handwritten English characters.

**Key Features:**
- Custom SOM training and testing pipeline
- Tunable grid size, learning rate, and epochs
- Error visualisation and clustering analysis
- Implemented without relying on high-level SOM libraries

**Repository:** https://github.com/Elenimichala55/kohonen-som

---

## Data & Dashboard Projects

### Public Health Insights Dashboard

A Streamlit-based dashboard for analysing WHO-style public health indicators such as life expectancy and obesity prevalence.

**Key Features:**
- Streamlit interactive dashboard
- SQLite backend for storing and managing records
- Filtering by indicator, country, year, and population group
- Trend analysis and descriptive statistics
- CRUD functionality for managing records
- CSV download support
- Activity logging

**Repository:** https://github.com/Elenimichala55/public-health-dashboard

---

### Weather Dashboard

A responsive dashboard built using vanilla JavaScript, HTML, and CSS.

**Key Features:**
- 5-day weather forecast display
- Temperature, humidity, and pressure charts
- OpenWeather API integration
- Responsive UI and animations
- Search-based city weather lookup

**Repository:** https://github.com/Elenimichala55/weather-dashboard

---

## Backend & Full-Stack Projects

### LMS – Leave Management System

A Spring Boot-based system where employees request leave and managers approve, update, or delete requests.

**Key Features:**
- Role-based authentication for users and managers
- REST API endpoints
- Multi-layer Spring Boot architecture
- Leave request creation, approval, update, and deletion
- Database-backed persistence

**Repository:** https://github.com/Elenimichala55/lms

---

### Payments Microservice

A distributed microservice implementing asynchronous payment processing.

**Key Features:**
- FastAPI backend
- Kafka producer and consumer logic
- PostgreSQL database persistence
- Docker Compose setup
- Event-driven architecture and inter-service communication

**Repository:** https://github.com/Elenimichala55/payments-microservice

---

# Research Project

## MicroGrid Eco-Charging Network — BSc Dissertation

A full-stack system for recommending eco-friendly EV charging routes using microgrid-powered stations, solar production estimates, and spatial-temporal data.

The system is currently deployed on the University of Cyprus Computer Science domain. A related research paper has also been submitted to the **IEEE Mobile Data Management Conference 2026**.

**Key Features:**
- Flask backend with modular API architecture
- Leaflet.js interactive map with routing, microgrid overlays, and charger markers
- SQLite database with microgrid, charger, and solar production data
- Forecast scheduling using cron jobs and OpenWeather integration
- Spatial computation for distances, ETAs, and ranking algorithms
- Frontend filters, charger panels, microgrid cards, and forecast slider

**Live Demo:** https://ecochargeplus.cs.ucy.ac.cy/  
**Demo Video:** https://www.youtube.com/watch?v=CmjFZFbXKDs  
**Repository:** https://github.com/dmsl/ecocharge/tree/main/Ecocharge%2B  
**Related Paper:** Submitted to IEEE Mobile Data Management Conference 2026

# CareCast

# 🩺 Online Health Prediction using Django

This project is a Django-based web platform that uses machine learning models to provide online predictions for health conditions like **mental disorders**, **PCOS**, and **obesity**. It also enables users to download reports and schedule appointments with healthcare professionals.

---

## 🚀 Features

- **🧠 Online Health Predictions**  
  Predict mental disorders, PCOS, and obesity using ML models trained on Kaggle datasets.

- **📄 Health Report Download**  
  Users can download their health prediction reports.

- **📅 Appointment Scheduling**  
  Users can schedule appointments with doctors through the platform.

- **👤 User Registration**  
  Registered users can generate reports and manage appointments.

- **👨‍⚕️ Doctor Registration**  
  Healthcare professionals can register to view and accept appointment requests.

- **📋 Appointment Management**  
  Doctors can manage, accept, or decline user appointment requests.

---

## 🧠 Tech Stack

- **Frontend**: HTML, CSS, Bootstrap  
- **Backend**: Python, Django, SQLite3  
- **Django Version**: 5.0.2  

---

## 📁 Project Structure

Here is the breakdown of the Django project structure:

- **predictHealth (Folder):**  
  This is the main root directory of Django project. It contains manage.py file, which is the primary script for managing this Django application

- **home (Folder):**  
  This is a Django app. Django apps are reusable components that contain models, views, and other logic specific to a particular functionality.

- **static (Folder):**  
  This folder stores static files that are served directly by the web server without being processed by Django. This folder contains:
  - **CSS files**, **Images**
  - **CSV files:** Datasets used for training ML models *(source: Kaggle)*
  - **encoders/**: Encoders for the prediction models
  - **models/**: Pretrained machine learning models for health condition prediction
  - **templates (Folder)/** : This folder contains HTML template files.



---
## 🛠️ Project Setup Guide

Follow the steps below to set up the project on your local machine:

---

### 📁 1. Change the Directory to the Project Folder

```bash
cd <directory to this folder>

pip install -r requirements.txt

pip install <module>

python manage.py makemigrations
python manage.py migrate

python manage.py runserver

Navigate to http://127.0.0.1:8000/ in your browser





DevOps Monitoring Agent

An AI-powered DevOps monitoring system that tracks real-time system metrics and detects anomalies using Machine Learning.

This project combines DevOps + AI + Real-time Monitoring to build an intelligent infrastructure monitoring solution.

📌 Project Overview

This system continuously monitors:

CPU Usage

Memory Usage

Disk Usage

Network Activity

It applies Isolation Forest (Unsupervised ML) to detect abnormal behavior and generates intelligent alerts and recommendations.

The system includes:

Flask backend server

Real-time dashboard

Machine learning–based anomaly detection

Automated alert system

Public deployment using Ngrok

🧠 Key Features

✔ Real-time system metric collection
✔ Isolation Forest anomaly detection
✔ AI-based alert & recommendation engine
✔ Interactive live dashboard
✔ Automatic monitoring loop (2-second refresh)
✔ Public access via Ngrok

🛠 Tech Stack

Python

Flask

Scikit-learn

Isolation Forest

psutil (system metrics)

Ngrok

Jupyter Notebook

📂 Project Structure
AI-DevOps-Monitoring-Agent/
│
├── Devops.ipynb              # Main implementation notebook
├── images/                   # Dashboard screenshots
│   ├── dashboard.png
│   ├── anomaly_detection.png
│   └── alerts.png
├── demo_video.mp4            # Working model demonstration
└── README.md

📊 How It Works
1️⃣ Metric Collection

System metrics are collected using psutil.

2️⃣ Data Processing

Metrics are formatted and prepared for model evaluation.

3️⃣ Anomaly Detection

Isolation Forest identifies abnormal system behavior.

4️⃣ Alert Generation

If anomaly detected → alert + recommendation displayed.

5️⃣ Dashboard Visualization

Flask serves a live dashboard updating every 2 seconds.

🖥 Screenshots
📊 Dashboard View

⚠️ Anomaly Detection

🚨 Alert System

🚀 How to Run Locally

Clone the repository:

git clone https://github.com/your-username/AI-DevOps-Monitoring-Agent.git


Install dependencies:

pip install flask scikit-learn psutil pandas numpy pyngrok


Run the notebook:

jupyter notebook


Execute cells to start monitoring.

🎯 Use Cases

DevOps Infrastructure Monitoring

AI-based System Health Detection

Real-time anomaly tracking

Intelligent alert automation

Educational MLOps project

🔮 Future Improvements

Deploy on cloud (AWS / GCP)

Docker containerization

CI/CD integration

Email/SMS alert integration

Streamlit or React dashboard

Model performance logging

⭐ Why This Project Matters

Traditional DevOps monitoring systems only show metrics.
This system interprets metrics intelligently using AI and detects abnormal patterns automatically.

It demonstrates practical understanding of:

DevOps principles

Monitoring systems

Unsupervised machine learning

Backend + dashboard integration

AI-driven automation


---
👤 Author: Ashish Kumar Nayak  
B.Tech CSE | Data Science | AI & ML  
GitHub: https://github.com/Ashish-nayakk

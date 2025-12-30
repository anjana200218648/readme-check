
# 🛡️ Safe Kid Webapp

> **A comprehensive AI-powered system to detect, monitor, and prevent social media addiction and mental health risks among adolescents aged 10–18.**

---

## 📌 Project Details

- **Project Title:** Safe Kid Webapp  
- **Authors:** 25-26J-251-Students  
- **University:** Sri Lanka Institute of Information Technology (SLIIT)  
- **Supervisor:** Ms. Jenny Krishara  
- **Co-Supervisor:** Ms. Poorna Panduwawala  

---

## 📖 Table of Contents

1. [Introduction](#-introduction)  
2. [Problem Statement](#-problem-statement)  
3. [Objectives](#-objectives)  
4. [System Overview](#-system-overview)  
5. [System Architecture](#-system-architecture)  
6. [Core Modules](#-core-modules)  
7. [Technologies Used](#-technologies-used)  
8. [Installation](#-installation)  
9. [Configuration](#-configuration)  
10. [Running the Application](#-running-the-application)  
11. [Testing](#-testing)  
12. [Use Cases](#-use-cases)  
13. [Security & Privacy](#-security--privacy)  
14. [Limitations](#-limitations)  
15. [Future Enhancements](#-future-enhancements)  
16. [Contributors](#-contributors)  
17. [Support](#-support)  
18. [License](#-license)

---

## 🚀 Introduction

With the rapid increase in social media usage among children and adolescents, digital addiction and mental health concerns have become critical global issues. **Safe Kid Webapp** addresses these challenges by offering an intelligent, secure, and scalable platform that detects risky behavior patterns and enables early intervention.

The system integrates **Artificial Intelligence (AI), Multimodal Analysis, Blockchain, and IoT technologies** to ensure accurate detection, transparency, and continuous monitoring.

---

## ❗ Problem Statement

Adolescents are increasingly exposed to addictive social media content, leading to behavioral changes, mental health issues, and reduced academic performance. Existing solutions lack:
- Real-time detection
- Multimodal analysis
- Secure and transparent decision-making
- Early intervention mechanisms

---

## 🎯 Objectives

- Detect addictive social media content using AI  
- Analyze behavioral patterns using multimodal data  
- Monitor physiological and behavioral indicators in real time  
- Provide explainable, privacy-preserving risk assessments  
- Enable early intervention through alerts and reports  

---

## 🧠 System Overview

Safe Kid Webapp collects and analyzes data from multiple sources including:
- Social media content
- Parent/guardian complaints
- Behavioral and physiological signals

Each data source is processed independently and combined into a final, explainable decision engine.

---

## 🏗️ System Architecture

The system follows a modular, microservice-based architecture:
- AI-powered analysis modules
- Central decision aggregation engine
- Blockchain-based audit logging
- Secure data storage and access control



---

## 🧩 Core Modules

### 1. Addictive Content Analysis (IMPACT Component)

**Description:**  
Analyzes images, captions, and hashtags shared by adolescents to identify addictive patterns.

**Features:**
- Image processing and pattern recognition  
- Caption sentiment analysis  
- Hashtag trend detection  
- Cognitive risk scoring  

**Applications:**
- Early addiction identification  
- Decision support for parents and educators  

---

### 2. Multimodal Complaint-Driven Risk Detection

**Description:**  
Processes complaints submitted by parents and guardians in text or voice format.

**Features:**
- Speech-to-text conversion  
- Behavioral trend analysis  
- Weighted risk scoring  
- Automated reporting and alerts  

---

### 3. Final Decision Behavior Analysis System

**Description:**  
Aggregates results from all modules to produce a reliable and explainable final decision.

**Features:**
- Multi-agent AI reasoning  
- Transformer-based aggregation  
- Conflict-aware analysis  
- Blockchain-secured audit logs  

---

### 4. Smart IoT-Based Behavioral Risk Monitoring System

**Description:**  
Uses IoT sensors to monitor real-time behavioral and physiological signals.

**Features:**
- Facial expression and speech intensity analysis  
- Heart rate, ECG, temperature monitoring  
- Stress and anomaly detection  
- Smart medical card generation  
- SMS alerts  

---

## 🧪 Technologies Used

- **Backend:** Python, Flask  
- **Frontend:** React, Vite  
- **AI/ML:** TensorFlow, OpenCV, NLP  
- **IoT:** Sensors, Microcontrollers  
- **Blockchain:** Distributed Ledger  
- **Database:** Secure Encrypted Storage  

---

## ⚙️ Installation

### 1. Clone Repository

```bash
git clone <YOUR_GIT_URL>
cd <YOUR_PROJECT_NAME>
```

### 2. Backend Setup

```bash
python -m venv venv

# Activate
venv\Scripts\activate        # Windows
source venv/bin/activate     # macOS/Linux

pip install -r requirements.txt
```

### 3. Frontend Setup

```bash
cd frontend
npm install
cd ..
```

---

## ⚙️ Configuration

- Update environment variables in `.env`
- Configure API keys and database credentials
- Ensure IoT devices are properly paired

---

## ▶️ Running the Application

### Backend

```bash
python app.py
```
Runs on: `http://localhost:5000`

### Frontend

```bash
cd frontend
npm run dev
```
Runs on: `http://localhost:5173`

---

## 🧪 Testing

### Backend

```bash
python -m pytest tests/ -v
```

### Frontend

```bash
npm test
npm run build
```

---

## 🎯 Use Cases

- Detecting social media addiction  
- Monitoring mental health risks  
- School counseling systems  
- Hospital pediatric monitoring  
- Parent and guardian supervision  

---

## 🔐 Security & Privacy

- End-to-end data encryption  
- Role-based access control  
- Blockchain-based audit trails  
- Privacy-preserving AI analysis  

---

## ⚠️ Limitations

- Requires stable internet connectivity  
- Accuracy depends on data quality  
- IoT hardware availability  

---

## 🚀 Future Enhancements

- Mobile application support  
- Advanced deep learning models  
- Multi-language support  
- Government and school system integration  

---

## 👥 Contributors

- 25-26J-251-Students  
- SLIIT Faculty of Computing  

---

## 📞 Support

For assistance:
- Check documentation and issues  
- Email: **it22097774@my.sliit.lk**  

---

## 📜 License

This project is developed for **academic and research purposes** under SLIIT.

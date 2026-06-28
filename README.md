# 🚁 SkyGuardAI

AI-powered drone detection and surveillance platform using Python, FastAPI, YOLO, and Leaflet.

---

## 🌟 Overview
SkyGuardAI is an intelligent surveillance system that detects drones in real-time using AI (YOLO object detection) and visualizes detections on an interactive map dashboard.

---

## 🧠 Features
- 🎯 Real-time drone detection using YOLO
- 🌍 Live map tracking using Leaflet
- ⚡ FastAPI backend for AI inference
- 📡 Detection alerts & coordinates logging
- 🖥️ Web-based monitoring dashboard

---

## 🏗️ Tech Stack
- Python
- FastAPI
- YOLO (Computer Vision)
- OpenCV
- Leaflet.js
- HTML/CSS/JavaScript

---

## 📸 Demo
(Add screenshots or GIF here)

---

## ⚙️ How it works
1. Video stream or input is processed
2. YOLO detects drones
3. Backend sends coordinates via FastAPI
4. Frontend displays detections on map

---

## 🚀 Installation

```bash
git clone https://github.com/YOUR_USERNAME/SkyGuardAI.git
cd SkyGuardAI
pip install -r requirements.txt
uvicorn main:app --reload

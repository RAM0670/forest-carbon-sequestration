# forest-carbon-sequestration
Developed a cloud-based AWS system to estimate tree height, crown width, trunk diameter, and carbon stock from a single image using YOLOv8 and MiDaS/ZoE-Depth. Integrated PlanetNet for species classification and enabled access via web and WhatsApp chatbot for real-time forest carbon assessment.

---

## 🧠 Problem Statement
Traditional forest carbon estimation requires expensive equipment and expert surveys. This project provides an accessible AI-based solution using images and cloud services.

---

## ⚙️ System Workflow
1. User uploads a tree image
2. YOLOv8 detects the tree
3. Depth estimation computes height
4. Tree species identified using PlanetNet API
5. Carbon stock calculated
6. Output delivered via web interface and WhatsApp bot

---

## 🛠 Tech Stack
- Python
- YOLOv8
- MiDaS / ZoE-Depth
- PlanetNet API
- AWS S3, Amplify, Lambda
- Docker
- Amazon Lex + Twilio

---

## ☁️ Cloud Deployment
This project is deployed entirely on AWS using managed services.
Live credentials and cloud resources are not included for security reasons.

---

## 🧪 Local Setup (Conceptual)
```bash
pip install -r requirements.txt
python lambda_function.py

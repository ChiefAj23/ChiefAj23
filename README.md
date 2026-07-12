# 👋 Hey, I'm Abhijeet Solanki

**AI Engineer • Edge AI + GenAI • I make models fast on small devices and useful in production**

I like making AI work where it is hardest: on edge devices with tight latency, memory, and power budgets, and in production where demos do not count.

- ⚡ Edge AI: real-time perception on **NVIDIA Jetson** (TensorRT, ONNX Runtime, quantization, pruning)
- 🤖 GenAI: **LLM agents, RAG pipelines, function calling** running in production (Azure OpenAI, LangChain, vLLM)
- 🚗 Autonomous systems: camera + LiDAR perception that stays accurate when the physical world misbehaves
- 🛠 Engineering: Python, C++, C#, FastAPI, React/TS, Docker/Kubernetes, CI/CD

📍 Nashville, TN · open to relocation · **4+ years** across applied ML, backend, and platform work.
💼 Currently: Software Engineer at **Arctera**, shipping GenAI incident tooling on Azure + AKS.

---

## ⚡ TL;DR for recruiters

- **11 peer-reviewed IEEE publications** (5 first-author, including **2 IEEE Access journal articles**) on robust perception and edge AI, with 4 more under review
- Deployed real-time models on **Jetson-class hardware**: 72% → 93% detection accuracy within the same compute budget
- Built and shipped **full-stack AI products** (FastAPI + React + ML on edge and cloud)
- 2× **1st Place Research Awards** (ACM Mid-Southeast, TTU Research Day) + **IEEE-HKN** and **Tau Beta Pi** honors

If you need someone who can **ship code**, **squeeze models onto small hardware**, *and* **read/write papers**, that is literally my lane.

---

## 🔗 Quick Links

[![Portfolio](https://img.shields.io/badge/Portfolio-abhijeetsolanki.com-000?style=flat&logo=google-chrome)](https://www.abhijeetsolanki.com/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Abhijeet%20Solanki-0A66C2?style=flat&logo=linkedin)](https://www.linkedin.com/in/abhijeet-solanki)
[![Email](https://img.shields.io/badge/Email-abhijeet.solanki%40outlook.com-D14836?style=flat&logo=microsoft-outlook&logoColor=white)](mailto:abhijeet.solanki@outlook.com)
[![Medium](https://img.shields.io/badge/Medium-@abhijeet.solanki-000000?style=flat&logo=medium)](https://abhijeet-solanki.medium.com)

---

## 🧩 What I'm building

### 🚘 [VLM Object Detection Baseline on BDD100K](https://github.com/ChiefAj23/bdd100k-vlm-baseline)
How well do vision-language models actually *detect* in driving scenes, with zero fine-tuning? An honest, reproducible mAP benchmark for VLMs (Qwen2.5-VL) on the BDD100K dataset: Dockerized two-service pipeline, preflight checks, full metric breakdowns. Spoiler: zero-shot VLM detection is much weaker than people assume, and now there is a repeatable baseline that proves it.

### 🛑 [Adversarial Patch Removal for Stop Signs](https://github.com/ChiefAj23/qcar-patch-removal)
A printed sticker on a stop sign can make a detector miss it in over half of frames. This generative restoration model removes the patch before detection on our QCar2 physical testbed, raising detection from **48% → 76%** with zero regressions on clean signs. Perception robustness you can bolt onto an existing stack.

### 🔊 [AI Voice Compliance Auditor](https://github.com/ChiefAj23/AI-Voice-Compliance-Auditor)
Full-stack GenAI app (FastAPI + React/TS) that turns raw call recordings into compliance and coaching insights: 0-100 scoring, toxicity and missing-disclosure detection, intent/topic extraction, email/webhook alerts, and **SHAP explainability** so reviewers can see *why* a call was flagged.

### 🛰 Published research code
- [ReAL: LiDAR Reflective Attack Detection](https://github.com/ChiefAj23/ReAL-ReflectiveAttack-Detection-Lidar) (IEEE SoutheastCon 2025)
- [GNAP: Attacking and Defending Facial Detection on Edge Devices](https://github.com/ChiefAj23/GNAPing-On-the-Job) (IEEE SoutheastCon 2025)

---

## 🔬 Research Overview

My research puts deep learning on **resource-constrained edge hardware** and keeps it reliable in the physical world:

- Real-time perception (camera, LiDAR, sensor fusion) under strict latency, memory, and power budgets
- Robustness of edge-deployed models against real-world interference, including laser and adversarial attacks
- Explainable AI (XAI) and uncertainty estimation for trustworthy deployment

> Some submitted papers are not listed due to double-blind review and will appear after acceptance.

---

## 🧪 Research Highlights (Selected)

- **IEEE Access 2026** – *Blinded by the Beam: A Unified Real-Time Defense Against Laser-Based Attacks on Navigational Perception of Autonomous Vehicles*
- **IEEE Access 2025** – *Survey of Navigational Perception Sensors' Security in Autonomous Vehicles*
- **ISVLSI 2024** – *Investigate the Effects of Laser Attack on the Intelligence of the AV Perception*
- **SoutheastCon 2025** – *ReAL: Machine Learning Detection of Reflective Attacks Against Lidarometry*
- **SoutheastCon 2025** – *GNAPing On the Job: Attacking and Defending Facial Detection on Edge Devices*
- **SoutheastCon 2025** – *Towards Machine Learning Based Fingerprinting of Ultrasonic Sensors*
- **ISCAS 2025** – *Mitigation of Camouflaged Adversarial Attacks in Autonomous Vehicles: A Case Study Using CARLA Simulator*
- **MWSCAS 2025** – *Realistic GPS Spoofing Via Customized CARLA GPS Navigation and Controller Systems*
- **IFAC MECC 2025** – *Investigating Adversarial Image Attacks in a Sensor Fusion Framework Using a Scaled Autonomous Vehicle Testbed*
- **FLAIRS 2025** – *Towards Trustworthy AI: Analyzing Model Uncertainty through MC Dropout and Noise Injection*
- **CBMS 2020** – *Protecting Electronic Health Records in Transit and at Rest*

Full list on [Google Scholar](https://scholar.google.com/citations?view_op=search_authors&mauthors=Abhijeet+Solanki) and my [website](https://www.abhijeetsolanki.com/).

---

## 🏆 Achievements & Honors

- 🥇 **2× 1st Place Research Awards** – ACM Mid-Southeast (#1 of 38) and TTU Research & Inquiry Day (#1 of 220)
- 🎓 **IEEE-HKN Honor Society** (Top 10%) · **Tau Beta Pi** Engineering Honor Society
- 📝 Reviewer, **IEEE DCAS 2026**

---

## 🛠 Tech Stack

**ML / AI**
- PyTorch, TensorFlow, ONNX Runtime, TensorRT, CUDA
- Quantization (PTQ/QAT), pruning, edge inference on NVIDIA Jetson (Orin/Nano)
- LLMs: LangChain, Azure OpenAI, vLLM, RAG, function calling, agents
- Computer vision, XAI (Grad-CAM, SHAP), anomaly detection, uncertainty estimation

**Languages & Backend**
- Python, C++, C#
- FastAPI, Flask, .NET, REST APIs, microservices

**Cloud & DevOps**
- Azure (AKS, VMs, networking), Docker, Kubernetes, Helm
- CI/CD (GitHub Actions, Azure DevOps), monitoring, incident automation

---

## ✍️ Selected Writing

- 🧭 **Detecting the Odd One Out: A Guide to One-Class Classification**
  👉 [Read on Medium](https://abhijeet-solanki.medium.com/detecting-the-odd-one-out-a-guide-to-one-class-classification-cf9e22ab9d4a)

---

## 🤝 Let's connect

I'm looking for roles where I can:

- Put **models on edge hardware** and make them fast (inference optimization, TensorRT, quantization)
- Build **GenAI systems** that hold up in production (agents, RAG, evals, guardrails)
- Bridge the gap between **research prototypes** and **shipped products**

If you're hiring or want to compare notes, reach out anytime:

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Abhijeet%20Solanki-0A66C2?style=flat&logo=linkedin)](https://www.linkedin.com/in/abhijeet-solanki)
[![Email](https://img.shields.io/badge/Email-abhijeet.solanki%40outlook.com-D14836?style=flat&logo=microsoft-outlook&logoColor=white)](mailto:abhijeet.solanki@outlook.com)
[![Medium](https://img.shields.io/badge/Medium-@abhijeet.solanki-000000?style=flat&logo=medium)](https://abhijeet-solanki.medium.com)

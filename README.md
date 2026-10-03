<img src="assets/banner.png" alt="Edge AI · GenAI · Production ML" width="100%">

<p align="center">
  <a href="https://www.abhijeetsolanki.com/"><img src="https://img.shields.io/badge/Portfolio-0D1B2A?style=for-the-badge&logo=googlechrome&logoColor=2DD4BF" alt="Portfolio"></a>
  <a href="https://www.linkedin.com/in/abhijeet-solanki"><img src="https://img.shields.io/badge/LinkedIn-0D1B2A?style=for-the-badge&logoColor=2DD4BF" alt="LinkedIn"></a>
  <a href="https://scholar.google.com/citations?view_op=search_authors&mauthors=Abhijeet+Solanki"><img src="https://img.shields.io/badge/Scholar-0D1B2A?style=for-the-badge&logo=googlescholar&logoColor=2DD4BF" alt="Google Scholar"></a>
  <a href="mailto:abhijeet.solanki@outlook.com"><img src="https://img.shields.io/badge/Email-0D1B2A?style=for-the-badge&logo=maildotru&logoColor=2DD4BF" alt="Email"></a>
</p>

I make AI work where it is hardest: on edge devices with tight latency, memory, and power
budgets, and in production where demos do not count.

Currently a Software Engineer at **Arctera**, shipping GenAI incident tooling on Azure and
AKS. Based in Nashville, TN, open to relocation.

<table>
<tr>
<td width="33%" valign="top">

**⚡ Edge AI**

Real-time perception on NVIDIA Jetson — TensorRT, ONNX Runtime, quantization, pruning.
Took a deployed detector from **72% → 93%** inside the same compute budget.

</td>
<td width="33%" valign="top">

**🤖 GenAI in production**

LLM agents, RAG, function calling, evals and guardrails on Azure OpenAI, LangChain and
vLLM. Systems that survive contact with real users.

</td>
<td width="33%" valign="top">

**🚗 Autonomous systems**

Camera and LiDAR perception that stays accurate when the physical world misbehaves —
adversarial patches, laser attacks, sensor spoofing.

</td>
</tr>
</table>

**12 peer-reviewed publications**, 5 first-author, including two IEEE Access journal
articles and ACM/IEEE SEC 2026. Three more under review.

---

## Selected work

### 🧠 [CAFE — Compressed Facial Expression Recognition for the Edge](https://github.com/ChiefAj23/CAFE-SEC-2026)

**Artifact for our ACM/IEEE SEC 2026 paper.** A two-stage, fully decoupled YOLOv12n pipeline —
face detector plus an independent emotion classifier — compressed to run in near real time on a
15 W NVIDIA Jetson Orin Nano. Topological model surgery makes YOLOv12n structurally prunable
where standard pruners fail, and an 88-configuration sweep across pruning ratios and precisions
is measured on both a desktop GPU and the Orin Nano.

<img src="assets/cafe-tradeoff.jpg" alt="All 88 pipeline configurations plotted as model size against end-to-end latency on a Jetson Orin Nano, with the P0-FP32 baseline and the chosen P10-FP16 configuration marked" width="100%">

| On a Jetson Orin Nano @ 15 W | Dense baseline | Compressed |
|---|---|---|
| Combined model size | 17.020 MB | **8.025 MB** — 2.12× smaller |
| End-to-end latency | 228.4 ms | **68.6 ms** — 3.33× faster (≈4.4 → ≈15 FPS) |
| Detector mAP50-95 | 0.5038 | 0.4895 — 97.2% retained |

Reference implementation, compressed weights, the annotated multi-face stress set, the EDUS
scoring metric, and the full measurement matrices for both platforms.

### 🔊 [AI Voice Compliance Auditor](https://github.com/ChiefAj23/AI-Voice-Compliance-Auditor)

Full-stack GenAI app that turns raw call recordings into compliance and coaching insights:
Whisper transcription, 0–100 scoring, toxicity and missing-disclosure detection, alert
workflows, and SHAP explainability so a reviewer can see *why* a call was flagged.
FastAPI + React/TypeScript.

<img src="assets/voice-auditor.jpg" alt="Mel spectrogram of an example call with the matched keyword rule and the 0 to 100 compliance score" width="100%">

### 🧪 [Prooftrace](https://abhijeetsolanki.com/prooftrace)

An agent that reads the acceptance criteria out of a user story, drives a real browser to check
each one, and emits reusable Gherkin features and Playwright specs the team can rerun. The run
below proves 8 of 8 criteria in 29.7 s for $0.028 of model spend, and the same recipe replays
without a model for free. Source is private, available on request.

<img src="assets/prooftrace.jpg" alt="Prooftrace run view: step timeline, per-criterion verification with evidence, and the generated feature, steps, page-object and spec files" width="100%">

### 📍 [Nashville Crime Hotspot Analysis](https://github.com/ChiefAj23/Nashville-Crime-Hotspot-Analysis-App)

DBSCAN clustering over Metro 911 call data, surfacing hotspots and proximity safety alerts
through a FastAPI + React map dashboard.

### 🖥 [gem5 Benchmark Suite](https://github.com/ChiefAj23/Gem5BenchSuite)

Workload benchmarking on the gem5 microarchitecture simulator.

### 🛰 Published research code

[**ReAL**](https://github.com/ChiefAj23/ReAL-ReflectiveAttack-Detection-Lidar) — machine
learning detection of reflective attacks against LiDAR odometry ·
[**GNAP**](https://github.com/ChiefAj23/GNAPing-On-the-Job) — attacking and defending
facial detection on edge devices. Both IEEE SoutheastCon 2025.

> *Two more lines of work are held back pending publication: adversarial patch removal for
> physical stop-sign attacks on a QCar2 testbed, and VLM perception for autonomous driving —
> benchmarking vision-language models as open-vocabulary detectors on real driving data with
> safety-weighted metrics.*

---

## Research

Robustness of edge-deployed perception under physical-world attack, and compressing
models small enough to run on it.

> **Just accepted** — *CAFE: Compressed Architecture for Edge-Deployed Facial Expression
> Recognition in Ambient Invisible Intelligence* at **ACM/IEEE SEC 2026**, the Eleventh
> ACM/IEEE Symposium on Edge Computing.

| Venue | Paper |
|---|---|
| **ACM/IEEE SEC 2026** | CAFE: Compressed Architecture for Edge-Deployed Facial Expression Recognition in Ambient Invisible Intelligence |
| **IEEE Access 2026** | Blinded by the Beam: A Unified Real-Time Defense Against Laser-Based Attacks on Navigational Perception of Autonomous Vehicles |
| **IEEE Access 2025** | Survey of Navigational Perception Sensors' Security in Autonomous Vehicles |
| **ISVLSI 2024** | Investigate the Effects of Laser Attack on the Intelligence of the AV Perception |

Full list on [Google Scholar](https://scholar.google.com/citations?view_op=search_authors&mauthors=Abhijeet+Solanki).
Some submitted papers are not listed due to double-blind review and will appear after
acceptance.

🥇 Two 1st Place research awards — ACM Mid-Southeast (#1 of 38), TTU Research and Inquiry
Day (#1 of 220) · IEEE-HKN and Tau Beta Pi · Reviewer, IEEE DCAS 2026

---

## Tools

**Machine learning**

<p>
<img src="https://img.shields.io/badge/PyTorch-0D1B2A?style=flat-square&logo=pytorch&logoColor=2DD4BF" alt="PyTorch">
<img src="https://img.shields.io/badge/TensorRT-0D1B2A?style=flat-square&logo=nvidia&logoColor=2DD4BF" alt="TensorRT">
<img src="https://img.shields.io/badge/ONNX%20Runtime-0D1B2A?style=flat-square&logo=onnx&logoColor=2DD4BF" alt="ONNX Runtime">
<img src="https://img.shields.io/badge/CUDA-0D1B2A?style=flat-square&logo=nvidia&logoColor=2DD4BF" alt="CUDA">
<img src="https://img.shields.io/badge/Jetson-0D1B2A?style=flat-square&logo=nvidia&logoColor=2DD4BF" alt="Jetson">
<img src="https://img.shields.io/badge/vLLM-0D1B2A?style=flat-square&logoColor=2DD4BF" alt="vLLM">
<img src="https://img.shields.io/badge/LangChain-0D1B2A?style=flat-square&logo=langchain&logoColor=2DD4BF" alt="LangChain">
</p>

Quantization (PTQ/QAT) · pruning · edge inference · RAG · agents · XAI (Grad-CAM, SHAP)

**Languages and backend**

<p>
<img src="https://img.shields.io/badge/Python-0D1B2A?style=flat-square&logo=python&logoColor=2DD4BF" alt="Python">
<img src="https://img.shields.io/badge/C++-0D1B2A?style=flat-square&logo=cplusplus&logoColor=2DD4BF" alt="C++">
<img src="https://img.shields.io/badge/C%23-0D1B2A?style=flat-square&logo=dotnet&logoColor=2DD4BF" alt="C#">
<img src="https://img.shields.io/badge/FastAPI-0D1B2A?style=flat-square&logo=fastapi&logoColor=2DD4BF" alt="FastAPI">
<img src="https://img.shields.io/badge/React-0D1B2A?style=flat-square&logo=react&logoColor=2DD4BF" alt="React">
<img src="https://img.shields.io/badge/TypeScript-0D1B2A?style=flat-square&logo=typescript&logoColor=2DD4BF" alt="TypeScript">
</p>

**Cloud and infrastructure**

<p>
<img src="https://img.shields.io/badge/Azure-0D1B2A?style=flat-square&logoColor=2DD4BF" alt="Azure">
<img src="https://img.shields.io/badge/AWS-0D1B2A?style=flat-square&logoColor=2DD4BF" alt="AWS">
<img src="https://img.shields.io/badge/Docker-0D1B2A?style=flat-square&logo=docker&logoColor=2DD4BF" alt="Docker">
<img src="https://img.shields.io/badge/Kubernetes-0D1B2A?style=flat-square&logo=kubernetes&logoColor=2DD4BF" alt="Kubernetes">
<img src="https://img.shields.io/badge/Terraform-0D1B2A?style=flat-square&logo=terraform&logoColor=2DD4BF" alt="Terraform">
</p>

---

## Elsewhere

[abhijeetsolanki.com](https://www.abhijeetsolanki.com/) ·
[LinkedIn](https://www.linkedin.com/in/abhijeet-solanki) ·
[Medium](https://abhijeet-solanki.medium.com) ·
[abhijeet.solanki@outlook.com](mailto:abhijeet.solanki@outlook.com)

I am looking for roles putting models on edge hardware and making them fast, or building
GenAI systems that hold up in production. Happy to compare notes either way.

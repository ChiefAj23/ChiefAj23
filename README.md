### AI Engineer — edge inference and GenAI in production

I make AI work where it is hardest: on edge devices with tight latency, memory, and
power budgets, and in production where demos do not count.

Currently a Software Engineer at **Arctera**, shipping GenAI incident tooling on Azure
and AKS. Based in Nashville, TN, open to relocation.

- **Edge AI** — real-time perception on NVIDIA Jetson: TensorRT, ONNX Runtime,
  quantization, pruning. Got a deployed detector from 72% to 93% within the same
  compute budget.
- **GenAI in production** — LLM agents, RAG, function calling, evals and guardrails
  on Azure OpenAI, LangChain, and vLLM.
- **Autonomous systems** — camera and LiDAR perception that stays accurate when the
  physical world misbehaves.
- **Research** — 11 peer-reviewed IEEE publications, 5 first-author, including two
  IEEE Access journal articles. Four more under review.

## Selected work

**[Adversarial Patch Removal for Stop Signs](https://github.com/ChiefAj23/qcar-patch-removal)**
A printed sticker on a stop sign makes a detector miss it in over half of approach
frames. This 3.35M-parameter dual-head U-Net erases the sticker before detection on
our QCar2 physical testbed, taking detection from 48% to 76% with no regression on
clean signs. Exports to ONNX and TensorRT.

**[AI Voice Compliance Auditor](https://github.com/ChiefAj23/AI-Voice-Compliance-Auditor)**
Full-stack GenAI app that turns raw call recordings into compliance and coaching
insights: Whisper transcription, 0-100 scoring, toxicity and missing-disclosure
detection, alert workflows, and SHAP explainability so a reviewer can see why a call
was flagged. FastAPI + React/TypeScript.

**[Nashville Crime Hotspot Analysis](https://github.com/ChiefAj23/Nashville-Crime-Hotspot-Analysis-App)**
DBSCAN clustering over Metro 911 call data, surfacing hotspots and proximity safety
alerts through a FastAPI + React map dashboard.

**[gem5 Benchmark Suite](https://github.com/ChiefAj23/Gem5BenchSuite)**
Workload benchmarking on the gem5 microarchitecture simulator.

**Published research code** —
[ReAL: LiDAR reflective attack detection](https://github.com/ChiefAj23/ReAL-ReflectiveAttack-Detection-Lidar)
and [GNAP: attacking and defending facial detection on edge devices](https://github.com/ChiefAj23/GNAPing-On-the-Job),
both IEEE SoutheastCon 2025.

*VLM perception for autonomous driving is in progress — benchmarking vision-language
models as open-vocabulary detectors on real driving data, with safety-weighted
metrics. Held back pending publication.*

## Research

Robustness of edge-deployed perception under physical-world attack.

- **IEEE Access 2026** — *Blinded by the Beam: A Unified Real-Time Defense Against
  Laser-Based Attacks on Navigational Perception of Autonomous Vehicles*
- **IEEE Access 2025** — *Survey of Navigational Perception Sensors' Security in
  Autonomous Vehicles*
- **ISVLSI 2024** — *Investigate the Effects of Laser Attack on the Intelligence of
  the AV Perception*

Full list on [Google Scholar](https://scholar.google.com/citations?view_op=search_authors&mauthors=Abhijeet+Solanki).
Some submitted papers are not listed due to double-blind review and will appear after
acceptance.

Two 1st Place research awards (ACM Mid-Southeast, #1 of 38; TTU Research and Inquiry
Day, #1 of 220). IEEE-HKN and Tau Beta Pi. Reviewer for IEEE DCAS 2026.

## Tools

**ML** — PyTorch, TensorFlow, ONNX Runtime, TensorRT, CUDA, vLLM, LangChain,
quantization (PTQ/QAT), pruning, XAI (Grad-CAM, SHAP).

**Languages and backend** — Python, C++, C#, FastAPI, React/TypeScript, .NET.

**Cloud** — Azure, AWS, Docker, Kubernetes, Terraform, GitHub Actions.

## Elsewhere

[abhijeetsolanki.com](https://www.abhijeetsolanki.com/) ·
[LinkedIn](https://www.linkedin.com/in/abhijeet-solanki) ·
[Medium](https://abhijeet-solanki.medium.com) ·
[abhijeet.solanki@outlook.com](mailto:abhijeet.solanki@outlook.com)

I am looking for roles putting models on edge hardware and making them fast, or
building GenAI systems that hold up in production. Happy to compare notes either way.

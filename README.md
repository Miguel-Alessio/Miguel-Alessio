# Hi, I'm Miguel Alessio 👋

Computer Science student at **UPB – Automatic Control and Computer Science (ACS)**, Bucharest. I work where **security engineering meets AI**: I build detections, automate incident response and train models, on top of solid low-level foundations in C and x86-64 Assembly.

I like finding out *why* something breaks, whether it's a bug, a misbehaving model or an attacker hiding in the logs.

### 🚀 What I'm working on
* 🛡️ **Mini-SOC lab**: a home SIEM/SOAR on Raspberry Pis with MITRE ATT&CK-mapped detections and automated response. Next up: CI tests, scanner detection (T1595.003), Sigma rules and a comparison against Suricata.
* 🤖 **AI agents and LLMs**: fine-tuning models and building agents, with a focus on how AI can make security operations faster.
* ⚙️ **Systems fundamentals**: operating systems, memory management and data structures, which is what makes the above work.
* 🎯 Looking for an **internship in detection engineering, security engineering or AI security**. Available part-time now, full-time from **summer 2027**. Bucharest or remote.

---

### 🔥 Featured Projects

**🛡️ Security & AI**
* **[Mini-SOC: Detection & Automated Response Lab](https://github.com/Miguel-Alessio/mini-soc-lab)**: a two-node SIEM/SOAR on Raspberry Pis. A hardened rsyslog pipeline streams SSH and Nginx logs to a Python detection engine with MITRE ATT&CK-mapped rules: brute force (T1110.001), LFI/SQLi (T1190) and compromised accounts (T1078.003), which catches slow attackers below the brute-force threshold. Attacker IPs are blocked through iptables within seconds and live sessions get cut. The engine is hardened too (no command injection, safe SSH handling, log-rotation support) and every scenario was verified on real hardware.
* **[Qwen-7B Chess Fine-Tuning](https://github.com/Miguel-Alessio/qwen-chess-lora)**: LoRA fine-tuning (BF16) of Qwen-7B on ~192,000 games to generate moves in SAN, trained on an NVIDIA A100 via Modal (12,000 steps, final loss 0.43). Built during the ROSEdu CDL open-source program; weights published.
* **[Edge Vision Alarm](https://github.com/Miguel-Alessio/edge-vision-alarm)**: person detection on a Raspberry Pi 3 with YOLOv8 (ONNX) and OpenCV. It publishes alarm state over MQTT, saves annotated frames and runs with Docker Compose.

**⚙️ Systems & Algorithms**
* **[In-Memory Search Engine](https://github.com/Miguel-Alessio/In-Memory-Search-Engine)**: a text-indexing system in C using tries, heaps and doubly linked lists for $O(w)$ lookups and top-k relevance retrieval.
* **[x86-64 Assembly Algorithmic Toolkit](https://github.com/Miguel-Alessio/x86-64-Assembly-Algorithmic-Toolkit)**: a 2D maze solver and custom struct sorters in pure x86-64 Assembly, following the System V AMD64 ABI.
* **[Sparse-View CT Reconstruction](https://github.com/Miguel-Alessio/Sparse-View-CT-Reconstruction)**: adaptive CT reconstruction from scratch with Conjugate Gradient Least Squares (CGLS) and Total Variation denoising.

---

### 🛠️ Tech Stack & Tools

<p align="left">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white" alt="C" />
  <img src="https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white" alt="C++" />
  <img src="https://img.shields.io/badge/Assembly_x86--64-1572B6?style=for-the-badge&logo=gnu-bash&logoColor=white" alt="Assembly" />
  <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java" />
  <img src="https://img.shields.io/badge/MATLAB-0076A8?style=for-the-badge&logo=mathworks&logoColor=white" alt="MATLAB" />
</p>
<p align="left">
  <img src="https://img.shields.io/badge/Linux_Pop!_OS-FCC624?style=for-the-badge&logo=linux&logoColor=black" alt="Linux" />
  <img src="https://img.shields.io/badge/Raspberry_Pi-A22846?style=for-the-badge&logo=raspberrypi&logoColor=white" alt="Raspberry Pi" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white" alt="Nginx" />
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git" />
  <img src="https://img.shields.io/badge/Hugging_Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black" alt="Hugging Face" />
  <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white" alt="OpenCV" />
  <img src="https://img.shields.io/badge/MITRE_ATT%26CK-C8102E?style=for-the-badge&logoColor=white" alt="MITRE ATT&CK" />
</p>

---

### 🌍 Languages
Romanian (native) · Spanish (native) · English (C1) · Italian & Catalan (A2)

### 📫 Let's Connect!
* **Email:** essio.pg@gmail.com
* **LinkedIn:** [linkedin.com/in/miguel-pasagali-82a997288](https://www.linkedin.com/in/miguel-pasagali-82a997288/)

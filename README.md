<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=26&duration=3000&pause=800&color=00E676&center=true&vCenter=true&width=1100&lines=Abhishek+Chandragiri;AI+Platform+Engineer+%7C+Production+Multimodal+AI;Document+Intelligence+%7C+Healthcare+AI+(HIPAA);GPUs+%7C+CUDA+%7C+Inference+Systems+%7C+MLOps;Building+AI+that+works+in+real+production" />

<p>
  <a href="https://www.linkedin.com/in/abhishek-chandragiri/">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="https://abhi0323.github.io/Abhishek-Chandragiri-Portfolio/">
    <img src="https://img.shields.io/badge/Portfolio-111111?style=for-the-badge&logo=About.me&logoColor=white" />
  </a>
  <a href="https://huggingface.co/Abhishek0323">
    <img src="https://img.shields.io/badge/HuggingFace-FFB000?style=for-the-badge&logo=huggingface&logoColor=111111" />
  </a>
  <a href="https://medium.com/@abhishekgoud1212">
    <img src="https://img.shields.io/badge/Medium-12100E?style=for-the-badge&logo=medium&logoColor=white" />
  </a>
  <a href="https://public.tableau.com/app/profile/abhishek.chandragiri/vizzes">
    <img src="https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=Tableau&logoColor=white" />
  </a>
</p>

<p>
  <img src="https://img.shields.io/badge/Total%20Profile%20Views-0B0F19?style=for-the-badge" />
  <img src="https://profile-counter.glitch.me/Abhi0323/count.svg" alt="Profile views counter" />
</p>

<p>
  <img src="https://img.shields.io/badge/Location-Greater%20Philadelphia-8A2BE2?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Focus-Production%20AI%20Systems-00E676?style=for-the-badge" />
</p>

</div>

---

<img align="right" height="305" src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExaGk4MnF3ajR1Y2l3Y3p0NHk1azF2b3JtYjQ2bDJ3aDN5b2o2dWh1YiZlcD12MV9naWZzX3NlYXJjaCZjdD1n/QTfX9Ejfra3ZmNxh6B/giphy.gif" />

## About

I build **production-grade AI systems for complex, regulated environments** — where **correctness, reliability, security, and explainability** matter more than demos.

My work sits at the intersection of:

- **Document Intelligence** (OCR, layout, page understanding, field extraction)
- **Multimodal AI** (LLMs, SLMs, VLMs) for real healthcare workflows
- **AI Platform Engineering** (on-prem, cloud, gov cloud; microservices; CI/CD)
- **GPU + Inference Systems** (CUDA, drivers, custom builds, profiling)

I care deeply about **responsible AI in healthcare**: audit-friendly, verifiable, compliant systems that make care faster and easier without compromising safety.

---

## Healthcare AI Work (Production Systems)

### Medical Claims Review Platform (HIPAA / PHI / PII, On-Prem)

Built and operated a production platform that processes large medical claim PDFs end-to-end:

- **OCR + document splitting**
- **Page classification** using DistilBERT + rules to identify page types reliably
- **Layout detection** using YOLO to localize regions (titles, summary boxes, checkboxes, etc.)
- **Region cropping** to reduce VLM/OCR noise and compute cost
- **Field extraction** tailored by page type (beneficiary details, NPI/MBI, HCPCS/CPT, ICD codes, claim lines, etc.)
- **Decision support** using RAG that answers reviewer questions with **evidence + traceability**
- Human-in-the-loop UI enabling reviewers to verify where answers came from

Key engineering themes included **accuracy vs scalability trade-offs** in regulated workflows, with layered validation and compute-aware routing (cheap → expensive only when necessary).

### CMS WISeR (2026) — Prior Authorization Automation (NJ / MAC Novitas)

- Built a **service operations module** end-to-end (frontend + backend) under aggressive timelines using AI-assisted development tools
- Implemented OCR using **Azure Document Intelligence**, including **custom model training** for prior authorization cover sheets
- Deployed services via **Azure Web Apps**

---

## Open Source

### Docling (LF AI & Data)

- Fixed layout label normalization issues impacting Egret layout outputs
- Added tests to ensure compatibility across layout model label styles
- Continuing contributions to document AI tooling

---

## Core Capabilities

### Production Document Intelligence
- OCR pipelines, layout detection, page classification, structured extraction
- Robust handling of messy real documents: handwriting, checkboxes, signatures, diagrams

### LLM / SLM / VLM Systems
- Model selection & benchmarking: LLaMA, Mistral, Phi-3, BioBERT, BioMedBERT, biomedical variants
- RAG with evidence grounding using PostgreSQL vector search
- Guardrails for controlled and compliant inputs/outputs
- Fine-tuning and 4-bit quantization for CPU-first inference paths

### GPU + Inference Engineering
- Bare-metal GPU bring-up: drivers, CUDA Toolkit, NVCC, kernel compatibility
- H100 / L40s / A40 / RTX 4090 / RTX 5090 / DGX environments
- Inference runtimes: PyTorch, ONNX Runtime, llama.cpp (custom builds aligned to CUDA + SM capability)

### Platform Engineering & Deployment
- Microservices architecture in regulated environments
- On-prem deployment on RHEL-based systems using **RPM packaging + systemd**
- Containers + Kubernetes + Azure Container Registry
- CI/CD using Azure DevOps for RPMs, artifacts, and release workflows
- Experience across **on-prem + cloud + gov cloud**

### Reliability, Observability, Security
- Monitoring stack: Telegraf + InfluxDB + Chronograf (system/service/GPU metrics)
- Production tuning: worker sizing, CPU/I/O concurrency, DB pooling, timeouts
- Security: HTTPS everywhere, certificate-based auth, **mTLS** between services and to DB
- Compliance-first engineering: HIPAA/PHI/PII handling influenced architecture end-to-end

### Leadership
- Led a team of interns for layout detection (Label Studio + YOLO)
- Mentored associates on installation/testing/validation and architecture onboarding
- Operated across roles when needed (client-facing technical lead, product owner proxy, infra/security partner)

---

## Tech Stack (Neon / Color)

### AI / ML / Inference
<p>
  <img src="https://img.shields.io/badge/Python-0B0F19?style=for-the-badge&logo=python&logoColor=00E676" />
  <img src="https://img.shields.io/badge/PyTorch-0B0F19?style=for-the-badge&logo=pytorch&logoColor=FF1744" />
  <img src="https://img.shields.io/badge/Transformers-0B0F19?style=for-the-badge&logo=huggingface&logoColor=FFCA28" />
  <img src="https://img.shields.io/badge/ONNX%20Runtime-0B0F19?style=for-the-badge&logo=onnx&logoColor=00B0FF" />
  <img src="https://img.shields.io/badge/llama.cpp-0B0F19?style=for-the-badge&logoColor=FFFFFF" />
  <img src="https://img.shields.io/badge/LangChain-0B0F19?style=for-the-badge&logoColor=00E676" />
</p>

### Document Intelligence
<p>
  <img src="https://img.shields.io/badge/OCR-0B0F19?style=for-the-badge&logoColor=00E5FF" />
  <img src="https://img.shields.io/badge/YOLO%20Layout%20Detection-0B0F19?style=for-the-badge&logoColor=FF1744" />
  <img src="https://img.shields.io/badge/DistilBERT%20Page%20Classification-0B0F19?style=for-the-badge&logoColor=B388FF" />
  <img src="https://img.shields.io/badge/RAG%20(Evidence%20Grounded)-0B0F19?style=for-the-badge&logoColor=00E676" />
</p>

### GPUs / CUDA
<p>
  <img src="https://img.shields.io/badge/NVIDIA-0B0F19?style=for-the-badge&logo=nvidia&logoColor=76B900" />
  <img src="https://img.shields.io/badge/CUDA-0B0F19?style=for-the-badge&logo=nvidia&logoColor=00E676" />
  <img src="https://img.shields.io/badge/H100%20%7C%20L40s%20%7C%20A40%20%7C%204090%20%7C%205090-0B0F19?style=for-the-badge&logoColor=FFFFFF" />
</p>

### Platform / Deployment
<p>
  <img src="https://img.shields.io/badge/Linux%20(RHEL%2FRocky%2FAlma)-0B0F19?style=for-the-badge&logo=linux&logoColor=FFFFFF" />
  <img src="https://img.shields.io/badge/FastAPI-0B0F19?style=for-the-badge&logo=fastapi&logoColor=00E676" />
  <img src="https://img.shields.io/badge/Docker-0B0F19?style=for-the-badge&logo=docker&logoColor=00B0FF" />
  <img src="https://img.shields.io/badge/Kubernetes-0B0F19?style=for-the-badge&logo=kubernetes&logoColor=3D8BFF" />
  <img src="https://img.shields.io/badge/Azure-0B0F19?style=for-the-badge&logo=microsoftazure&logoColor=00B0FF" />
  <img src="https://img.shields.io/badge/Azure%20DevOps-0B0F19?style=for-the-badge&logo=azuredevops&logoColor=00B0FF" />
  <img src="https://img.shields.io/badge/RPM%20%2B%20systemd-0B0F19?style=for-the-badge&logo=redhat&logoColor=FF1744" />
</p>

### Databases / Vector Search
<p>
  <img src="https://img.shields.io/badge/PostgreSQL-0B0F19?style=for-the-badge&logo=postgresql&logoColor=00B0FF" />
  <img src="https://img.shields.io/badge/Postgres%20Vector%20Search-0B0F19?style=for-the-badge&logo=postgresql&logoColor=00E676" />
</p>

### Observability / Performance
<p>
  <img src="https://img.shields.io/badge/Telegraf-0B0F19?style=for-the-badge&logoColor=00E5FF" />
  <img src="https://img.shields.io/badge/InfluxDB-0B0F19?style=for-the-badge&logo=influxdb&logoColor=00B0FF" />
  <img src="https://img.shields.io/badge/Chronograf-0B0F19?style=for-the-badge&logoColor=B388FF" />
</p>

### Security / Compliance
<p>
  <img src="https://img.shields.io/badge/mTLS-0B0F19?style=for-the-badge&logoColor=00E676" />
  <img src="https://img.shields.io/badge/Certificate%20Auth-0B0F19?style=for-the-badge&logoColor=00B0FF" />
  <img src="https://img.shields.io/badge/HIPAA%20(PHI%2FPII)-0B0F19?style=for-the-badge&logoColor=FF1744" />
</p>

---

## Featured Projects

- **RAG-Powered AI Assistant (Web + PDFs)**  
  https://github.com/Abhi0323/RAG-Powered-AI-Assistant-Transforming-Data-Retrieval-and-Analysis-Across-the-Web-and-PDFs

- **Fine-Tuning LLaMA-2 with QLoRA/PEFT**  
  https://github.com/Abhi0323/Fine-Tuning-LLaMA-2-with-QLORA-and-PEFT

- **Real-time ML Deployment (K8s + CI/CD)**  
  https://github.com/Abhi0323/Real-Time-Customer-Segmentation-with-Scalable-Kubernetes-Deployment-and-CI-CD-Integration

- **MLOps Predictive Maintenance (AWS + Docker + CI/CD)**  
  https://github.com/Abhi0323/Agile-MLOps-Deployment-Docker-AWS-CI-CD-Pipeline

---

## GitHub Stats

<div align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api?username=Abhi0323&show_icons=true&theme=radical&rank_icon=github" />
<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Abhi0323&layout=compact&theme=radical&langs_count=10" />
<img height="170" src="https://streak-stats.demolab.com/?user=Abhi0323&theme=radical" />

</div>

---

## Writing

- Medium: https://medium.com/@abhishekgoud1212  
- Portfolio: https://abhi0323.github.io/Abhishek-Chandragiri-Portfolio/

Topics: production AI architecture, accuracy vs scalability in regulated systems, GPU inference and deployment.

---

## Contact

If you’re building production AI in regulated environments (document intelligence, evidence-grounded RAG, GPU-backed inference), connect here:  
https://www.linkedin.com/in/abhishek-chandragiri/

<div align="center">
  <img src="https://img.shields.io/badge/Production%20AI%20Systems-0B0F19?style=for-the-badge&logoColor=00E676" />
  <img src="https://img.shields.io/badge/Compliance%20First-0B0F19?style=for-the-badge&logoColor=FF1744" />
  <img src="https://img.shields.io/badge/Performance%20Aware-0B0F19?style=for-the-badge&logoColor=00B0FF" />
</div>

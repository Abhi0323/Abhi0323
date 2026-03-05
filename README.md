<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=26&duration=3000&pause=800&color=00E676&center=true&vCenter=true&width=1000&lines=Hi+%F0%9F%91%8B+I%27m+Abhishek+Chandragiri" />

<p>
  <a href="https://www.linkedin.com/in/abhishek-chandragiri/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
  <a href="https://abhi0323.github.io/Abhishek-Chandragiri-Portfolio/"><img src="https://img.shields.io/badge/Portfolio-111111?style=for-the-badge&logo=About.me&logoColor=white"/></a>
  <a href="https://huggingface.co/Abhishek0323"><img src="https://img.shields.io/badge/HuggingFace-FFB000?style=for-the-badge&logo=huggingface&logoColor=white"/></a>
  <a href="https://medium.com/@abhishekgoud1212"><img src="https://img.shields.io/badge/Medium-12100E?style=for-the-badge&logo=medium&logoColor=white"/></a>
  <a href="https://public.tableau.com/app/profile/abhishek.chandragiri/vizzes"><img src="https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=Tableau&logoColor=white"/></a>
</p>

<p>
  <img src="https://komarev.com/ghpvc/?username=Abhi0323&label=Profile%20Views&color=0e75b6&style=for-the-badge" />
  <img src="https://img.shields.io/badge/Location-Greater%20Philadelphia-8A2BE2?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Focus-Production%20AI%20Systems-2ECC40?style=for-the-badge" />
</p>

</div>

---

<img align="right" height="310" src="https://media.giphy.com/media/qgQUggAC3Pfv687qPC/giphy.gif"/>
## 🚀 About Me

I build **production-grade AI systems for complex regulated environments** — where **correctness, reliability, security, and explainability** matter more than benchmarks.

My work sits at the intersection of:

- 📄 **Document Intelligence** (OCR + layout + page understanding + field extraction)
- 🧠 **Multimodal AI** (LLMs / SLMs / VLMs) for real healthcare workflows
- ⚙️ **AI Platform Engineering** (on-prem, cloud, gov cloud; microservices; CI/CD)
- ⚡ **GPU + inference systems** (CUDA, NVIDIA drivers, custom builds, profiling)

I’m passionate about **Responsible AI in healthcare** — making care faster and easier while staying **audit-friendly, verifiable, and compliant**.

---

## 🏥 What I’ve built in Healthcare AI

### ✅ AI platform for medical claims review (HIPAA / PHI / PII)
A production platform that processes large medical claim PDFs end-to-end:

- **OCR + document splitting**
- **Page classification** (DistilBERT + rules) to categorize page types
- **Layout detection** (YOLO) to locate page regions (titles, summary boxes, checkboxes, etc.)
- **Region cropping** to improve OCR/VLM accuracy and reduce compute
- **Field extraction** (beneficiary details, NPI/MBI, HCPCS/CPT, ICD codes, claim lines, etc.)
- **Decision support system** using **RAG**, answering nurse review questions with **evidence + traceability**
- Human-in-the-loop UI: nurses can **verify exactly where an answer came from**

### ✅ Prior Authorization automation 
- Built a **full end-to-end service operations module** (frontend + backend) rapidly using AI-assisted development (Cursor/Claude)
- Implemented an OCR service using **Azure Document Intelligence** with **custom-trained models** for prior auth cover sheets
- Deployed services using **Azure Web Apps**

## 🧩 Core Capabilities (What I do well)

✅ **Production Document Intelligence**
- OCR pipelines, layout detection, page classification, field extraction
- Handling messy documents: handwriting, checkboxes, signatures, diagrams

✅ **LLM/SLM/VLM Systems**
- Model selection & benchmarking (LLaMA, Mistral, Phi-3, BioBERT, BioMedBERT, Bio-Mistral)
- RAG with citations + evidence grounding
- Guardrails using LangChain (safe inputs/outputs for regulated environments)
- Fine-tuning + CPU-first optimization via 4-bit quantization (C++/BitNet-style)

✅ **GPU + Inference Engineering**
- Bare-metal GPU bring-up (drivers, CUDA toolkit, NVCC, kernels)
- H100 / L40s / A40 / RTX 4090 / RTX 5090 / DGX environments
- Inference runtimes: PyTorch, ONNX Runtime, llama.cpp
- Custom builds aligned to CUDA versions + GPU compute capability

✅ **Platform Engineering & Deployment**
- Microservices architecture
- On-prem deployment on RHEL-based systems
- RPM packaging + systemd services for “install → services up”
- Containers + Kubernetes + ACR
- CI/CD (Azure DevOps) for RPMs + artifacts + deployments
- Experience across **on-prem + cloud + gov cloud**

✅ **Reliability, Observability, Security**
- Performance monitoring stack: Telegraf + InfluxDB + Chronograf
- System/service/GPU metrics and bottleneck analysis
- Production tuning: Uvicorn workers, CPU/I/O concurrency, DB pooling
- Security: HTTPS everywhere, cert-based auth, **mTLS** between services + to DB

✅ **Leadership**
- Led **15 interns** (Label Studio + YOLO layout detection pipeline)
- Mentored **3 associates** (install/test/validation, architecture onboarding)
- Acted as product-owner proxy / client-facing technical lead when needed

---

## 🧰 Tech Stack (Colorful + Organized)

### 🧠 AI / ML / NLP
<p>
  <img src="https://skillicons.dev/icons?i=python,pytorch,tensorflow" />
  <img src="https://img.shields.io/badge/Transformers-FFCA28?style=for-the-badge&logo=huggingface&logoColor=000"/>
  <img src="https://img.shields.io/badge/ONNX%20Runtime-005CED?style=for-the-badge&logo=onnx&logoColor=white"/>
  <img src="https://img.shields.io/badge/llama.cpp-6D4C41?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge"/>
</p>

### 📄 Document Intelligence
<p>
  <img src="https://img.shields.io/badge/OCR-00ACC1?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Layout%20Detection%20(YOLO)-FF1744?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Page%20Classification%20(DistilBERT)-7E57C2?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/RAG%20%2B%20Evidence%20Tracing-26A69A?style=for-the-badge"/>
</p>

### ⚡ GPUs / CUDA
<p>
  <img src="https://img.shields.io/badge/NVIDIA-76B900?style=for-the-badge&logo=nvidia&logoColor=white"/>
  <img src="https://img.shields.io/badge/CUDA-0B0F19?style=for-the-badge&logo=nvidia&logoColor=76B900"/>
  <img src="https://img.shields.io/badge/H100%20%7C%20L40s%20%7C%20A40%20%7C%204090%20%7C%205090-111111?style=for-the-badge"/>
</p>

### ☁️ Platform / Deployment
<p>
  <img src="https://skillicons.dev/icons?i=linux,docker,kubernetes,azure,aws,fastapi" />
  <img src="https://img.shields.io/badge/RPM%20Packaging-CC0000?style=for-the-badge&logo=redhat&logoColor=white"/>
  <img src="https://img.shields.io/badge/systemd-0B0F19?style=for-the-badge&logo=linux&logoColor=white"/>
  <img src="https://img.shields.io/badge/Azure%20DevOps-0078D7?style=for-the-badge&logo=azuredevops&logoColor=white"/>
</p>

### 🗄️ Databases / Vector Search
<p>
  <img src="https://skillicons.dev/icons?i=postgres,mysql,mongodb" />
  <img src="https://img.shields.io/badge/Postgres%20Vector%20Search-336791?style=for-the-badge&logo=postgresql&logoColor=white"/>
</p>

### 📈 Observability / Performance
<p>
  <img src="https://img.shields.io/badge/Telegraf-22A2A2?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/InfluxDB-22ADF6?style=for-the-badge&logo=influxdb&logoColor=white"/>
  <img src="https://img.shields.io/badge/Chronograf-8E24AA?style=for-the-badge"/>
</p>

### 🔐 Security / Compliance
<p>
  <img src="https://img.shields.io/badge/mTLS-2E7D32?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Cert%20Auth-1565C0?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/HIPAA%20(PHI%2FPII)-D32F2F?style=for-the-badge"/>
</p>


## 📊 GitHub Stats

<div align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api?username=Abhi0323&show_icons=true&theme=radical&rank_icon=github" />
<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Abhi0323&layout=compact&theme=radical&langs_count=10" />
<img height="170" src="https://streak-stats.demolab.com/?user=Abhi0323&theme=radical" />

</div>

---

## ✍️ Writing & Content

- Medium: https://medium.com/@abhishekgoud1212  
- Portfolio: https://abhi0323.github.io/Abhishek-Chandragiri-Portfolio/
---

## 🤝 Work With Me

If you're building:
- AI platforms in regulated environments  
- Document intelligence at scale  
- Evidence-grounded RAG systems  
- GPU-backed inference services  

Let’s connect: **https://www.linkedin.com/in/abhishek-chandragiri/**

---

<div align="center">

### ⭐ I build AI that survives production constraints — compliance, performance, and real-world messy data.

</div>

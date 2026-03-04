<div align="center">

# Abhishek Chandragiri

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=26&duration=3000&pause=800&color=00E5FF&center=true&vCenter=true&width=900&lines=AI+Platform+Engineer;Production+AI+Systems;Document+Intelligence+%7C+Healthcare+AI;GPU+Computing+%7C+CUDA+%7C+Inference+Engineering;Building+AI+Systems+for+Real+World+Impact" />

</div>

---

## About

I am an AI Platform Engineer focused on building production-grade artificial intelligence systems for complex real-world environments, particularly in regulated healthcare domains.

My work spans the entire lifecycle of AI systems, from model research and experimentation to infrastructure engineering, deployment, and operational monitoring.

Areas of focus include:

- Large Language Models, Small Language Models, and Vision Language Models  
- Document Intelligence and multimodal document processing  
- GPU inference infrastructure and CUDA optimization  
- AI microservices architectures  
- Healthcare AI systems operating under HIPAA-compliant environments  
- Evidence-grounded RAG systems for decision support  

My goal is to design AI platforms that are not only intelligent, but reliable, explainable, and deployable in real operational systems.

---

## Healthcare AI Platform Experience

I contributed to the development of an AI-powered clinical claims review platform used for medical claims processing and clinical document analysis.

The system processes large unstructured medical claim documents and transforms them into structured insights that assist clinical reviewers in making faster and safer decisions.

Typical documents contain a mixture of structured and unstructured information such as:

- handwritten notes  
- clinical signatures  
- checkboxes  
- medical diagrams  
- clinical observations  
- beneficiary and provider metadata  

The system architecture includes the following stages:

```
Document Input
     │
     ▼
OCR Processing and Page Splitting
     │
     ▼
Layout Detection using YOLO
     │
     ▼
Page Classification using DistilBERT
     │
     ▼
Region Cropping and Semantic Extraction
     │
     ▼
Field Extraction and Validation
     │
     ▼
RAG-based Decision Support with Evidence Tracing
```

Clinical reviewers can validate answers produced by the system by viewing the exact document locations where information was extracted.

---

## CMS WISeR Prior Authorization Project

I also contributed to a system supporting prior authorization workflows aligned with the CMS WISeR model.

This project focused on automating prior authorization document processing and enabling faster claim review workflows.

Key contributions included:

- Designing and implementing a service operations module  
- Rapid development of full-stack services using AI-assisted engineering tools  
- Building an OCR pipeline using Azure Document Intelligence  
- Training custom OCR models for prior authorization cover sheets  
- Deploying services through Azure Web Apps  

---

## AI Model Research and Deployment

My work includes evaluating and deploying a wide range of models for document understanding and clinical text processing.

Models explored and benchmarked include:

- LLaMA family models  
- Mistral models  
- Phi-3 small language models  
- BioBERT  
- BioMedBERT  
- Bio-Mistral  

Typical work includes:

- model benchmarking for domain-specific tasks  
- fine tuning for specialized document understanding tasks  
- model quantization (including 4-bit inference)  
- CPU-first inference optimization  
- integration with RAG pipelines  
- implementing guardrails using LangChain  

The focus is always on achieving reliable performance in production environments rather than relying solely on benchmark scores.

---

## GPU Systems and Inference Engineering

I work directly with bare-metal GPU environments and inference frameworks to support production AI workloads.

Hardware environments include:

- NVIDIA H100  
- NVIDIA L40s  
- NVIDIA A40  
- RTX 4090  
- RTX 5090  
- DGX systems  

Work performed includes:

- installing NVIDIA drivers and kernel modules  
- configuring CUDA toolkit environments  
- compiling CUDA components using NVCC  
- aligning inference frameworks with CUDA versions and GPU compute capability  
- profiling and optimizing inference performance  

Inference frameworks used include:

- PyTorch  
- ONNX Runtime  
- llama.cpp  

These systems are integrated into microservices to serve AI workloads efficiently.

---

## Document Intelligence Systems

Medical documents often contain complex layouts that standard OCR pipelines struggle to process.

To address this, document understanding pipelines were developed that combine computer vision and NLP techniques.

Key components include:

- layout detection using YOLO  
- page-level classification models  
- semantic region cropping for targeted extraction  
- multimodal reasoning using VLM models  
- structured data extraction from complex layouts  

This architecture significantly improves extraction accuracy when compared with full-page processing approaches.

---

## Platform Engineering and Deployment

The systems I work on are deployed across multiple environments including on-prem infrastructure, commercial cloud platforms, and government cloud environments.

Deployment experience includes:

- microservices architecture design  
- RPM-based packaging for enterprise Linux systems  
- systemd service configuration  
- containerized deployments using Docker  
- orchestration using Kubernetes  
- CI/CD pipelines built with Azure DevOps  

In regulated environments, deployment strategies must ensure both security and operational reliability.

---

## Security and Compliance

Healthcare AI systems must operate under strict security and compliance requirements.

Security mechanisms implemented include:

- certificate-based authentication between microservices  
- mutual TLS (mTLS) for secure service communication  
- encrypted communication channels across the entire system  
- compliance with HIPAA requirements for PHI and PII data  

These measures ensure that the platform operates safely in regulated healthcare environments.

---

## Observability and Performance Monitoring

To support reliable production operations, I designed and implemented a monitoring stack based on time-series observability tools.

The monitoring stack includes:

- Telegraf for metric collection  
- InfluxDB for time-series storage  
- Chronograf for visualization and dashboards  

Metrics collected include:

- CPU utilization  
- memory usage  
- disk IO  
- GPU utilization  
- microservice resource usage  

This monitoring system enables rapid diagnosis of performance bottlenecks and supports system capacity planning.

---

## Technical Stack

### AI and Machine Learning

<img src="https://skillicons.dev/icons?i=python,pytorch,tensorflow,sklearn"/>

### Infrastructure and Platform Engineering

<img src="https://skillicons.dev/icons?i=linux,docker,kubernetes,azure,aws"/>

### Databases

<img src="https://skillicons.dev/icons?i=postgres,mongodb,mysql"/>

### Development Tools

<img src="https://skillicons.dev/icons?i=git,github,vscode"/>

---

## GitHub Statistics

<p align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api?username=Abhi0323&show_icons=true&theme=tokyonight"/>

<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Abhi0323&layout=compact&theme=tokyonight"/>

<img height="170" src="https://streak-stats.demolab.com/?user=Abhi0323&theme=tokyonight"/>

</p>

---

## Writing and Publications

I write about applied AI engineering and real-world AI systems, including topics such as:

- building production-grade AI platforms  
- RAG architectures and model evaluation  
- GPU inference optimization  
- challenges of deploying AI in regulated environments  

Articles can be found at:

https://medium.com/@abhishekgoud1212

---

## Connect

LinkedIn  
https://www.linkedin.com/in/abhishek-chandragiri/

Portfolio  
https://abhi0323.github.io/Abhishek-Chandragiri-Portfolio/

Hugging Face  
https://huggingface.co/Abhishek0323

Tableau  
https://public.tableau.com/app/profile/abhishek.chandragiri

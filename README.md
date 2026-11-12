<h1>Hi, I'm Duy Lam 👋</h1>

**AI / ML Engineer** based in Ho Chi Minh City. I build end-to-end AI systems — real-time
Computer Vision on edge devices for factory lines, and LLM applications (RAG, agents, fine-tuning).

- 🏭 Machine Learning Engineer @ **Greystone Data Systems Vietnam** — detection models running 24/7 on device-manufacturing and phone-inspection lines
- 🔭 Currently working on: **RAG evaluation & MLOps**: retrieval benchmarks on UIT-ViQuAD 2.0 tracked in MLflow, CI with GitHub Actions
- 📄 2 peer-reviewed publications (Elsevier *Data in Brief*, *CTU Journal*)
- 📫 lamtanduy1605@gmail.com · [LinkedIn](https://www.linkedin.com/in/duy-l%C3%A2m-9b45a3234/)

---

### 🚀 Featured projects

| Project | What it does | Stack |
|---|---|---|
| 🤖 [**Vietnamese Agentic RAG**](https://github.com/lmtndy/vietnamese-agentic-rag) | Q&A over Vietnamese documents with source citations. A LangGraph agent routes each query, grades retrieved context and rewrites the query when retrieval fails. | LangGraph · Qdrant · Cross-encoder rerank · FastAPI |
| 🔧 [**Qwen2.5 QLoRA Fine-tuning**](https://github.com/lmtndy/qwen-qlora-vietnamese) | QLoRA fine-tuning of Qwen2.5-1.5B for Vietnamese text classification on a single 11 GB GPU, with a synthetic-data generator. Adapter: 20 MB. | PEFT · TRL · bitsandbytes |
| 🔥 [**Real-time Fire Detection**](https://github.com/lmtndy/Real-time-fire-detection) | Team course project: fire & smoke detection with YOLOv8n trained on 21.5k images (mAP@50 0.788, 1.9 ms inference per image on a T4). | YOLOv8 · OpenCV |
| 🚗 [**Wrong-direction Vehicle Detection**](https://github.com/lmtndy/detectCarWrongDirection) | Detects and tracks wrong-way vehicles across multiple lanes. | YOLOv11 · SAM · Supervision |
| ⚡ [**SAM 2 → OpenVINO**](https://github.com/lmtndy/sam2_project) | Exports the SAM 2 image encoder and mask decoder to OpenVINO IR for CPU inference. | SAM 2 · OpenVINO |

### 🏭 Industrial work (closed source)
- Real-time detection for fixture / device-presence checks on manufacturing lines; misposition detection that triggers an automatic robot retry
- Upgraded a phone-inspection system to **RF-DETR + Grounding DINO** (open-vocabulary detection)
- AIoT defect detection with **YOLOv7/YOLOv10 + TensorRT** (ESP32 alarms, Telegram alerts); dust/hair detection for a pharmaceutical line with **YOLOX + TensorRT** on **Jetson Orin** (4 Basler cameras)

---

### 🛠️ Tech stack

**LLM & GenAI**
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?logo=langchain&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?logo=huggingface&logoColor=black)
![Qdrant](https://img.shields.io/badge/Qdrant-DC244C)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white)

**Computer Vision & Optimization**
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?logo=pytorch&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?logo=opencv&logoColor=white)
![YOLO](https://img.shields.io/badge/YOLO-111F68)
![TensorRT](https://img.shields.io/badge/TensorRT-76B900?logo=nvidia&logoColor=white)
![ONNX](https://img.shields.io/badge/ONNX-005CED?logo=onnx&logoColor=white)
![OpenVINO](https://img.shields.io/badge/OpenVINO-0071C5?logo=intel&logoColor=white)

**Edge, Backend & Tools**
![NVIDIA Jetson](https://img.shields.io/badge/NVIDIA%20Jetson-76B900?logo=nvidia&logoColor=white)
![ESP32](https://img.shields.io/badge/ESP32-E7352C?logo=espressif&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![C#](https://img.shields.io/badge/C%23-512BD4?logo=dotnet&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?logo=linux&logoColor=black)

---

### 📄 Publications
- V. Tran, **D. Lam**, T. Le. [*VNWoodKnot: A High-Quality Image Dataset for Wood Knot Detection and Classification*](https://www.sciencedirect.com/science/article/pii/S2352340925007619). **Data in Brief**, Elsevier, 2025.
- **T. D. Lam**, T. Le. *A Robust Ensemble Framework for Helmet Usage Classification in Real-World Scenarios*. **CTU Journal of Innovation and Sustainable Development** (in press).

# 🤖 AI Engineer Portfolio

This portfolio features advanced AI/ML projects with production-ready pipelines. It covers everything from LLM integration and model fine-tuning to deploying ML services and validating notebooks with CI workflows.

## 🧠 Highlights
- LLMs with Hugging Face Transformers
- Model training and evaluation notebooks
- MLOps-style workflow testing (nbmake, CI)
- Checkpointing and model lifecycle
- AI deployments with FastAPI & Docker
  

## Project List

## 1. Multilingual Voice Agent for Public Services

### Problem
Citizens struggle to access government info in native languages via digital channels.

### Solution
Build a voice assistant that:
- Converts speech to text using **Whisper**
- Translates using **NLLB (No Language Left Behind)**
- Queries a knowledge base using **RAG with LlamaIndex**
- Speaks answers via **TTS (Bark or Coqui)**
- Deployable via **Twilio Voice** or WhatsApp

### Goals
- Serve local languages like Swahili, Luo, Kikuyu, Somali
- Provide answers about IDs, licenses, schools, etc.
- Log anonymized usage metrics

---

## 2. African News Summarizer and Bias Detector

### Problem
News often contains bias and lacks multilingual accessibility.

### Solution
Train a summarizer + bias detector:
- **Fine-tune T5 or Falcon** on local news corpora
- Build React frontend to enter URLs and summarize
- Use **Hugging Face Transformers + Langchain**

### Goals
- Summarize articles in 3 languages
- Classify for bias type: political, regional, tone
- Suggest counterpoints and sources

---

## 3. Medical Imaging Assistant for Understaffed Clinics

### Problem
Clinics lack radiologists to interpret X-rays and CT scans.

### Solution
Build a diagnostic model using:
- **YOLOv8 + fastai** for object detection
- Train on open datasets (NIH ChestX-ray14, VinDr)
- Deploy via **Streamlit** or **Gradio** interface

### Goals
- Identify common findings (TB, pneumonia, fractures)
- Allow image uploads from mobile
- Generate PDF reports

# 🩺 XAI-CKD  

## Project 1: Explainable AI for Chronic Kidney Disease Prediction (Resource Efficient)  
## Project 2: End-to-End Fine-Tuning of LLMs for CKD Prediction & Prescription (Resource Intensive)  

---

## 📌 Project Summary  
Chronic Kidney Disease (CKD) is a global health challenge and a **"silent killer,"** often progressing without early symptoms.  
This research explores **two complementary approaches** for CKD prediction:  

- **Resource-Efficient:** Traditional ML/DL models perform the prediction, while a lightweight LLM (API or small model) generates natural language explanations.  
- **Resource-Intensive:** End-to-end fine-tuned LLMs perform both prediction and explanation, with potential for AI-assisted prescription generation.  

Both approaches aim to improve **explainability** and **clinician trust** in AI-driven healthcare systems.  

---

## 🎯 Objectives  
- **Predictive Modeling:** Benchmark traditional ML/DL models against fine-tuned LLMs for CKD prediction.  
- **Explainability:** Enable natural language reasoning behind predictions.  
- **Deployment:** Deliver a CKD risk prediction system for healthcare professionals and patients at **Pakistan Kidney Center (PKC), Abbottabad**.  

---

## 🧪 Methodology  

### 🔹 Project 1: Resource Efficient (ML/DL + LLM API for Explanations)  
- Train baseline **ML/DL models** (SVM, Random Forest, ANN, CNN, etc.).  
- Use these models for **prediction**.  
- Pass prediction + features into an **LLM API (e.g., GPT-4, LLaMA-2-7B, etc.)** or a **small local model** to generate **natural language explanations**.  
- Minimal GPU/compute needed.  

📊 **Project 1 Workflow**  
![Resource Efficient Workflow](8a98f927-8a65-41d2-94d2-b3c1626b82ce.png)  

---

### 🔹 Project 2: Resource Intensive (End-to-End LLM)  
- Serialize tabular patient data → natural language strings.  
- Fine-tune LLMs using **PEFT methods (LoRA/QLoRA)**.  
- LLM directly performs **prediction (Yes/No for CKD)** and **explanation** in one step.  
- Extend system to generate **AI-assisted prescription suggestions**, with clinician-in-the-loop validation.  
- Requires **high compute resources** (GPUs, large memory).  

📊 **Project 2 Workflow**  
![Resource Intensive Workflow](7cd7a2b1-d572-456d-be69-854ea6ea5ee3.jpg)  

---

## 📈 Expected Impact  
- **Healthcare:** Early CKD detection → reduced dialysis/transplant cost, improved survival.  
- **AI in Medicine:** Deploy **explainable AI** in real-world practice.  
- **Industry:** Enable **HealthTech startups** and AI-driven healthcare innovation in Pakistan.  
- **Policy & Development (KPK):** Strengthen healthcare infrastructure and foster AI adoption.  

---

## 🤝 Collaborators  
- **Pakistan Kidney Center (PKC), Abbottabad, KPK, Pakistan**  
- **PAF-IAST Research Team**  

---

## 📌 Research Interest  
My focus is on **Explainability in Medical AI**.  
- **Project 1:** Efficient approach → doctors get **ML/DL predictions + LLM explanations**.  
- **Project 2:** Cutting-edge approach → doctors get **LLM-driven predictions, reasoning, and prescriptions**.  

---

## 🔮 Future Vision  
AI-assisted prescription generation with **LLM reasoning** to support doctors in making faster, evidence-based, and explainable decisions.  

📷 **AI-assisted Prescription Vision**  
![Prescription Workflow](8a98f927-8a65-41d2-94d2-b3c1626b82ce.png)  

---

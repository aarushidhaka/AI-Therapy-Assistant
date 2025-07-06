# AI-Therapy-Assistant
This project develops an AI-powered therapy assistant to detect academic stress and provide empathetic support to university students. Leveraging advanced NLP techniques like DistilBERT fine-tuning, Low-Rank Adaptation (LoRA), and prompt engineering, the system classifies emotions and risk levels while adhering to clinical safety protocols.

# 🤖 AI Therapy Assistant – Generative AI Project

This project develops an **AI-powered therapy assistant** to detect academic stress and provide empathetic support to university students. Leveraging advanced NLP techniques like **DistilBERT fine-tuning**, **Low-Rank Adaptation (LoRA)**, and **prompt engineering**, the system classifies emotions and risk levels while adhering to clinical safety protocols.  

It includes **human-in-the-loop mechanisms** and Warwick-specific wellbeing resources to ensure responsible deployment in academic environments.  

---

## 📂 Repository Contents

| File                                | Description                                                                                 |
|-------------------------------------|---------------------------------------------------------------------------------------------|
| `Group_8_Narrative&Code.ipynb`     | Jupyter Notebook containing the implementation of emotion classification, LoRA, and prompts.|
| `Group_8_One_Pager.pdf`            | A one-page project summary detailing objectives, methodology, and key outcomes.             |

---

## 📊 Project Overview

- **Objective**: Build an AI system to classify academic stress, detect high-risk scenarios, and generate supportive responses.  
- **Key Features**:
  - Fine-tuned **DistilBERT** for emotion and risk classification (79% accuracy).  
  - Designed 12 emotion-specific prompts for **FLAN-T5** to deliver dynamic, empathetic replies.  
  - Reduced GPU memory usage by **40%** via **LoRA** without compromising performance.  
  - Embedded safety measures like regex filters, response constraints, and clinician override.  

---

## 🛠️ Core Techniques
- **NLP Models**: DistilBERT, DeBERTa, FLAN-T5  
- **Techniques**: LoRA fine-tuning, Prompt Engineering, Human-in-the-Loop  
- **Evaluation**: Confusion matrices, F1-scores (Emotion detection F1: 0.74)  

---

## 📁 File Descriptions

### `Group_8_Narrative&Code.ipynb`
- Implements the AI pipeline including:
  - Dataset preprocessing
  - Model fine-tuning (DistilBERT + LoRA)
  - Risk classification and dynamic prompt responses  
  - Evaluation metrics and confusion matrices  

---

### `Group_8_One_Pager.pdf`
- Concise summary of the project:
  - Objective, methodology, and key innovations  
  - Core techniques like LoRA and prompt constraints  
  - Evaluation highlights (79% classification accuracy, 74% F1-score)  

---

### `Group_8_Video_Presentation.MP4`
- Explains system design, human-in-the-loop integration, and future scope.  
- Useful for stakeholders and non-technical audiences.  

---

## 🚀 How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/<yourusername>/AI-Therapy-Assistant.git
   cd AI-Therapy-Assistant
2. Open Group_8_Narrative&Code.ipynb in Jupyter Notebook.
3. Install dependencies from requirements.txt (if provided).
4. Run all cells to reproduce results.

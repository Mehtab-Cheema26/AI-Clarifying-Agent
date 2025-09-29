# 🤖 AI Clarifying Agent  

![Python](https://img.shields.io/badge/Python-3.10-blue.svg)  
![PyTorch](https://img.shields.io/badge/PyTorch-2.2-red.svg)  
![HuggingFace](https://img.shields.io/badge/🤗-Transformers-orange.svg)  
![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)  
![Status](https://img.shields.io/badge/Status-Research--Prototype-yellow.svg)  

**Jan 2025 – Apr 2025 | Python, Pandas, Hugging Face, PyTorch, Feature Engineering**  

An open-source conversational AI pipeline (with support from **The Linux Foundation**) that **detects ambiguity, intent, and sentiment in user queries** and decides whether to ask clarifying questions before responding. This makes AI interactions more **empathetic, agentic, and human-like**—bridging the gap between passive answering and active collaboration.  

---

## 🌟 Motivation  

Most AI systems (e.g., ChatGPT) default to verbose answers instead of asking clarifying questions. Humans, however, refine conversations by probing, clarifying, and adapting. Our project reimagines dialogue by giving AI the ability to:  

- Detect when a query is **ambiguous**  
- Ask meaningful **clarifying questions**  
- Adapt responses once ambiguity is resolved  
- Incorporate **sentiment** and **intent** for empathetic communication  

---

## 🛠️ Key Features  

- **Ambiguity Detection** → Random Forest with TF-IDF, engineered features, and synthetic datasets  
- **Intent Classification** → Linear SVC to determine the user’s goal  
- **Sentiment Analysis** → Fine-tuned DistilBERT, achieving **0.92 F1-score** with hyperparameter optimization  
- **Dynamic Response Pipeline** → Chooses when to clarify vs. when to answer directly  
- **Dataset Contribution** → High-quality clarifying questions (synthetic + human-validated)  

---

## 🎤 Presentation  

We presented this project at **AI Tinkerers (March 2025)**, hosted at **Mozilla**, in front of hundreds of AI researchers and builders.  

📖 [Read the full story on LinkedIn](https://www.linkedin.com/posts/cheemamehtab_this-week-i-got-to-present-in-front-of-hundreds-activity-7311956497075171329-YQHp?utm_source=share&utm_medium=member_desktop&rcm=ACoAADWvPAYBia9EIQpf-IpuikruuKJGmPoxiCU)  

---

## 🚀 Demo Walkthrough  

🎥 **Watch the full demo video here:** [![Demo Video](https://img.youtube.com/vi/j8gUzAow5j8/maxresdefault.jpg)](https://youtu.be/j8gUzAow5j8)

---

## 📄 Research Paper  

Read the full paper here → [View of Building an Emphatic AI Coach & Agent](https://jps.library.utoronto.ca/index.php/mcsjournal/article/view/45679) 

---

## 🔮 Impact  

- **Conversational AI** → More natural, human-like interactions  
- **AI Alignment** → Safer, steerable models that clarify instead of hallucinate  
- **Instruction Tuning** → Data and methods that improve model adaptability  

---

## ⚙️ Tech Stack  

- **Python, Pandas, scikit-learn**  
- **PyTorch, Hugging Face (Transformers, Datasets)**  
- **Random Forest, Linear SVC, DistilBERT**  
- **Feature Engineering & Synthetic Data**  

---

## 📌 Citation  

If you use this work in research, please cite:  


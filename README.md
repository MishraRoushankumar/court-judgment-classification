# ⚖️ Court Judgment Classification (Capstone – IIT Indore)

## 📌 Project Overview
This project applies **Natural Language Processing (NLP)** and **Machine Learning** to classify Indian court judgments.  
It is developed as part of the **IIT Indore Certification Capstone Project (Aug 2025 – Aug 2026)**.  

---

## 📂 Repository Structure
court-judgment-classification/
│── data/ # Raw and processed datasets (ignored in Git)
│── notebooks/ # Jupyter notebooks for EDA & experiments
│── src/ # Python scripts for modular code
│── app/ # Deployment (Streamlit/Flask)
│── models/ # Trained models (ignored in Git)
│── requirements.txt # Project dependencies
│── README.md # Project documentation

## 📊 Dataset
- Source: Indian court judgment PDFs (~7.21 GB)  
- Type: Text-based PDFs  
- Preprocessing: Text extraction (`pdfplumber`), cleaning, labeling

## 💻 Installation & Setup
1. Clone the repo:
```bash
git clone https://github.com/mishraroushankumar/court-judgment-classification.git
cd court-judgment-classification

# ⚖️ Court Judgment Classification (Capstone – IIT Indore)

## 📌 Project Overview

This project applies **Natural Language Processing (NLP)** and **Machine Learning** to classify Indian court judgments.  
It is a **Capstone Project** developed as part of the **IIT INDORE** - **DRISHTI CPS Data Science** and **Machine Learning** Certification Program .  

---

## 📂 Repository Structure

```bash
court-judgment-classification/
├── app/                # Deployment code (e.g., Streamlit, Flask)
├── data/               # Raw and processed datasets (ignored by Git)
│     ├── raw/
│     └──processed/
├── models/             # Trained models and artifacts (ignored by Git)
├── notebooks/          # Jupyter notebooks for EDA and experiments
├── src/                # Source code for the project
├── requirements.txt    # List of project dependencies
└── README.md           # Project documentation (this file)
```

## 📊 Dataset

- Source: **Legal Dataset: SC Judgments India (1950–2024)** (`Kaggle`)
- Type: Text-based PDFs  
- Preprocessing: Text extraction (`pdfplumber`), cleaning, labeling

## 💻 Installation & Setup

1. Clone the repo:

```bash
git clone https://github.com/mishraroushankumar/court-judgment-classification.git
cd court-judgment-classification
```

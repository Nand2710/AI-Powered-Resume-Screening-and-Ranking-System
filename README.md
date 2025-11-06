# 🧠 AI Resume Ranking System
[![Streamlit App](https://img.shields.io/badge/Streamlit-App-blue)](https://ai-powered-resume-screening-and-ranking-system-aoondnlkbk5sigu.streamlit.app/)
[![Python](https://img.shields.io/badge/Python-3.8+-yellow.svg)](https://www.python.org/)

## 📘 Overview

The **AI Resume Ranking System** is an intelligent, automated tool built to streamline the recruitment process by leveraging **Natural Language Processing (NLP)** and **Machine Learning**.  
It scans resumes, extracts relevant information, and ranks candidates based on how closely their skills match the provided job description.

This project is designed to help HR professionals and recruiters save time and identify top candidates efficiently.

---

## 🚀 Features

- 🔍 **Automated Resume Screening** – Extracts and identifies important skills, experiences, and qualifications.  
- 📊 **AI-Based Ranking System** – Ranks candidates according to job description relevance.  
- 💻 **Interactive Interface** – Simple and intuitive **Streamlit** web app for uploading resumes and job descriptions.  
- ⚙️ **NLP-Powered Matching** – Uses text similarity and keyword extraction for accurate matching.

---

## 🧩 Tech Stack

- **Frontend**: Streamlit  
- **Backend**: Python  
- **Libraries**: 
  - `scikit-learn` (Machine Learning)
  - `spaCy` / `NLTK` (Natural Language Processing)
  - `PyPDF2` / `pdfminer.six` (Resume text extraction)
  - `pandas`, `numpy` (Data handling)
- **Deployment**: Streamlit Cloud

---

## 🖼️ Screenshots

| Upload Job Description and Resume | Uploaded Resume(s) | Ranked Results |
|------------------------|------------------|----------------|
| ![Job Description](https://github.com/Nand2710/AI-Powered-Resume-Screening-and-Ranking-System/blob/main/Images/Upload%20Job%20Description%20and%20Resume.PNG) | ![Resume Upload](https://github.com/Nand2710/AI-Powered-Resume-Screening-and-Ranking-System/blob/main/Images/Uploaded%20Job%20Description%20and%20Resume.PNG) | ![Results](https://github.com/Nand2710/AI-Powered-Resume-Screening-and-Ranking-System/blob/main/Images/Ranked%20Results.PNG) |

---
## ⚙️ Installation

## Installation

1. Clone the repository:
   ```bash  
   git clone https://github.com/your-username/Intelligent-Healthcare-Assistant.git
   cd Intelligent-Healthcare-Assistant  
   
2. Install Dependencies:
   ```bash
    pip install -r requirements.txt  
   
3. Run the Application:
   ```bash
   streamlit run app.py
 ---
## 💡 Usage

1. Upload multiple resumes (PDF format).
2. Enter or paste a job description in the provided text area.
3. Click "Rank Candidates" to generate ranking results.
4. View a ranked list of candidates based on their skill-job match score.
---
## 🔮 Future Enhancements

- 🧩 Continuous Learning: Implement feedback loops to improve model accuracy over time.
- 🧠 Bias Mitigation: Integrate fairness algorithms to reduce hiring bias.
- ☁️ Database Integration: Store candidate profiles for future comparison and analytics.
- 🧾 Comprehensive Reporting: Generate downloadable analytics reports in PDF/CSV format.
---

## 🤝 Contributing

Contributions are always welcome!
If you'd like to improve this project:
  1. Fork the repo
  2. Create a new branch (feature/your-feature)
  3. Commit your changes
  4. Submit a pull request with a detailed description of improvements

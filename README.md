# 🧠 AI Resume Screening Tool

An NLP-powered resume screening web application that ranks candidates based on job description similarity.

## 🚀 Features

- Upload multiple resumes (PDF)
- Extract text using NLP
- Extract key skills
- Compare resumes with job description
- Rank candidates by similarity score
- Clean Streamlit UI

## 🛠 Tech Stack

- Python
- spaCy (NLP)
- scikit-learn (TF-IDF + Similarity)
- pandas
- PyPDF
- Streamlit

## 📂 Project Structure

```
ai-resume-screening/
│
├── app.py
├── utils.py
├── requirements.txt
├── README.md
├── .gitignore
├── resumes/
└── venv/
```

## ⚙️ Installation

1. Clone the repository:

```
git clone https://github.com/mruthyunjayar07/ai-resume-screening.git
cd ai-resume-screening
```

2. Create virtual environment:

```
python -m venv venv
venv\Scripts\activate
```

3. Install dependencies:

```
pip install -r requirements.txt
python -m spacy download en_core_web_sm
```

4. Run the app:

```
streamlit run app.py
```

## 🎯 How It Works

1. Extract text from uploaded resumes
2. Preprocess text using spaCy
3. Convert text to TF-IDF vectors
4. Compute cosine similarity
5. Rank candidates

## 📊 Future Improvements

- Skill-based weighting
- Experience-based ranking
- Deploy on Streamlit Cloud
- Add database storage
- Add authentication

---

⭐ If you found this project useful, give it a star!
# 🧠 AI-Powered Resume Screening & Candidate Ranking System

## 🚀 Project Overview

This project builds an AI-powered Resume Screening and Candidate Ranking System using Natural Language Processing (NLP) and Machine Learning techniques.

The system automatically:
- analyzes resumes
- compares resumes with job descriptions
- ranks candidates based on relevance
- extracts important skills
- identifies missing skills

This simulates a real-world Applicant Tracking System (ATS) used in recruitment and HR operations.

---

## 🎯 Problem Statement

Companies receive hundreds of resumes for job openings. 
Manual resume screening is time-consuming and inefficient.

The goal of this project is to automate the resume screening process using AI and NLP techniques to improve hiring efficiency and candidate shortlisting.

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- NLP Techniques
- Jupyter Notebook

---

## 📂 Dataset

The dataset contains:
- Candidate resumes
- Job categories
- Resume text data

Dataset used:
Resume Screening Dataset

---

## ⚙️ Project Workflow

### 1. Data Loading
- Loaded resume dataset using Pandas

### 2. Text Cleaning
- Lowercasing
- Removing special characters
- Removing unnecessary spaces

### 3. Job Description Creation
Created a sample job description for candidate matching.

### 4. Feature Extraction
Used TF-IDF vectorization to convert resume text into numerical vectors.

### 5. Resume Matching
Used Cosine Similarity to compare resumes with job descriptions and generate match scores.

### 6. Candidate Ranking
Ranked candidates based on resume-job similarity scores.

### 7. Skill Extraction
Extracted technical skills from resumes automatically.

### 8. Skill Gap Analysis
Identified missing skills compared to required job skills.

### 9. Visualization
Created graphs for:
- Candidate match scores
- Most common skills

---

## 📊 Key Features

✅ Resume-job matching  
✅ Candidate ranking system  
✅ Skill extraction  
✅ Missing skill analysis  
✅ ATS-style AI workflow  
✅ Data visualization dashboard  

---

## 📈 Sample Output

| Category | Match Score |
|---|---|
| Data Science | 38.89% |
| Python Developer | 35.12% |
| Java Developer | 28.45% |

---

## 💡 Business Impact

This system can help organizations:
- automate resume screening
- reduce recruiter workload
- improve candidate shortlisting
- speed up hiring processes
- identify skill gaps quickly

---

## ⚠️ Limitations

- Keyword-based skill extraction
- Limited job description size
- Does not analyze soft skills

---

## 🚀 Future Improvements

- Use advanced NLP models like BERT
- Add resume PDF parsing
- Build web application deployment
- Add real-time recruiter dashboard

---

## 🏁 Conclusion

This project successfully demonstrates how AI and NLP can automate recruitment workflows through intelligent resume screening and candidate ranking systems.

It highlights practical applications of Machine Learning in HR technology and recruitment automation.

---

## 🙌 Acknowledgment

This project was completed as part of the Machine Learning Internship by Future Interns.

---

## 🔗 GitHub Repository

(Add your repository link here)

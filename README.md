# 🧠 Resume Shortlisting System

A smart, AI-powered web application to automate and optimize the process of resume screening. Built using **Flask** and **NLP techniques**, this tool compares job descriptions with uploaded resumes to identify the most relevant candidates using **TF-IDF** and **cosine similarity**.

---

## 🚀 Key Features

- 📄 **Upload Multiple Resumes**  
  Supports `.pdf`, `.docx`, and `.txt` formats.

- 🧾 **Job Description Matching**  
  Paste a job description and get similarity scores for each resume.

- 📊 **Top 5 Resume Recommendations**  
  Automatically ranks and displays the top matches with relevance scores.

- 🎯 **Matching Accuracy**  
  Calculates overall accuracy based on a configurable similarity threshold.

- 🖥️ **User-Friendly Web Interface**  
  Built using `Flask` and `Jinja2` templates for a smooth user experience.

---

## 🛠️ Technologies Used

- **Backend:** Python 3.10+, Flask  
- **Text Extraction:** PyPDF2, docx2txt  
- **NLP & ML:** Scikit-learn (TF-IDF, cosine similarity), NumPy  
- **Frontend:** HTML + Jinja2  
- **File Handling:** Upload & temporary storage via `uploads/`

---

## 🧪 How It Works

1. Upload one or more resumes through the web interface.
2. Enter a job description in the provided text field.
3. The system extracts and vectorizes all text using **TF-IDF**.
4. Computes **cosine similarity** between each resume and the job description.
5. Displays the **top 5 matched resumes** and an overall **accuracy** score.

---

## 📁 Project Structure


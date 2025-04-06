# ATS Resume Expert 💼

An intelligent web app that evaluates a candidate’s resume against a job description using **Google Gemini Pro Vision API** and **Streamlit**. This tool mimics both a **Technical HR** reviewer and an **ATS (Applicant Tracking System)** to give insightful feedback and a matching percentage.

---

## 🔧 Features

- 📄 Upload a resume (PDF format)
- 📝 Paste job description
- 🤖 Get HR-style professional feedback
- 📊 Get ATS-style percentage match with keyword analysis

---

## 🧐 Tech Stack

- **Python**
- **Streamlit**
- **Google Gemini Pro Vision API**
- **pdf2image**
- **Pillow (PIL)**
- **dotenv**

---

## 📁 Project Structure

```
🔺 ATS-Resume-Expert/
├── app.py                 # Main Streamlit app
├── .env                   # API key environment file
├── requirements.txt       # Python dependencies
└── README.md              # Project documentation
```

---

## 🛠️ Installation Instructions

### 1. Clone the repository
```bash
git clone https://github.com/your-username/ats-resume-expert.git
cd ats-resume-expert
```

### 2. Set up a virtual environment (optional)
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

### 3. Install dependencies
```bash
pip install -r requirements.txt
```

### 4. Set your API key

Create a `.env` file in the root directory and add your Google API key:

```
GOOGLE_API_KEY=your_google_gemini_api_key_here
```

---

## 🚀 How to Run

```bash
streamlit run app.py
```

---

## ✅ How to Use

1. **Paste the job description** in the text area.
2. **Upload your resume (PDF format)**.
3. Choose an option:
   - 🔍 **Tell Me About the Resume**: Get a detailed HR review.
   - 📈 **Percentage Match**: See the matching score, missing keywords, and final thoughts.

---

## ⚠️ Notes

- Only the **first page of the resume** is analyzed.
- Ensure the `.env` file is **not shared publicly**.
- Designed for educational and personal use.

---

## 📦 Example `requirements.txt`

```txt
streamlit
python-dotenv
pdf2image
Pillow
google-generativeai
```

---

## 📨 Contact

Made by **Vishva Patel**


## 📄 License

This project is licensed under the **MIT License**.


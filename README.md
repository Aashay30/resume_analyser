# 🚀 AI Resume Analyzer  

An **AI-powered microSaaS solution** designed to simplify the hiring process by analyzing resumes, extracting key details, and providing actionable insights. This tool is perfect for job seekers to improve their resumes and for HR professionals to streamline candidate evaluations.

---

## 📜 Project Description  

The **AI Resume Analyzer** leverages **Named Entity Recognition (NER)** and machine learning to:  
- 📝 Extract key information such as name, email, phone number, skills, and experience level from resumes.  
- 📈 Provide recommendations for missing skills, certifications, and courses.  
- ⭐ Generate a resume score to assess the overall quality of the document.  
- 🎥 Offer video tutorials and tips for resume improvement.  

This tool addresses challenges faced by job seekers in creating impactful resumes and recruiters in evaluating numerous applications. It’s simple, efficient, and tailored for niche use cases like self-assessment and automated candidate screening.  

---

## 🌟 Features Overview  

### 👤 User Features:  
1. **Resume Upload**:  
   - 📂 Upload resumes (PDF format) with multi-page support.  
   - 🔍 View resumes within an interactive PDF viewer.  

2. **Resume Analysis**:  
   - Extracts:  
     - 👤 Name  
     - 📧 Email Address  
     - 📱 Phone Number  
     - 📄 Number of Pages  
   - Identifies:  
     - 🛠️ Skills mentioned in the resume.  
     - ⚡ Missing skills (with recommendations).  
   - Predicts the user's **experience level** (Beginner, Intermediate, Advanced).  
   - Determines the **target job role** based on keywords in the resume.  
   - Provides a **Resume Score** and **customized suggestions**.  

3. **Recommendations**:  
   - Suggests:  
     - 🔧 Skills to add.  
     - 🎓 Certifications and courses (customizable by the user).  
     - 🎥 Video resources for improvement.  

### 🛠️ Admin Features:  
1. **Dashboard**:  
   - 📊 View all uploaded resumes and their analyses.  
   - 📈 Monitor user statistics (e.g., resumes uploaded, extracted skills).  
   - 📥 Download detailed reports for further evaluation.  

2. **Database Integration**:  
   - 💾 Stores extracted data in an **SQL database**.  
   - 📤 Supports exporting data for further analysis.  

---

## ⚙️ Setup Instructions  

### 📋 Prerequisites:  
- **Programming Language**: Python (with Flask or Django for web backend).  
- **Frontend**: HTML/CSS/JavaScript.  
- **Database**: SQLite or MySQL.  
- **Libraries/Frameworks**:  
  - 🤖 `spaCy` or `transformers` for NER.  
  - 🌐 `Flask` or `Django` for backend API.  
  - 📄 `pdfplumber` or `PyPDF2` for PDF parsing.  
  - 🗃️ `SQLAlchemy` for database interactions.  

### 🛠️ Steps to Run the Project:  
1. Clone the repository:  
   ```bash
   git clone https://github.com/Aashay30/ai-resume-analyzer.git
   cd ai-resume-analyzer
2. Install required dependencies:
      ```bash
   pip install -r requirements.txt

3. Set up the database:
      ```bash
   python manage.py migrate

4. Run the server:
      ```bash
   python manage.py runserver

5. Open the app in your browser at http://127.0.0.1:8000.

## 🖼️ Screenshots  

### 🧑‍💻 User Interface:  
- **Resume Upload Screen**:  
  ![📂 Resume Upload Screen](https://github.com/Aashay30/resume_analyser/blob/main/sc1.png)  

### 🛠️ Admin Dashboard:  
- **Dashboard Overview**:  
  ![📈 Admin Dashboard](https://github.com/Aashay30/resume_analyser/blob/main/sc2.png)  

## 💡 Evaluation  

This project fulfills the MicroSaaS requirements by:  
- 🧩 **Solving a niche problem**: Resume analysis and improvement.  
- 🤖 **Implementing a clear and functional AI-based solution**: Efficiently extracts and analyzes resume data.  
- 📚 **Providing comprehensive documentation**: Guides both users and developers effectively.  
- 💡 **Ensuring feasibility for a one-person startup**: Built using lightweight frameworks and tools.  


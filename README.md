# DOX AI

> **AI-Powered Resume Analyzer & Builder**

<p align="center">
  <img src="assets/doxai-logo.svg" alt="DOX AI Logo" width="220"/>
</p>

## 🚀 Overview

**DOX AI** is a modern, AI-powered web application for resume analysis, building, and career insights. Featuring a bold yellow/white/black theme, DOX AI helps you create, analyze, and optimize your resume with advanced AI, interactive UI, and actionable feedback.

This project is a complete redesign and reimplementation, with all features, UI, and logic built from scratch for a seamless, user-friendly experience.

---

## ✨ Features

- **AI Resume Analyzer:**
  - Get instant, detailed feedback on your resume using advanced AI models.
  - ATS compatibility, keyword gap, and section analysis.
- **Smart Resume Builder:**
  - Build a professional resume from scratch with modern templates.
  - Guided forms for personal info, experience, education, skills, and more.
- **Job Search:**
  - Discover job opportunities and get personalized recommendations.
- **Career Insights & Analytics:**
  - Visualize your resume's strengths, weaknesses, and improvement areas.
- **Feedback System:**
  - Share your experience and help improve DOX AI.
- **Modern UI:**
  - Clean, responsive, and accessible design with a yellow/white/black color scheme.

---

## 🖥️ Screenshots

![Screenshot](https://user-images.githubusercontent.com/202119875/placeholder.png)

---

## 🛠️ Setup & Installation

### 1. Clone the repository
   ```bash
git clone https://github.com/anskp/DOX-AI
cd DOX-AI
   ```

### 2. Create a Virtual Environment (Optional)
Set up a virtual environment to manage dependencies:
```bash
python -m venv venv
```

#### Activate the Virtual Environment:
- **Windows:**
  ```bash
  venv\Scripts\activate
  ```
- **MacOS & Linux:**
  ```bash
  source venv/bin/activate
  ```

### 3. Install dependencies
Install the required Python packages:
   ```bash
   pip install -r requirements.txt
   ```

### 4. Download the spaCy model
Ensure that the necessary NLP model is installed:
   ```bash
   python -m spacy download en_core_web_sm
   ```
   
🎉 **Congratulations 🥳😱 your set-up 👆 and installation is finished 🥳😱**

### 5. Configure Environment Variables (Mandatory for AI-Analyzer Functionality)
To enable access to the Gemini API used by the AI Resume Analyzer, you need to set up environment variables securely.

#### ✅ Step-by-Step:
1. Create a `.env` file inside the `utils/` directory.
2. Paste your Google Gemini API key in the following format:

```env
GOOGLE_API_KEY=your_google_gemini_api_key
```

> Get your Gemini API Key: Visit [Google AI Studio – Gemini API Access](https://aistudio.google.com/app/apikey) 👉 Grab and use your own API key — Since Mine One Have Usage Limits.

### 6. Run the application
Start the application using Streamlit:
   ```bash
   streamlit run app.py
   ```

---

## 📁 Folder Structure After Adding `.env`

(Insert folder structure tree here)

---

## 🔐 Admin Login Credentials

**Username:**
```
admin@example.com
```
**Password:**
```
admin123
```

---

## 🙋‍♂️ About the Author

Created and maintained by [ANAS KP (anskp)](https://github.com/anskp)

---

## 📄 License

This project is licensed under the MIT License.

---

## ⭐️ Star this repo if you like it!

# Resume ATS Checker 📄🤖

![Application Screenshot](https://github.com/user-attachments/assets/f915239c-efa0-40dd-967d-d72fc0506ca0)

## Overview 🔎

Many companies use **Applicant Tracking Systems (ATS)** to filter resumes before they are reviewed by recruiters. As a result, a large proportion of applications are automatically rejected due to formatting issues or missing keywords.

**Resume ATS Checker** analyzes resumes using an AI model to simulate how an ATS system evaluates applications and provides actionable feedback to improve resume quality.

This project helps users understand how their resume may be interpreted by automated screening systems and how to improve it.

---

## Features 🚀

* 📊 **ATS-style resume analysis**
* 💡 **AI-powered feedback and suggestions**
* 📈 **Resume optimization guidance**
* 💬 **Interactive chat interface for personalized advice**

---

## Tech Stack 🛠️

* **Frontend:** Streamlit
* **AI Model:** Google Gemini 3 Flash ⚡
* **PDF Processing:** PyPDF2 📑

---

## Improvements in This Version 🔧

This repository includes several fixes and improvements compared to the original implementation:

* ✔️ Fixed the **incorrect run command** in the original `README.md`.
* ⚡ Updated the AI model to **Gemini 3 Flash**, providing faster responses and improved analysis accuracy.
* 🐞 Fixed a bug that prevented the application from running by **adding missing dependencies to `requirements.txt`**.

---

## Installation 💻

Clone the repository:

```bash
git clone https://github.com/lucaterpirla/Resume-ATS-Check.git
cd Resume-ATS-Check
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Edit the `.env` file and add your **Google API key**:

```bash
GOOGLE_API_KEY="your_api_key_here"
```

---

## Running the Application ▶️

Start the Streamlit app:

```bash
streamlit run resumeATS.py
```

The application will open automatically in your browser.

---

## Project Origin 📚

This repository is based on the original project:

**Advanced-ATS-Resume-Checker**

Additional fixes and improvements have been implemented to ensure correct execution and updated AI capabilities.

---

## License 📜

This project is released under the **MIT License**. See the `LICENSE` file for details.

---

## Contact 📬

For questions, suggestions, or improvements, please open an **Issue** in this repository.

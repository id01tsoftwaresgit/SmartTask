# SmartTask AI Assistant
**Version 1.0.0**
Author: Guillaume Lessard, iD01t Softwares
Website: https://www.id01t.ca
License: MIT

---

## 🚀 Overview
SmartTask AI Assistant is a **premium AI-powered productivity suite** designed to streamline your workflow.
It integrates **task management, document generation, file analysis, and email/calendar tools** – all in one sleek desktop app.

---

## ✨ Features
- Natural Language Command Bar
- File Analysis (TXT, PDF, DOCX, CSV)
- Smart Content Generation (reports, slides, spreadsheets, code)
- Task Manager with reminders (SQLite backend)
- Email draft assistant (Gmail/Outlook APIs)
- Export to PDF, DOCX, Markdown
- Dark/Light Mode
- Multi-LLM API support (OpenAI, Claude, Gemini)

---

## 📦 Installation
1.  Navigate into the project directory:
    ```bash
    cd smarttask-ai
    ```
2.  Run the application:
    ```bash
    python smarttask_ai.py
    ```
    The script will automatically check for and install any missing dependencies on the first run.

3.  To build a standalone executable:
    ```bash
    pyinstaller --onefile --noconsole --icon=icon.ico smarttask_ai.py
    ```

---

## 🔑 API Keys

SmartTask AI requires user-provided API keys. Go to the **Settings** tab in the application to add your keys for:

*   OpenAI
*   Claude
*   Gemini
*   A Custom LLM endpoint

---

## 💰 Monetization

*   **Free Plan**: 20 queries/month (using your own API key).
*   **Pro Plan**: Unlimited queries.
*   Unlock the Pro Plan by purchasing a license via the **Ko-fi** or **Gumroad** buttons in the app's Settings tab.

---

## 📩 Support

*   Website: [https://www.id01t.ca](https://www.id01t.ca)
*   Email: [itechinfomtl@gmail.com](mailto:itechinfomtl@gmail.com)

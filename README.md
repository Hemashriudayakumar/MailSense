# 📧 MailSense - Automated Email Summarization System

MailSense is an AI-powered tool that automatically extracts email content from Excel files (uploaded via UiPath automation to Google Drive), preprocesses the data, summarizes it using a fine-tuned **BART** model, and provides a clean, easy-to-read report.

---

## 🚀 Features
- **UiPath Automation Integration** – Extracts emails from a mailbox and saves them as Excel files in Google Drive.
- **Google Drive Fetch** – Downloads the Excel file automatically to the backend for processing.
- **Data Preprocessing** – Cleans, formats, and structures the email body content.
- **AI Summarization** – Uses a fine-tuned **BART Transformer** model to summarize long email text.
- **Export to PDF** – Generates a summarized PDF report for easy sharing.
- **Simple Web Frontend** – View summaries directly in a clean, user-friendly dashboard.

---

## 📂 Project Structure
mailsense/
├── backend/
│ ├── main.py # Main FastAPI backend server
│ ├── drive_service.py # Google Drive integration
│ ├── preprocess.py # Data cleaning & preprocessing
│ ├── summarize.py # BART model summarization logic
│ ├── pdf_export.py # PDF export functionality
│ ├── requirements.txt # Python dependencies
│
├── frontend/
│ ├── index.html # Web UI
│ ├── style.css # Styling for frontend
│ ├── script.js # API integration with backend

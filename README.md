# Gemini AI Assistant – Desktop Automation Tool

A professional **Python desktop application** built with **Tkinter** that integrates **Google Gemini AI** to automatically generate structured answers from **Word (.docx) question files**.

Designed for **students, finance professionals, researchers, and educators** who need reliable, resumable, and well-formatted AI-generated content.

---

## Table of Contents

- Overview  
- Key Features  
- Application Workflow  
- Input & Output Specification  
- Installation  
- Configuration  
- Supported AI Models  
- Stop & Resume Mechanism  
- Security & Privacy  
- Use Cases  
- Technology Stack  
- Roadmap  
- Developer  
- License  
- Contributions  

---

## Overview

Gemini AI Assistant is a **desktop-based AI automation tool** that reads questions from Microsoft Word documents and generates clear, exam-oriented or explanatory answers using **Google Gemini models**.

Unlike browser-based AI tools, this application:
- Runs completely on your local system  
- Supports long-running batch processing  
- Allows stopping and resuming without data loss  
- Produces professionally formatted Word documents  

---

## Key Features

- Google Gemini AI integration  
- Word (.docx) input and output support  
- Batch question processing  
- Start / Stop / Resume execution  
- Smart resume from last completed item  
- Adjustable creativity (temperature control)  
- Time & token usage estimation  
- Progress tracking with live logs  
- Secure API key handling  
- Clean, structured answer formatting  

---

## Application Workflow

1. Enter Google Gemini API key  
2. Select Gemini model and creativity level  
3. Upload Word file containing questions  
4. (Optional) Estimate time and usage  
5. Start processing  
6. Stop anytime and resume later  
7. Receive finalized Word document with answers  

---

## Input & Output Specification

### Input
- File type: `.docx`  
- Each paragraph is treated as one question  

### Output
- Auto-generated file:
  ```
  <input_filename>_Gemini_Answer.docx
  ```
- Output includes:
  - Question headings  
  - Bullet-point answers  
  - Bolded key terms  
  - Resume-safe formatting  

---

## Installation

### Option 1: Windows EXE (Recommended)

1. Go to the **GitHub Releases** page  
2. Download the latest `Gemini-AI-Assistant.exe`  
3. Run the EXE — no Python installation required 

---

### Option 2: Run from Source (Developers)
```bash
git clone https://github.com/Tamil-Venthan/gemini-ai-assistant.git
cd gemini-ai-assistant
pip install google-generativeai python-docx
python gemini_bot.py
```
> Note: `tkinter` is bundled with standard Python installations on Windows.

---
## Windows EXE Release

- Standalone Windows executable
- No Python dependency required
- Distributed via GitHub Releases
- Built for easy installation and updates
---
## Auto Update & Manual Update Check
### 🔄 Auto Update

- The application automatically checks for updates on startup
- If a newer version is available:
- User is notified
- Update can be downloaded and applied safely

### 🔍 Manual Update Check

- Users can manually trigger update checks from within the app
- Ensures users always stay on the latest stable version
- Updates are fetched securely from the official GitHub repository only.

## Configuration

### Obtain Google Gemini API Key

1. Visit: https://aistudio.google.com/app/apikey  
2. Generate a new API key  
3. Paste the key into the application’s **Google API Key** field  

The API key is **never stored locally**.

---

## Supported AI Models

- `models/gemini-flash-latest` (Recommended)  
- `models/gemini-2.0-flash`  
- `models/gemini-1.5-flash`  
- `models/gemini-1.5-pro`  

---

## Stop & Resume Mechanism

- Processing progress is saved automatically  
- Application detects previously completed questions  
- Restarting resumes from the last processed item  
- Prevents token wastage and repeated work  

---

## Security & Privacy

- API keys are not persisted  
- No user files are uploaded or shared  
- Only question text is sent to Gemini API  
- All generated documents remain local  

---

## Use Cases

- Exam preparation  
- Academic note generation  
- Interview question answering  
- Research documentation  
- AI-driven document automation  
- Bulk Q&A processing  

---

## Technology Stack

- Python  
- Tkinter (GUI framework)  
- Google Gemini AI  
- python-docx  
- Multithreading  

---

## Roadmap

- PDF export support  
- Token cost calculator  
- Markdown & TXT input support  
- Dark mode UI  
- Windows EXE installer  
- Plugin-based prompt templates  

---

## Developer

**Tamil Venthan**   

- LinkedIn: https://www.linkedin.com/in/tamil-venthan4  
- GitHub: https://github.com/Tamil-Venthan  

---

## License

This project is licensed under the **MIT License**.

You are free to:
- Use  
- Modify  
- Distribute  
- Fork  

---

## Contributions

Contributions, issues, and feature requests are welcome.

If you find this project useful:
- ⭐ Star the repository  
- 🍴 Fork it  
- 🧠 Share feedback or ideas  

---

Built with a focus on **reliability, clarity, and real-world usage**.

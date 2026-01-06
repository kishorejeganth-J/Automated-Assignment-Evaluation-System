# Automated Assignment Evaluation System

## Project Overview
This project is an automated system that evaluates student assignment PDFs submitted through a Telegram bot.  
It extracts text from the uploaded PDF, evaluates the assignment using rule-based logic, assigns marks, and sends a structured evaluation report back to the student automatically.

The system is built using no-code workflow automation and does not rely on paid AI APIs, making it reliable, cost-effective, and suitable for academic use.

---

## Problem Statement
Manual evaluation of assignments is time-consuming and repetitive. Faculty members need to download assignments, read them individually, and assign marks manually.

This project automates the assignment evaluation process and provides instant feedback to students.

---

## Features
- Assignment submission via Telegram Bot
- Automatic file download and cloud storage
- PDF text extraction
- Rule-based evaluation using workflow routing
- Automatic score assignment (8/10, 7/10, 5/10)
- Structured evaluation report generation
- Instant response back to Telegram

---

## Technologies Used
- Make (Integromat)
- Telegram Bot API
- PDF.co
- OneDrive
- Workflow Router and Filters

---

## Evaluation Logic
Assignments are evaluated based on extracted text length:

- More than 1500 characters → **8/10**
- Between 800 and 1500 characters → **7/10**
- Less than or equal to 800 characters → **5/10**

This logic is implemented using router paths and filters in Make.

---

## Workflow Explanation
1. Student uploads assignment PDF to Telegram bot  
2. The file is downloaded automatically  
3. PDF is stored in OneDrive  
4. Text is extracted from the PDF  
5. Router decides the evaluation path  
6. Evaluation report is generated  
7. Result is sent back to Telegram  

---

## Project Structure
- `workflow/` – Make scenario blueprint (JSON)
- `screenshots/` – Workflow and output screenshots
- `docs/` – Project documentation

---

## Outcome
- Fully automated assignment evaluation
- No manual intervention required
- Fast and consistent scoring
- Stable and free solution without AI quota limits

---

## Future Enhancements
- AI-based semantic evaluation
- Plagiarism detection
- Faculty dashboard
- Grade-based evaluation system

---

## Conclusion
This project demonstrates how workflow automation can be used to solve real-world academic problems efficiently.  
It showcases automation logic, document processing, and system integration using no-code tools.

---

## Author
**KISHORE JEGANTH J**
